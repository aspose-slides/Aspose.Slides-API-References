---
title: EndGetHostAddresses()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 비동기 작업이 새 IPHostEntry-class 인스턴스를 생성할 때까지 기다립니다.
type: docs
weight: 144
url: /ko/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) 메서드

지정된 비동기 작업이 새 IPHostEntry-class 인스턴스를 생성할 때까지 기다립니다.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 비동기 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 개체. |

### 반환 값

새로 생성된 IPHostEntry-class 인스턴스.

## 관련 항목

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPAddress](../../ipaddress/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [Dns](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)