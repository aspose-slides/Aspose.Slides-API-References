---
title: EndGetHostEntry()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 비동기 작업이 새로운 IPHostEntry-class 인스턴스를 생성할 때까지 대기합니다.
type: docs
weight: 118
url: /ko/system.net/dns/endgethostentry/
---
## Dns::EndGetHostEntry(System::SharedPtr\<IAsyncResult\>) 메서드

지정된 비동기 작업이 새로운 IPHostEntry-class 인스턴스를 생성할 때까지 대기합니다.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostEntry(System::SharedPtr<IAsyncResult> asyncResult)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 비동기 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 개체. |

### 반환 값

새로 생성된 IPHostEntry-class 인스턴스.

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPHostEntry](../../iphostentry/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [Dns](../)
* 네임스페이스 [System::Net](../../)
* Library [Aspose.Slides](../../../)