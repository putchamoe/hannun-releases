# 한눈 (Hannun) — 웹 배포판

macOS 용 마크다운 뷰어 **한눈**의 웹 배포 채널임. 앱 소스는 별도 비공개 저장소에 있고, 이 저장소는 **배포물과 업데이트 피드만** 담음.

| 항목 | 주소 |
|---|---|
| 내려받기 | [Releases](https://github.com/putchamoe/hannun-releases/releases) |
| 업데이트 피드 | `https://putchamoe.com/hannun-releases/appcast.xml` |

## 구성

- `appcast.xml` — Sparkle 업데이트 피드. GitHub Pages 로 서빙됨
- `.dmg` — Releases 에 올림. Pages 에는 두지 않음 (대용량 파일은 Releases 가 맞음)

## 서명

각 판은 EdDSA 로 서명되며, 서명은 `appcast.xml` 의 `sparkle:edSignature` 에 실림. 개인 키는 배포자의 키체인에만 있고 이 저장소에 없음.

## 라이선스

배포되는 바이너리의 서드파티 고지는 앱 안 `한눈 › 한눈에 관하여 › 고지 사항` 에 있음.
