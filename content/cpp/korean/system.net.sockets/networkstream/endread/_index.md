---
title: EndRead()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 비동기 읽기 작업이 완료될 때까지 대기합니다.
type: docs
weight: 261
url: /ko/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) 메서드


지정된 비동기 읽기 작업이 완료될 때까지 대기합니다.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 비동기 읽기 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체 |

### Return Value

**asyncResult**에 의해 나타내지는 읽기 작업 중에 읽힌 바이트 수

## See Also

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [NetworkStream](../)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)