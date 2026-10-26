---
title: EndGetResponse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 리소스에 대한 비동기 요청이 완료될 때까지 대기합니다.
type: docs
weight: 183
url: /ko/system.net/filewebrequest/endgetresponse/
---
## FileWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) 메서드


지정된 리소스에 대한 비동기 요청이 완료될 때까지 대기합니다.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::FileWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) 개체는 리소스에 대한 비동기 요청을 나타냅니다. |

### 반환 값

웹 응답.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [WebResponse](../../webresponse/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [FileWebRequest](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)