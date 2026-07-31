---
layout: home

hero:
  name: "ELLA'S 1DAY WORKSHOP"
  text: "AI-Native 업무 자동화"
  tagline: "오늘 워크숍이 끝나면, 시니어 시장을 국내·해외로 대신 조사해주는 리서치 봇이 손에 있을 거예요!"
  actions:
    - theme: brand
      text: 시작하기
      link: /prologue
    - theme: alt
      text: 강사 소개
      link: /part1/0-host

features:
  - icon: 🤖
    title: "1-1. 클로드 코드란?"
    details: "보통 챗봇과 뭐가 다른지 · AI-Native 마인드셋"
    link: /part1/1-1-intro
    linkText: 열기
  - icon: ⌨️
    title: "1-2. 명령어 익히기"
    details: "슬래시 명령어 · 대화로 시키고 고치기"
    link: /part1/1-2-commands
    linkText: 열기
  - icon: 🚀
    title: "1-3. 자동화, 어디까지?"
    details: "강사 에이전트의 리서치·제안·콘텐츠 실물 쇼케이스"
    link: /part1/1-3-showcase
    linkText: 열기
  - icon: ✨
    title: "1-4. 자동화 맛보기 : 시니어 리서치 봇 첫 실행"
    details: "⭐ 오늘의 하이라이트 — 국내·해외 비교 브리프 · 기회 카드 · 주간 리포트"
    link: /part1/1-4-agent
    linkText: 열기
  - icon: 🧩
    title: "2-1. 에이전트"
    details: "에이전트 · 서브에이전트 · 오케스트레이션 3가지 개념"
    link: /part2/2-1-agents
    linkText: 열기
  - icon: 📋
    title: "2-2. PRD (제품 요구사항 문서)"
    details: "AI에게 주는 업무 지시서 · PRD 요청법 · CLAUDE.md 활용법"
    link: /part2/2-2-prd
    linkText: 열기
  - icon: 🛡️
    title: "2-3. 하네스 엔지니어링"
    details: "Generator/Evaluator — 출처 없는 숫자를 걸러내는 구조"
    link: /part2/2-3-harness
    linkText: 열기
  - icon: 🔁
    title: "2-4. 루프 엔지니어링"
    details: "⭐ 네 가지 루프 — 무엇을 쥐고 무엇을 맡길 것인가"
    link: /part2/2-4-loop
    linkText: 열기
---

## 워크북 사용법

이 워크북은 **직접 따라하며 배우는 실습 중심** 자료입니다.

### 구조
- **[개념]** — 읽고 이해하는 파트
- **[실습]** — 직접 수행하는 파트 (슬래시 커맨드 호출)
- **[체크포인트]** — 진행 상황 확인 + 주요 마일스톤

### 소요시간
약 **3시간** (프롤로그 5분 + Part 1 기초·리서치 봇 실행 + Part 2 개념·실무)

### 사전 준비물
- 노트북, 인터넷 연결
- 클로드 코드 설치 (Pro/Max 구독) — 이미 설치돼 있어도 OK, 무엇을 시킬지가 핵심이에요
- **조사해보고 싶은 시니어 주제 2~3개** — "시니어 주거", "시니어 식품", "시니어 여행"처럼 러프해도 괜찮아요. 떠오르지 않으시면 봇이 샘플을 제안해드립니다.

::: tip 준비물이 가벼운 이유
리서치 봇은 **웹에서 직접 조사**합니다. 나리님이 자료를 모아 오실 필요가 없어요. 주제만 던져주시면 됩니다.
:::

### 학습 모드
- 프롬프트가 완벽하지 않아도 괜찮습니다. 봇은 **클로드 코드와의 대화로 언제든 수정**할 수 있어요.
- 모르는 부분 있으면 멈추고 물어보세요.
- 봇이 만든 브리프·리포트는 `output/` 폴더에 쌓입니다. 워크숍이 끝나도 그대로 남아요.
