---
title: EndRead()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 비동기 읽기 작업이 완료될 때까지 대기합니다.
type: docs
weight: 183
url: /ko/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) 메서드

지정된 비동기 읽기 작업이 완료될 때까지 대기합니다.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) 객체는 비동기 읽기 작업을 나타냅니다 |

### 반환 값

비동기 읽기 작업을 나타내는 **asyncResult**에 의해 수행된 읽기 작업 중 읽은 바이트 수

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [Stream](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)