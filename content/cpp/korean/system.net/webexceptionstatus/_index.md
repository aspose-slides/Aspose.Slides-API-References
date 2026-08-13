---
title: WebExceptionStatus
second_title: Aspose.Slides for C++ API 레퍼런스
description: WebException 클래스의 상태 코드를 열거합니다.
type: docs
weight: 651
url: /ko/system.net/webexceptionstatus/
---
## WebExceptionStatus 열거형


WebException 클래스의 상태 코드를 열거합니다.

```cpp
enum class WebExceptionStatus
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Success | 0 | 오류가 발생하지 않았습니다. |
| NameResolutionFailure | 1 | 이름 확인 서비스가 호스트 이름을 확인할 수 없습니다. |
| ConnectFailure | 2 | 전송 단계에서 원격 서비스 지점에 연결할 수 없습니다. |
| ReceiveFailure | 3 | 원격 서버로부터 전체 응답을 받지 못했습니다. |
| SendFailure | 4 | 전체 요청을 원격 서버에 보낼 수 없습니다. |
| PipelineFailure | 5 | 요청은 파이프라인 방식이었으며 응답을 받기 전에 연결이 닫혔습니다. |
| RequestCanceled | 6 | 요청이 취소되었거나 분류할 수 없는 오류가 발생했습니다. |
| ProtocolError | 7 | 서버에서 받은 응답은 완전했지만 프로토콜 수준의 오류를 나타냈습니다. |
| ConnectionClosed | 8 | 연결이 조기에 닫혔습니다. |
| TrustFailure | 9 | 서버 인증서를 검증할 수 없습니다. |
| SecureChannelFailure | 10 | SSL을 사용하여 연결을 설정하는 중 오류가 발생했습니다. |
| ServerProtocolViolation | 11 | 서버 응답이 유효한 HTTP 응답이 아닙니다. |
| KeepAliveFailure | 12 | 'Keep-Alive' 헤더를 지정한 요청의 연결이 예기치 않게 닫혔습니다. |
| Pending | 13 | 내부 비동기 요청이 대기 중입니다. |
| Timeout | 14 | 요청에 대한 시간 초과 기간 동안 응답을 받지 못했습니다. |
| ProxyNameResolutionFailure | 15 | 이름 확인 서비스가 프록시 호스트 이름을 확인할 수 없습니다. |
| UnknownError | 16 | 알 수 없는 유형의 예외가 발생했습니다. |
| MessageLengthLimitExceeded | 17 | 지정된 제한을 초과한 메시지를 받았습니다. |
| CacheEntryNotFound | 18 | 지정된 캐시 항목을 찾을 수 없습니다. |
| RequestProhibitedByCachePolicy | 19 | 요청이 캐시 정책에 의해 허용되지 않았습니다. |
| RequestProhibitedByProxy | 20 | 이 요청은 프록시에 의해 허용되지 않았습니다. |

## 참조

* 네임스페이스 [System::Net](../)
* 라이브러리 [Aspose.Slides](../../)