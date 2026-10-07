# 대화 영작 훈련

Claude가 회사·식당·공항·상점·파티·관공서 등 일상 상황의 한국어 대화를 만들고, 대화 중간의 한 문장(하이라이트)을 영어로 옮기면 채점합니다.

- 대학 졸업 이상 원어민 수준의 모범 답안과 다른 표현
- 100점 만점 채점(의미 40 · 자연스러움 30 · 문법 20 · 어조 10)
- 고칠 점(원래 표현 → 개선 표현, 이유)과 기억할 표현
- 기준 점수 미만 문장은 복습 노트에 저장해 세 문제마다 다시 출제

## 사용법

1. GitHub Pages 주소로 접속합니다.
2. 처음 한 번 [Anthropic API 키](https://console.anthropic.com/settings/keys)를 입력합니다.
3. 설정에서 상황, 난이도, 복습 기준 점수, 모델(Opus 5.5 / Sonnet 5.5 / Haiku 4.5)을 고를 수 있습니다.

## 저장 위치와 기기 간 동기화

API 키와 GitHub 토큰은 **사용하는 브라우저의 localStorage**에만 저장되고, 각각 `api.anthropic.com`과 `api.github.com`으로만 전송됩니다.

복습 노트와 통계도 기본적으로 브라우저에 저장됩니다. 설정의 ‘기기 간 동기화’에 [gist 권한만 있는 GitHub 토큰](https://github.com/settings/tokens/new?scopes=gist&description=eng-composition%20sync)을 넣으면, 내 계정의 비공개 Gist(`eng-composition-data.json`) 하나에 저장되어 PC와 휴대폰이 같은 복습 노트를 봅니다. 접속할 때, 채점·삭제할 때, 앱으로 돌아올 때마다 자동으로 합쳐집니다.

단일 파일(`index.html`)이며 빌드 과정이 없습니다.
