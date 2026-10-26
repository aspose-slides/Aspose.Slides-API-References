---
title: EndGetHostByName()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 비동기 작업이 새 IPHostEntry-class 인스턴스를 생성할 때까지 대기합니다.
type: docs
weight: 66
url: /ko/system.net/dns/endgethostbyname/
---
## Dns::EndGetHostByName(System::SharedPtr\<IAsyncResult\>) method

지정된 비동기 작업이 새 IPHostEntry-class 인스턴스를 생성할 때까지 대기합니다.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostByName(System::SharedPtr<IAsyncResult> asyncResult)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 비동기 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체. |

### 반환값

새로 생성된 IPHostEntry-class 인스턴스.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPHostEntry](../../iphostentry/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [Dns](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)