---
title: BeginGetHostEntry()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문자열(호스트 이름 또는 IP 주소를 포함)을 사용하여 새 IPHostEntry-class 인스턴스를 생성하는 비동기 작업을 시작합니다.
type: docs
weight: 105
url: /ko/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) 메서드

지정된 문자열(호스트 이름 또는 IP 주소를 포함) 을 사용하여 새 IPHostEntry-class 인스턴스를 생성하는 비동기 작업을 시작합니다.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | 호스트 이름 또는 IP 주소를 포함하는 문자열. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 작업을 고유하게 식별하는 데 사용되는 사용자 제공 데이터. |

### 반환값

[IAsyncResult](../../../system/iasyncresult/) 객체는 시작된 비동기 작업을 나타냅니다.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) 메서드

지정된 IP 주소를 사용하여 새 IPHostEntry-class 인스턴스를 생성하는 비동기 작업을 시작합니다.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP 주소. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 작업을 고유하게 식별하는 데 사용되는 사용자 제공 데이터. |

### 반환값

[IAsyncResult](../../../system/iasyncresult/) 객체는 시작된 비동기 작업을 나타냅니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [String](../../../system/string/)
* 클래스 [Object](../../../system/object/)
* 클래스 [Dns](../)
* 클래스 [IPAddress](../../ipaddress/)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)