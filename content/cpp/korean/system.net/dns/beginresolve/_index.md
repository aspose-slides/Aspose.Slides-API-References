---
title: BeginResolve()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 호스트 이름을 사용하여 새로운 IPHostEntry-class 인스턴스를 만들기 위한 비동기 작업을 시작합니다.
type: docs
weight: 157
url: /ko/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) 메서드


지정된 호스트 이름을 사용하여 새로운 IPHostEntry-class 인스턴스를 만들기 위한 비동기 작업을 시작합니다.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | 새로운 [IPHostEntry](../../iphostentry/) class 인스턴스를 만드는 데 사용되는 호스트 이름. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 작업이 완료될 때 호출되는 콜백. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 각 비동기 작업을 고유하게 식별하는 데 사용되는 사용자 제공 데이터. |

### 반환 값

시작된 비동기 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체.

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 타입 정의 [AsyncCallback](../../../system/asynccallback/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [String](../../../system/string/)
* 클래스 [Object](../../../system/object/)
* 클래스 [Dns](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)