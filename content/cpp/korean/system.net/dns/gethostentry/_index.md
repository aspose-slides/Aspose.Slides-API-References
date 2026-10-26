---
title: GetHostEntry()
second_title: Aspose.Slides C++ API 레퍼런스
description: 지정된 문자열(호스트 이름 또는 IP 주소를 포함)을 사용하여 새로운 IPHostEntry-class 인스턴스를 생성합니다.
type: docs
weight: 79
url: /ko/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) 메서드

지정된 문자열(호스트 이름 또는 IP 주소를 포함)을 사용하여 새로운 IPHostEntry 클래스 인스턴스를 생성합니다.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | 호스트 이름 또는 IP 주소를 포함하는 문자열입니다. |

### 반환 값

새로 생성된 IPHostEntry 클래스 인스턴스.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) 메서드

지정된 IP 주소를 사용하여 새로운 IPHostEntry 클래스 인스턴스를 생성합니다.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP 주소입니다. |

### 반환 값

새로 생성된 IPHostEntry 클래스 인스턴스.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPHostEntry](../../iphostentry/)
* 클래스 [String](../../../system/string/)
* 클래스 [Dns](../)
* 클래스 [IPAddress](../../ipaddress/)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)