---
title: Details_XmlSchemaValidationException
second_title: Aspose.Slides for C++ API 참조
description: 검증 중인 XML 문서에서 XML 스키마 정의 언어(XSD) 스키마 검증 오류 및 경고가 발생했을 때 발생하는 예외를 나타냅니다.
type: docs
weight: 27
url: /ko/system.xml.schema/details_xmlschemavalidationexception/
---
## Details_XmlSchemaValidationException 클래스

XML [Schema](../) 정의 언어 (XSD) 스키마 검증 오류 및 경고가 검사 중인 XML 문서에서 발생할 때 발생하는 예외를 나타냅니다.

```cpp
class Details_XmlSchemaValidationException : public System::Xml::Schema::Details_XmlSchemaException
```

## 메서드

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따라 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 구현합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따라 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 구현합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | 사용자 정의 예외 데이터를 포함하는 사전을 반환합니다. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | 현재 객체가 나타내는 예외와 연관된 HRESULT 코드인 32비트 정수 값을 반환합니다. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | 내부 예외를 나타내는 객체에 대한 참조를 반환합니다. |
| **int32_t** [get_LineNumber](../details_xmlschemaexception/get_linenumber/)() | 오류가 발생한 위치를 나타내는 행 번호를 반환합니다. |
| **int32_t** [get_LinePosition](../details_xmlschemaexception/get_lineposition/)() | 오류가 발생한 위치를 나타내는 열 번호를 반환합니다. |
| [String](../../system/string/) [get_Message](../details_xmlschemaexception/get_message/)() const override | 이 예외의 오류 상태에 대한 설명을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SourceObject](./get_sourceobject/)() | 이 XmlSchemaValidationException을 일으킨 XML 노드를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_SourceSchemaObject](../details_xmlschemaexception/get_sourceschemaobject/)() | XmlSchemaException을 발생시킨 **[XmlSchemaObject](../xmlschemaobject/)**. |
| [String](../../system/string/) [get_SourceUri](../details_xmlschemaexception/get_sourceuri/)() | 예외를 일으킨 스키마의 Uniform Resource Identifier(URI) 위치를 반환합니다. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | 스택 트레이스를 포함하는 문자열을 반환합니다. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | 가장 안쪽 예외를 나타내는 Exception 객체의 복사본을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사체입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_systemexception/gettype/)() const override | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사체입니다. |
| **bool** [Is](../../system/details_systemexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠금합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조에 의해 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조에 의해 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | 특정 예외에 할당되는 코드화된 숫자값인 HRESULT를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유가 아닌 weak 포인터로 설정합니다. 컨테이너 내 포인터를 weak 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | 현재 객체의 문자열 표현을 반환합니다. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_systemexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 구현하여 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 참조 카운트를 감소시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual const char * [what](../../system/details_exception/what/)() const | [what()](../../system/details_exception/what/) 메서드를 구현하며, 이는 [ExceptionWrapper](../../system/exceptionwrapper/) 클래스에 의해 호출됩니다. 이 클래스가 std::exception에서 상속되지 않았음에도 파생 클래스는 보호/프라이빗 멤버를 사용해 로직을 구현할 수 있습니다. 이 메서드 구현을 [ExceptionWrapper](../../system/exceptionwrapper/)로 이동하면 해당 로직이 깨질 수 있습니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입정의

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스 인스턴스에 대한 공유 포인터 별칭입니다. |

## 관련 항목

* 클래스 [Details_XmlSchemaException](../details_xmlschemaexception/)
* 네임스페이스 [System::Xml::Schema](../)
* 라이브러리 [Aspose.Slides](../../)