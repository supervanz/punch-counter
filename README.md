# Punch Counter Precision

마이크 하나로 샌드백 타격 횟수를 실시간으로 측정하는 웹 앱입니다.
A web app that counts sandbag punches in real time using only a microphone.

---

## 한국어

### 바로 사용하기

👉 **[https://your-username.github.io/punch-counter/](https://your-username.github.io/punch-counter/)**

설치 불필요. 링크를 열고 마이크 권한만 허용하면 됩니다.
스마트폰, 태블릿, PC 브라우저 모두 지원합니다.

> Chrome 또는 Safari 최신 버전 권장

---

### 사용 방법

1. 위 링크를 브라우저로 엽니다
2. 마이크 권한 요청이 뜨면 **허용**을 누릅니다
3. 운동 시간 프리셋(5 / 10 / 15 / 30분)을 선택합니다
4. 체중을 입력합니다 (칼로리 계산에 사용)
5. **운동 시작** 버튼을 누르고 샌드백을 칩니다

| 버튼 | 동작 |
|------|------|
| 운동 시작 | 마이크 켜기 → 타이머 시작 |
| PAUSE | 일시정지 |
| RESUME | 재개 |
| STOP | 세션 초기화 (기록 저장 없음) |
| 타이머 만료 | 자동 저장 후 종료 |

---

### 조정 팁

- **타격 임계값** — 주변이 시끄러우면 값을 올리세요 (기본값: 35)
- **타격 간격(쿨다운)** — 빠른 연타가 잘 안 잡히면 값을 내리세요 (기본값: 180ms)

---

### 주요 기능

- 설치 없이 URL 하나로 즉시 사용
- 타격 횟수 · 운동 시간 · 소모 칼로리 실시간 표시
- 최근 5건 운동 기록 자동 저장 (기기 내 브라우저에만 저장, 서버 전송 없음)
- 마이크 입력만 사용 — 별도 센서 불필요

---

## English

### Try It Now

👉 **[https://your-username.github.io/punch-counter/](https://your-username.github.io/punch-counter/)**

No install. No app store. Just open the link, allow microphone access, and start punching.
Works on smartphones, tablets, and desktop browsers.

> Recommended: Latest version of Chrome or Safari

---

### How to Use

1. Open the link above in your browser
2. Tap **Allow** when prompted for microphone access
3. Select a session duration (5 / 10 / 15 / 30 min)
4. Enter your body weight (used for calorie calculation)
5. Press **운동 시작** (Start) and hit the bag

| Button | Action |
|--------|--------|
| 운동 시작 (Start) | Enable mic → start timer |
| PAUSE | Pause session |
| RESUME | Resume session |
| STOP | Reset session (no save) |
| Timer end | Auto-save and finish |

---

### Tuning Tips

- **Threshold** — Raise this if you're in a noisy environment (default: 35)
- **Cooldown** — Lower this if fast combos aren't being counted (default: 180ms)

---

### Features

- Zero install — works instantly from a URL on any device
- Real-time punch count, timer, and calorie display
- Last 5 sessions saved automatically (stored locally in your browser only — nothing is sent to a server)
- Microphone only — no extra hardware needed

---

### Privacy

All audio processing happens entirely in your browser. No sound data, personal data, or workout history is transmitted to any server.

---

### Tech

Web Audio API · AudioWorklet · Vanilla JS · No dependencies · No backend
