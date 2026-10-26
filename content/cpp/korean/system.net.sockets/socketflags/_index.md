---
title: SocketFlags
second_title: Aspose.Slides for C++ API 참조
description: 소켓 메시지에 대한 상수 값을 제공합니다.
type: docs
weight: 222
url: /ko/system.net.sockets/socketflags/
---
## SocketFlags enum

소켓 메시지에 대한 상수 값을 제공합니다.

```cpp
enum class SocketFlags
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | 0 | 이 호출에 사용된 플래그가 없습니다. |
| OutOfBand | 1 | 대역외 데이터가 처리되고 있습니다. |
| Peek | 2 | 수신 메시지를 엿봅니다. |
| DontRoute | 4 | 라우팅 테이블을 사용하지 않고 메시지를 보냅니다. |
| Truncated | 256 | 메시지가 지정된 버퍼에 맞기에는 너무 큽니다. 잘려서 전송되었습니다. |
| ControlDataTruncated | 512 | 제어 데이터가 64KB보다 커서 내부 버퍼에 맞지 않습니다. 잘려서 전송되었습니다. |
| Broadcast | 1024 | 브로드캐스트 패킷. |
| Multicast | 2048 | 멀티캐스트 패킷. |
| Partial | 32768 | 부분적으로 전송되거나 수신된 메시지. |

## 참고

* 네임스페이스 [System::Net::Sockets](../)
* 라이브러리 [Aspose.Slides](../../)