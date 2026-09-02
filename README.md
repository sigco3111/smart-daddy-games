<div align="center">

# 🎮 스마트대디 게임 모음

**Claude Fable 5.1로 생성한 3D 웹 게임 3종을 한 곳에서 플레이하세요.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-06d6a0?style=for-the-badge&logo=github&logoColor=white)](https://sigco3111.github.io/smart-daddy-games/)
[![Made With](https://img.shields.io/badge/Made%20With-Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)](https://threejs.org/)
[![AI Generated](https://img.shields.io/badge/AI-Claude%20Fable%205.1-d97706?style=for-the-badge&logo=anthropic&logoColor=white)](https://www.youtube.com/watch?v=MqspiD73wPI)
[![Games](https://img.shields.io/badge/Games-3%20Titles-ef476f?style=for-the-badge)](#-게임-목록)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](#-라이선스)

</div>

---

## 📑 목차

- [✨ 프로젝트 소개](#-프로젝트-소개)
- [🌐 라이브 데모](#-라이브-데모)
- [🎮 게임 목록](#-게임-목록)
  - [🦖 공룡 막아라! — Dino Siege](#-공룡-막아라--dino-siege)
  - [🐺 붉은 맹약 3D — Chapter 1](#-붉은-맹약-3d--chapter-1)
  - [🚗 SMART THEFT AUTO — 한강시티](#-smart-theft-auto--한강시티)
- [📺 원본 출처](#-원본-출처)
- [🚀 로컬 실행](#-로컬-실행)
- [🗂️ 프로젝트 구조](#-프로젝트-구조)
- [🛠️ 기술 스택](#-기술-스택)
- [🤖 제작 과정](#-제작-과정)
- [🎯 특징](#-특징)
- [📜 라이선스](#-라이선스)

---

## ✨ 프로젝트 소개

**스마트대디 게임 모음**은 단일 랜딩페이지에서 3개의 3D 웹 게임을 바로 플레이할 수 있도록 만든 **게임 쇼케이스 사이트**입니다.

이 페이지에 포함된 모든 게임은 Anthropic의 **Claude Fable 5.1** 모델이 단일 프롬프트만으로 생성한 결과물입니다. 별도의 설치나 회원가입 없이 브라우저만 있으면 즉시 플레이할 수 있습니다.

| 항목 | 내용 |
|------|------|
| 🎮 **게임 수** | 3종 (타워 디펜스 · 시네마틱 · 오픈월드) |
| 🌐 **배포** | GitHub Pages |
| 💾 **총 용량** | 약 7.4 MB |
| ⚙️ **엔진** | Three.js (WebGL) |
| 🤖 **AI 모델** | Claude Fable 5.1 |

---

## 🌐 라이브 데모

> ### 👉 [https://sigco3111.github.io/smart-daddy-games/](https://sigco3111.github.io/smart-daddy-games/)

랜딩페이지에서 **"바로 플레이"** 버튼을 누르면 모달로 게임이 즉시 로드되며, **ESC** 또는 모달 외곽 클릭으로 종료할 수 있습니다.

---

## 🎮 게임 목록

### 🦖 공룡 막아라! — Dino Siege

> **장르**: 3D 타워 디펜스 · **파일**: [`dino-siege.html`](./dino-siege.html) · **용량**: 7.2 MB

스테이지가 진행될수록 강해지는 공룡 웨이브를 막아내는 3D 타워 디펜스. 타워 종류를 선택하고 웨이브를 시작하면, 공룡들이 웨이브 단위로 몰려옵니다. 최종 보스는 **티라노사우루스**.

**핵심 게임 요소**
- 🦖 다양한 공룡 종류 (일반 공룡 + 보스급)
- 🏗️ 타워 종류 선택 → 배치 → 업그레이드
- ⚡ 액티브 아이템 사용 (운석 · 빙하기 · 목책 보수 등)
- 🌊 웨이브 시스템 + 속도 조절
- 🏆 보스전 (티라노사우루스)

**플레이 팁**
1. 시작 화면에서 타워를 선택하세요.
2. **"웨이브 시작"** 버튼을 눌러 첫 라운드를 시작합니다.
3. 클리어 후 아이템 선택지로 강화할 수 있습니다.
4. 속도 조절 슬라이더로 게임 템포를 바꿔보세요.

---

### 🐺 붉은 맹약 3D — Chapter 1

> **장르**: 3D 시네마틱 / 스토리 · **파일**: [`red-pact-3d.html`](./red-pact-3d.html) · **용량**: 124 KB

국경의 늑대들. 붉은 맹약 시리즈의 첫 챕터를 3D로 체험하는 인터랙티브 시네마틱 단편입니다.

**핵심 게임 요소**
- 🎬 자동 연출되는 3D 시네마틱
- 🐺 늑대와 인간, 국경 지대를 배경으로 한 서사
- 📷 카메라·조명이 장면에 맞춰 자동 전환
- 🎮 키 입력으로 인터랙티브하게 진행

---

### 🚗 SMART THEFT AUTO — 한강시티

> **장르**: 3D 오픈월드 (GTA 풍) · **경로**: [`SMART_THEFT_AUTO_HangangCity/`](./SMART_THEFT_AUTO_HangangCity/) · **용량**: 149 KB

한강을 끼고 도심·변두리·컨테이너 야드까지 돌아다니는 3D 오픈월드. 차량 탑승, 사격, 라디오 채널 변경 등 자유도가 높은 게임입니다.

**기본 조작법**

| 키 | 동작 |
|---|---|
| `W` `A` `S` `D` | 이동 / 운전 |
| `마우스` | 시점 |
| `좌클릭` | 사격 |
| `E` | 차량 탑승 / 하차 |
| `Space` | 점프 / 핸드브레이크 |
| `Shift` | 달리기 |
| `1` `2` `3` | 무기 교체 |
| `R` | 라디오 채널 변경 / OFF |
| `C` | 조작법 보기 |
| `P` | 일시정지 |

**게임 시스템**
- ⭐ 범죄를 저지르면 **별(추격 등급)** 이 올라가고 경찰이 추격합니다.
- 🚁 **4성부터 경찰 헬기**가 출동합니다.
- 💚 초록 총 마커에 가면 **체력과 로켓 탄약을** 보급받을 수 있습니다.
- 🎵 시작하면 **SMART FM 신스웨이브** 배경음악이 자동으로 깔립니다 (`R` 키로 변경/OFF).

> ⚠️ **주의**: 키보드가 한글 입력 상태면 조작이 잘 안 될 수 있으니 **영문 입력 상태**로 바꿔주세요.

---

## 📺 원본 출처

이 페이지의 모든 게임은 아래 유튜브 영상의 시연 결과를 직접 받아 **그대로 웹에 올린** 것입니다.

<div align="center">

[![YouTube Video](https://img.shields.io/badge/YouTube-클로드%20Fable%205.1%20그냥%20미쳤습니다...-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=MqspiD73wPI)

</div>

| 항목 | 내용 |
|------|------|
| 📺 **채널 / 영상** | 클로드 Fable 5.1 그냥 미쳤습니다... |
| 🔗 **URL** | https://www.youtube.com/watch?v=MqspiD73wPI |
| 🎬 **시연 항목** | 공룡 3D 타워 디펜스 (1시간 30분, 약 $64 API 환산) |
| 🤖 **AI 모델** | Anthropic Claude Fable 5.1 |

**영상에서 시연된 결과**
- 공룡 디펜스 게임은 **단일 프롬프트**("3D 타워 디펜스 게임 만들어 줘. 3.js 기반으로 하고 몰입도 있는 웹 게임을 만들어 줘")로 생성됨
- 약 **1시간 30분** 소요, **약 $64** (API 환산 비용)
- 다른 모델(GPT 5.6 솔 울트라)과 비교 시 페이블이 **속도·비용·완성도** 모두 우위였음을 영상에서 강조

---

## 🚀 로컬 실행

이 레포는 빌드 단계가 없습니다. 정적 HTML이므로 그대로 더블 클릭하거나, 로컬 서버를 띄우면 됩니다.

### 방법 1. 그냥 열기

```bash
open "/Users/mac/Downloads/스마트대디_landing/index.html"
```

### 방법 2. 로컬 서버 (권장)

일부 브라우저는 `file://` 프로토콜에서 모듈 로딩·CORS를 제한할 수 있으므로, 로컬 서버 권장:

```bash
cd "/Users/mac/Downloads/스마트대디_landing"
python3 -m http.server 8000
```

그 다음 브라우저에서 [http://localhost:8000](http://localhost:8000) 접속.

### 권장 환경

| 항목 | 권장 |
|------|------|
| 🌐 **브라우저** | Chrome / Edge 최신판 |
| 🖥️ **해상도** | 1280×720 이상 |
| 💾 **메모리** | 4 GB 이상 |
| 🌐 **네트워크** | 첫 로딩 시 CDN(Three.js 등) 다운로드 필요 |

---

## 🗂️ 프로젝트 구조

```
smart-daddy-games/
├── 📄 index.html                                # 랜딩페이지 (게임 카드 + 모달 뷰어)
├── 🦖 dino-siege.html                           # 공룡 막아라! Dino Siege (단일 HTML)
├── 🐺 red-pact-3d.html                          # 붉은 맹약 3D Chapter 1 (단일 HTML)
└── 📁 SMART_THEFT_AUTO_HangangCity/
│   └── 📄 index.html                            # SMART THEFT AUTO 한강시티
├── 📄 .gitignore                                # macOS .DS_Store 등 제외
└── 📄 README.md                                 # 본 문서
```

**원칙**: 빌드 도구·번들러 없음. 각 게임은 **단일 HTML 파일**로 임베드 가능하도록 설계되었습니다 (`<iframe>` 모달 패턴).

---

## 🛠️ 기술 스택

### 프론트엔드 (랜딩페이지)
- HTML5
- CSS3 (Custom Properties, Grid, Flexbox, 모달)
- Vanilla JavaScript (iframe 모달 트리거, 키보드 단축키)
- 반응형 (모바일 1열 / 데스크탑 3열)

### 게임 내부 (3개 게임 공통)
- **Three.js** — WebGL 3D 렌더링
- **WebGL** — GPU 가속
- 외부 이미지·모델 에셋 (게임별로 상이)

### 배포
- **GitHub Pages** (legacy, gh-pages 브랜치)

---

## 🤖 제작 과정

1. **자료 수집** — 유튜브 영상 "클로드 Fable 5.1 그냥 미쳤습니다..." 첨부 파일로 게임 3종 HTML 확보
2. **게임 검증** — 각 HTML의 `<title>` 추출, 파일 크기·구조 확인
3. **랜딩페이지 설계** — 다크 테마 + 게임 카드 그리드 + 모달 게임 뷰어
4. **영상 출처 명시** — 유튜브 썸네일 + 링크 + 영상 정보 카드
5. **GitHub 배포** — public repo 생성 → `npx gh-pages -d .` → GitHub Pages 활성화
6. **라이브 검증** — 4개 URL HTTP 200 + 한글 grep + 출처 박힘 확인

---

## 🎯 특징

- ✅ **설치 불필요** — 브라우저만 있으면 바로 플레이
- ✅ **모바일 반응형** — 작은 화면에서도 카드 그리드 정상 동작
- ✅ **모달 게임 뷰어** — 페이지 이동 없이 즉시 게임 실행
- ✅ **키보드 단축키** — `ESC`로 모달 닫기
- ✅ **출처 투명성** — 모든 게임의 원본 영상·모델 정보 명시
- ✅ **단일 HTML 게임** — 별도 빌드·번들 단계 없음
- ✅ **정적 호스팅** — 어떤 정적 호스팅(GitHub Pages, Vercel, Netlify)에서도 동작

---

## 📜 라이선스

본 레포는 **MIT License** 하에 배포됩니다.

### 각 게임의 권리
- 본 랜딩페이지의 HTML/CSS/JS 구조: **MIT License**
- 포함된 3개 게임(`dino-siege.html`, `red-pact-3d.html`, `SMART_THEFT_AUTO_HangangCity/`): **스마트대디** 가 제작한 결과물로, 유튜브 영상을 통해 공개된 결과물의 배포 형식을 따릅니다.
- 영상 원본 권리는 **해당 영상 제작자**에게 있습니다.

자세한 권리·재배포 문의는 이슈로 남겨 주세요.

---

<div align="center">

**[⬆ 맨 위로](#-스마트대디-게임-모음)** · **[🌐 라이브 데모](https://sigco3111.github.io/smart-daddy-games/)** · **[📺 원본 영상](https://www.youtube.com/watch?v=MqspiD73wPI)**

<sub>Made with ❤️ by <strong>스마트대디</strong> · Published by <strong>sigco3111</strong></sub>

</div>