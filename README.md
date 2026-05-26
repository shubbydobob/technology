# Technology Notes

기술면접과 CS 개념을 카테고리별로 정리하는 정적 웹사이트입니다.

## 사이트 구성

이 저장소는 `index.html` 기반 정적 사이트입니다. 메인 페이지에서 운영체제, 네트워크, 백엔드, 인프라, Spring 카테고리로 이동할 수 있습니다.

| 카테고리 | 포함된 주제 |
|---|---|
| 운영체제 | `.inf란 무엇인가?`, `리눅스란 무엇인가?` |
| 네트워크 | `TCP란 무엇인가?`, `IoT란 무엇인가?`, `DNS란 무엇인가?`, `MQTT란 무엇인가?`, `WebSocket이란 무엇인가?`, `포트 포워딩이란 무엇인가?`, `SSH란 무엇인가?`, `터널링이란 무엇인가?` |
| 백엔드 | `WAS란 무엇인가?` |
| 인프라 | `EC2란 무엇인가?` |
| Spring | `MVC란 무엇인가?`, `DTO란 무엇인가?`, `RequestBody란 무엇인가?`, `RestController와 Controller 차이` |

## 배포

이 저장소는 별도 빌드 과정이 없는 정적 사이트입니다. Vercel에서 GitHub 저장소를 Import하면 그대로 배포할 수 있습니다.

권장 Vercel 설정:

- Framework Preset: `Other`
- Build Command: 비움
- Output Directory: `.`
