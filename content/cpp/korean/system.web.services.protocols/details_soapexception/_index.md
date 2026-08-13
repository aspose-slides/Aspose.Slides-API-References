---
title: Details_SoapException
second_title: Aspose.Slides for C++ API 레퍼런스
description: "SOAP을 통해 메서드가 호출되고 오류가 발생했을 때 발생하는 예외를 나타냅니다. 이 클래스를 직접 인스턴스화하지 마세요. 대신 SoapException 클래스를 사용하십시오. SoapException 클래스 인스턴스를 System::SmartPtr에 래핑하지 마세요."
type: docs
weight: 1
url: /ko/system.web.services.protocols/details_soapexception/
---
## Details_SoapException 클래스

SOAP을 통해 메서드를 호출하고 오류가 발생했을 때 발생하는 예외를 나타냅니다. 이 클래스를 직접 인스턴스화하지 마세요. 대신 SoapException 클래스를 사용하십시오. SoapException 클래스 인스턴스를 [System::SmartPtr](../../system/smartptr/)에 래핑하지 마세요.

```cpp
class Details_SoapException : public System::Details_SystemException
```

## Methods

| Method | Description |
| --- | --- |
|  [Details_SoapException](./details_soapexception/)() | 새 인스턴스를 생성합니다. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | 새 인스턴스를 생성합니다. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [Exception](../../system/exception/)) | 새 인스턴스를 생성합니다. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/)) | 새 인스턴스를 생성합니다. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [Exception](../../system/exception/)) | 새 인스턴스를 생성합니다. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>) | 새 인스턴스를 생성합니다. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [Exception](../../system/exception/)) | 새 인스턴스를 생성합니다. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>) | 새 인스턴스를 생성합니다. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>, [Exception](../../system/exception/)) | 새 인스턴스를 생성합니다. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>, [Exception](../../system/exception/)) | 새 인스턴스를 생성합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동등하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동등하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [String](../../system/string/) [get_Actor](./get_actor/)() | SOAP 버전 1.1을 사용할 때 예외가 발생한 코드 조각을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_Code](./get_code/)() | 'namespace:localname' 형식의 네임스페이스가 지정된 로컬 이름을 반환하여 SOAP 오류 코드를 지정합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | 사용자 정의 예외 데이터를 포함하는 사전을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\> [get_Detail](./get_detail/)() | 발생한 예외에 대한 세부 정보를 반환합니다. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | 현재 객체가 나타내는 예외와 연결된 HRESULT 코드인 32비트 정수 값을 반환합니다. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | 내부 예외를 나타내는 객체에 대한 참조를 반환합니다. |
| [String](../../system/string/) [get_Lang](./get_lang/)() | 예외 속성을 지역화하는 데 사용되는 언어를 반환합니다. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | 오류 설명 문자열을 반환합니다. |
| [String](../../system/string/) [get_Node](./get_node/)() | SOAP 버전 1.2를 사용할 때 예외가 발생한 코드 조각을 반환합니다. |
| [String](../../system/string/) [get_Role](./get_role/)() | 예외를 발생시키는 XML 웹 서비스의 역할을 반환합니다. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | 스택 트레이스를 포함하는 문자열을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\> [get_SubCode](./get_subcode/)() | 'subcode' XML 요소에서 선택적 정보를 반환합니다. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | 가장 내부의 예외를 나타내는 Exception 객체의 복사본을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_systemexception/gettype/)() const override | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| **bool** [Is](../../system/details_systemexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| static **bool** [IsClientFaultCode](./isclientfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | 지정된 코드가 'Client' SOAP 오류 코드와 같은지 확인합니다. |
| static **bool** [IsMustUnderstandFaultCode](./ismustunderstandfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | 지정된 코드가 'MustUnderstand' SOAP 오류 코드와 같은지 확인합니다. |
| static **bool** [IsServerFaultCode](./isserverfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | 지정된 코드가 'Server' SOAP 오류 코드와 같은지 확인합니다. |
| static **bool** [IsVersionMismatchFaultCode](./isversionmismatchfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | 지정된 코드가 'VersionMismatch' SOAP 오류 코드와 같은지 확인합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠금을 겁니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스를 복사 생성할 수 있게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스를 복사 생성할 수 있게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체와 nullptr를 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | 특정 예외에 할당된 코드화된 숫자 값인 HRESULT를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있게 합니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운터를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운터를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | 현재 객체의 문자열 표현을 반환합니다. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_systemexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 구현하여 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운터를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운터를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual const char * [what](../../system/details_exception/what/)() const | [what()](../../system/details_exception/what/) 메서드를 구현하며, 이는 [ExceptionWrapper](../../system/exceptionwrapper/) 클래스에 의해 호출됩니다. 이 클래스가 std::exception을 상속하지 않았음에도 파생 클래스들은 보호/비공개 멤버를 사용해 로직을 구현할 수 있습니다. 이 메서드 구현을 [ExceptionWrapper](../../system/exceptionwrapper/) 로 이동하면 해당 로직이 손상될 수 있습니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## Fields

| Field | Description |
| --- | --- |
| static [ClientFaultCode](./clientfaultcode/) | 잘못 포맷되었거나 필수 정보를 포함하지 않은 클라이언트 호출을 나타내는 SOAP 오류 코드. |
| static [DetailElementName](./detailelementname/) | 'namespace:localname' 형식의 네임스페이스가 지정된 로컬 이름. |
| static [MustUnderstandFaultCode](./mustunderstandfaultcode/) | 'MustUnderstand' 속성으로 표시된 SOAP 요소가 처리되지 않았음을 나타내는 SOAP 오류 코드. |
| static [ServerFaultCode](./serverfaultcode/) | 서버에서 오류가 발생했음을 나타내는 SOAP 오류 코드. |
| static [VersionMismatchFaultCode](./versionmismatchfaultcode/) | 잘못된 네임스페이스를 나타내는 SOAP 오류 코드. |

## 참조

* 클래스 [Details_SystemException](../../system/details_systemexception/)
* 네임스페이스 [System::Web::Services::Protocols](../)
* 라이브러리 [Aspose.Slides](../../)