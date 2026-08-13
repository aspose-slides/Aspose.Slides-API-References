---
title: EndRead()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 비동기 읽기 작업이 완료될 때까지 대기합니다.
type: docs
weight: 430
url: /ko/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) 메서드


지정된 비동기 읽기 작업이 완료될 때까지 대기합니다.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) 객체는 비동기 읽기 작업을 나타냅니다. |

### 반환값

**asyncResult**에 의해 나타내는 읽기 작업 중 읽힌 바이트 수

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [SslStream](../)
* 네임스페이스 [System::Net::Security](../../)
* 라이브러리 [Aspose.Slides](../../../)