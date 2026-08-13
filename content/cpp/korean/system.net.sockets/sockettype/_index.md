---
title: SocketType
second_title: Aspose.Slides for C++ API 참조
description: 소켓 유형을 열거합니다.
type: docs
weight: 131
url: /ko/system.net.sockets/sockettype/
---
## SocketType 열거형

소켓 유형을 열거합니다.

```cpp
enum class SocketType
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Stream | 1 | 데이터 중복 및 경계 보존 없이 신뢰성 있는 양방향, 연결 기반 byte streams를 지원하는 타입. |
| Dgram | 2 | 고정된 최대 길이의 연결 비없음, 신뢰성 없는 메시지인 datagrams를 지원하는 타입. |
| Raw | 3 | 기본 transport protocol에 대한 접근을 지원하는 타입. |
| Rdm | 4 | 연결 비없음, 메시지 지향, 신뢰성 있게 전달되는 메시지를 지원하고 데이터의 메시지 경계를 보존하는 타입. |
| Seqpacket | 5 | 네트워크를 통한 순서가 지정된 byte streams의 연결 지향적이며 신뢰성 있는 양방향 전송을 제공하는 타입. |
| Unknown | n/a | 알 수 없는 타입. |

## 참조

* 네임스페이스 [System::Net::Sockets](../)
* 라이브러리 [Aspose.Slides](../../)