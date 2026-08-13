---
title: HttpClient
second_title: Aspose.Slides for C++ API 레퍼런스
description: "HTTP 요청을 보내고 응답을 받기 위한 HTTP 클라이언트 기본 클래스를 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여만 할당해야 합니다. 스택에 이 유형의 인스턴스를 만들거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인수로 전달하십시오."
type: docs
weight: 27
url: /ko/system.net.http/httpclient/
---
## HttpClient 클래스

HTTP 요청을 보내고 응답을 받기 위한 HTTP 클라이언트의 기본 클래스입니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 이 유형의 인스턴스를 만들거나 operator new를 사용하여 생성하지 마십시오. 그렇지 않으면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인수로 전달하십시오.

```cpp
class HttpClient : public System::Net::Http::HttpMessageInvoker
```

## 메서드

| Method | Description |
| --- | --- |
| void [CancelPendingRequests](./cancelpendingrequests/)() | 모든 대기 중인 요청을 취소합니다. |
| void [Dispose](../httpmessageinvoker/dispose/)() override | 현재 인스턴스를 해제합니다. 필요에 따라 이 메서드는 핸들러도 해제합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미론을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_BaseAddress](./get_baseaddress/)() | 요청을 보내는 데 사용되는 리소스의 기본 주소를 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Headers::HttpRequestHeaders](../../system.net.http.headers/httprequestheaders/)\> [get_DefaultRequestHeaders](./get_defaultrequestheaders/)() | 각 요청에 함께 전송되는 헤더를 가져옵니다. |
| **int64_t** [get_MaxResponseContentBufferSize](./get_maxresponsecontentbuffersize/)() | 응답 콘텐츠의 최대 바이트 수를 가져옵니다. |
| [TimeSpan](../../system/timespan/) [get_Timeout](./get_timeout/)() | 요청이 시간 초과되기 전에 대기할 시간 간격을 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 동일합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 동일합니다. |
|  [HttpClient](./httpclient/)() | 새 인스턴스를 생성합니다. |
|  [HttpClient](./httpclient/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMessageHandler](../httpmessagehandler/)\>) | 새 인스턴스를 생성합니다. |
|  [HttpClient](./httpclient/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMessageHandler](../httpmessagehandler/)\>, **bool**) | 새 인스턴스를 생성합니다. |
|  [HttpMessageInvoker](../httpmessageinvoker/httpmessageinvoker/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMessageHandler](../httpmessagehandler/)\>) | 새 인스턴스를 생성합니다. |
|  [HttpMessageInvoker](../httpmessageinvoker/httpmessageinvoker/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMessageHandler](../httpmessagehandler/)\>, **bool**) | 새 인스턴스를 생성합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 동일합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 동일합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpResponseMessage](../httpresponsemessage/)\> [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[HttpRequestMessage](../httprequestmessage/)\>, [HttpCompletionOption](../httpcompletionoption/)) | 지정된 HTTP 요청을 전송합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[HttpResponseMessage](../httpresponsemessage/)\> [Send](../httpmessageinvoker/send/)([System::SharedPtr](../../system/sharedptr/)\<[HttpRequestMessage](../httprequestmessage/)\>) | 지정된 요청을 전송합니다. |
| void [set_BaseAddress](./set_baseaddress/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 요청을 보내는 데 사용되는 리소스의 기본 주소를 설정합니다. |
| void [set_MaxResponseContentBufferSize](./set_maxresponsecontentbuffersize/)(**int64_t**) | 응답 콘텐츠의 최대 바이트 수를 설정합니다. |
| void [set_Timeout](./set_timeout/)([TimeSpan](../../system/timespan/)) | 요청이 시간 초과되기 전에 대기할 시간 간격을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 강한 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 동일합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [HttpMessageInvoker](../httpmessageinvoker/)
* 네임스페이스 [System::Net::Http](../)
* 라이브러리 [Aspose.Slides](../../)