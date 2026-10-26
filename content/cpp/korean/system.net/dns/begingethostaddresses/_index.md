---
title: BeginGetHostAddresses()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자열(호스트 이름 또는 IP 주소를 포함)을 사용하여 새로운 IPHostEntry-class 인스턴스를 생성하는 비동기 작업을 시작합니다.
type: docs
weight: 131
url: /ko/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) 메서드

지정된 문자열(호스트 이름 또는 IP 주소를 포함)을 사용하여 새로운 IPHostEntry-class 인스턴스를 생성하는 비동기 작업을 시작합니다.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | 호스트 이름 또는 IP 주소를 포함하는 문자열. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 작업을 고유하게 식별하기 위해 사용자가 제공한 데이터. |

### 반환값

시작된 비동기 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체입니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [String](../../../system/string/)
* 클래스 [Object](../../../system/object/)
* 클래스 [Dns](../)
* 네임스페이스 [System::Net](../../)
* Library [Aspose.Slides](../../../)