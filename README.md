# k-labor for Gemini CLI
일의 무늬의 한국어 노동 도구를 Gemini CLI에 연결합니다. 이 초기 버전은 공휴일 근로 수당 계산과 모성보호 서식 목록 조회만 제공합니다.

## 설치
```sh
gemini extensions install https://github.com/seojaehong/k-labor-gemini
```

새 세션에서 `/mcp`로 `k-labor` 연결을 확인합니다. 예시: “월 통상임금 2,508,000원, 월 209시간, 5인 이상, 관공서 공휴일 8시간 근무, 야간근로 없음. k-labor로 월급 외 추가 금액을 계산해 줘.” 합성 예시의 기대값은 144,000원입니다.

입력은 일의 무늬 서버로 전송됩니다. 실제 근로자나 고객을 식별할 수 있는 정보는 입력하지 마세요. 계산 조건과 공식 자료를 확인한 후 실무에 사용하세요. 법률 자문 또는 신고 제출 도구가 아닙니다.

- [일의 무늬 AI 도구](https://yellowenvelope.kr/ai-tools)
- [개인정보처리방침](https://yellowenvelope.kr/privacy) · [이용약관](https://yellowenvelope.kr/terms) · [문의](https://yellowenvelope.kr/contact)

This extension is for Gemini CLI, not the consumer Gemini app.
