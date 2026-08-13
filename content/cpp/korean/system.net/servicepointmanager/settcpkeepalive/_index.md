---
title: SetTcpKeepAlive()
second_title: Aspose.Slides for C++ API 참조
description: 'Keep-Alive' 옵션이 활성화되어 있는지 여부를 나타내는 값을 설정합니다.
type: docs
weight: 326
url: /ko/system.net/servicepointmanager/settcpkeepalive/
---
## ServicePointManager::SetTcpKeepAlive(bool, int32_t, int32_t) 메서드

'Keep-Alive' 옵션이 활성화되어 있는지 여부를 나타내는 값을 설정합니다.

```cpp
static void System::Net::ServicePointManager::SetTcpKeepAlive(bool enabled, int32_t keepAliveTime, int32_t keepAliveInterval)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| enabled | **bool** | 'Keep-Alive' 옵션이 활성화되어 있는지 여부를 나타내는 값. |
| keepAliveTime | **int32_t** | 첫 번째 'Keep-Alive' 패킷이 전송되기 전까지의 밀리초 단위 제한 시간. |
| keepAliveInterval | **int32_t** | 'Keep-Alive' 패킷을 전송하는 사이의 밀리초 단위 제한 시간. |

## 참조

* 클래스 [ServicePointManager](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)