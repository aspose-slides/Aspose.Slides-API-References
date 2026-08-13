---
title: Poll()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 폴링 모드에 따라 소켓의 상태를 반환합니다.
type: docs
weight: 742
url: /ko/system.net.sockets/socket/poll/
---
## Socket::Poll(int32_t, SelectMode) 메서드

지정된 폴링 모드에 따라 소켓의 상태를 반환합니다.

```cpp
bool System::Net::Sockets::Socket::Poll(int32_t microSeconds, SelectMode mode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| microSeconds | **int32_t** | 응답을 기다리는 시간(밀리초)입니다. |
| mode | [SelectMode](../../selectmode/) | 폴링 모드입니다. |

### 반환 값

지정된 폴링 모드에 따라 소켓의 상태입니다.

## 참고

* 열거형 [SelectMode](../../selectmode/)
* 클래스 [Socket](../)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)