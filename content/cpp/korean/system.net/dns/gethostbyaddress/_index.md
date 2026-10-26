---
title: GetHostByAddress()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 IP 주소의 문자열 표현을 사용하여 새로운 IPHostEntry-class 인스턴스를 생성합니다.
type: docs
weight: 14
url: /ko/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) 메서드

지정된 IP 주소의 문자열 표현을 사용하여 새로운 IPHostEntry-class 인스턴스를 생성합니다.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| address | [String](../../../system/string/) | IP 주소의 문자열 표현. |

### 반환값

새로 생성된 IPHostEntry-class 인스턴스.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) 메서드

지정된 IP 주소를 사용하여 새로운 IPHostEntry-class 인스턴스를 생성합니다.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP 주소. |

### 반환값

새로 생성된 IPHostEntry-class 인스턴스.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [String](../../../system/string/)
* Class [Dns](../)
* Class [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)