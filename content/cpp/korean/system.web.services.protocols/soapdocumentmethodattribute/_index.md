---
title: SoapDocumentMethodAttribute
second_title: Aspose.Slides for C++ API 레퍼런스
description: "모든 SOAP 메시지가 메서드에서 전달되거나 반환될 때 Document 형식을 사용하도록 지정합니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용하여 이 유형의 인스턴스를 생성하지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 래핑하고 해당 포인터를 함수 인수로 전달하십시오."
type: docs
weight: 53
url: /ko/system.web.services.protocols/soapdocumentmethodattribute/
---
## SoapDocumentMethodAttribute 클래스

모든 SOAP 메시지가 메서드에서 전달되거나 반환될 때 Document 형식을 사용하도록 지정합니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들지 마세요. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달하십시오.

```cpp
class SoapDocumentMethodAttribute : public System::Attribute
```


## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [String](../../system/string/) [get_Action](./get_action/)() | ‘SOAPAction’ 속성의 값을 가져옵니다. |
| [String](../../system/string/) [get_Binding](./get_binding/)() | XML 웹 서비스 메서드가 작업을 구현하는 바인딩을 가져옵니다. |
| **bool** [get_OneWay](./get_oneway/)() | 클라이언트가 서버가 메서드 처리를 완료할 때까지 기다리지 않는지를 나타내는 값을 가져옵니다. |
| [SoapParameterStyle](../soapparameterstyle/) [get_ParameterStyle](./get_parameterstyle/)() | 매개변수가 ‘Body’ 요소 아래의 단일 XML 요소에 캡슐화되는지를 나타내는 값을 가져옵니다. |
| [String](../../system/string/) [get_RequestElementName](./get_requestelementname/)() | 서비스 설명에서 작업으로 정의된 SOAP 요청과 연관된 XML 요소의 이름을 가져옵니다. |
| [String](../../system/string/) [get_RequestNamespace](./get_requestnamespace/)() | SOAP 요청과 연관된 네임스페이스를 가져옵니다. |
| [String](../../system/string/) [get_ResponseElementName](./get_responseelementname/)() | SOAP 응답과 연관된 XML 요소의 이름을 가져옵니다. |
| [String](../../system/string/) [get_ResponseNamespace](./get_responsenamespace/)() | SOAP 응답과 연관된 네임스페이스를 가져옵니다. |
| [Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/) [get_Use](./get_use/)() | 메시지 인코딩 방식을 결정하는 값을 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| static [Object::ptr](../../system/object/ptr/) [GetCustomAttribute](../../system/attribute/getcustomattribute/)(const [TypeInfo](../../system/typeinfo/)\&, const [TypeInfo](../../system/typeinfo/)\&) | 지정된 형식에 적용된 사용자 지정 속성을 반환합니다. |
| static [ArrayPtr](../../system/arrayptr/)\<[Object::ptr](../../system/object/ptr/)\> [GetCustomAttributes](../../system/attribute/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&) | 지정된 형식에 적용된 모든 사용자 지정 속성을 반환합니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 형식을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 대상 형식으로 설명된 타입의 인스턴스인지 확인합니다. C# ‘is’ 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 형식의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성하고 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사를 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사를 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_Action](./set_action/)([String](../../system/string/)) | ‘SOAPAction’ 속성의 값을 설정합니다. |
| void [set_Binding](./set_binding/)([String](../../system/string/)) | XML 웹 서비스 메서드가 작업을 구현하는 바인딩을 설정합니다. |
| void [set_OneWay](./set_oneway/)(**bool**) | 클라이언트가 서버가 메서드 처리를 완료할 때까지 기다리지 않는지를 나타내는 값을 설정합니다. |
| void [set_ParameterStyle](./set_parameterstyle/)([SoapParameterStyle](../soapparameterstyle/)) | 매개변수가 ‘Body’ 요소 아래의 단일 XML 요소에 캡슐화되는지를 나타내는 값을 설정합니다. |
| void [set_RequestElementName](./set_requestelementname/)([String](../../system/string/)) | 서비스 설명에서 작업으로 정의된 SOAP 요청과 연관된 XML 요소의 이름을 설정합니다. |
| void [set_RequestNamespace](./set_requestnamespace/)([String](../../system/string/)) | SOAP 요청과 연관된 네임스페이스를 설정합니다. |
| void [set_ResponseElementName](./set_responseelementname/)([String](../../system/string/)) | SOAP 응답과 연관된 XML 요소의 이름을 설정합니다. |
| void [set_ResponseNamespace](./set_responsenamespace/)([String](../../system/string/)) | SOAP 응답과 연관된 네임스페이스를 설정합니다. |
| void [set_Use](./set_use/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/)) | 메시지 인코딩 방식을 결정하는 값을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 대신)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)() | 새 인스턴스를 구성합니다. |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)([String](../../system/string/)) | 새 인스턴스를 구성합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴하고 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [Attribute](../../system/attribute/)
* 네임스페이스 [System::Web::Services::Protocols](../)
* 라이브러리 [Aspose.Slides](../../)