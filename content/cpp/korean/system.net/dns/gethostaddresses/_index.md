---
title: GetHostAddresses()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 호스트 이름 또는 IP 주소의 IP 주소 컬렉션을 반환합니다.
type: docs
weight: 92
url: /ko/system.net/dns/gethostaddresses/
---
## Dns::GetHostAddresses(String) 메서드

지정된 호스트 이름 또는 IP 주소의 IP 주소 컬렉션을 반환합니다.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::GetHostAddresses(String hostNameOrAddress)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | 호스트 이름 또는 IP 주소를 포함하는 문자열. |

### 반환값

IP 주소 컬렉션.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPAddress](../../ipaddress/)
* 클래스 [String](../../../system/string/)
* 클래스 [Dns](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)