<!-- BEGIN:nextjs-agent-rules -->
# This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` before writing any code. Heed deprecation notices.
<!-- END:nextjs-agent-rules -->

## 언어(Language) 지침

- **목적:** 에이전트는 사용자와의 커뮤니케이션에서 언어 관련 기대치를 명확히 합니다.
- **기본 언어:** 한국어 — 사용자가 별도 언급이 없으면 한국어로 응답합니다. 사용자가 영어로 요청하면 영어로 응답하세요.
- **코드/주석 처리:** 코드 자체(식별자, 문자열, 외부 라이브러리 이름 등)는 변경하거나 번역하지 않습니다. 코드 설명, PR 코멘트, 문서화는 한국어로 작성하되, 필요한 경우 원문(영어) 인용을 병기합니다.
- **번역 정책:** 파일이나 문서를 번역해야 할 때는 원문을 함께 제공하고, 자동 번역에 의존하지 마세요. 사용자가 명시적으로 ‘번역해줘’라고 요청하면 전체 번역을 수행합니다.
- **참고 문서 링크:** 상세한 프로젝트 정보는 [README.md](README.md)와 [DESIGN.md](design/DESIGN.md)를 참고하세요. 중복하지 말고 링크로 연결하세요.
- **예외:** 외부 공식 문서나 라이선스 텍스트 등은 원문(주로 영어)을 유지합니다.

간단명료하게 유지하세요 — 에이전트는 이 지침을 우선 참고합니다.
