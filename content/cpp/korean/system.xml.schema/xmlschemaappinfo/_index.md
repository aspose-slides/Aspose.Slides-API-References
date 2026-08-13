---
title: XmlSchemaAppInfo
second_title: Aspose.Slides for C++ API 레퍼런스
description: World Wide Web Consortium (W3C) appinfo 요소를 나타냅니다.
type: docs
weight: 157
url: /ko/system.xml.schema/xmlschemaappinfo/
---
## XmlSchemaAppInfo 클래스

World Wide [Web](../../system.web/) Consortium (W3C) **appinfo** 요소를 나타냅니다.

```cpp
class XmlSchemaAppInfo : public System::Xml::Schema::XmlSchemaObject
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 IEC 60559:1989에 따라 어느 값과도, NaN과도 같지 않음에도 불구하고 동등하다고 간주되는 C# 스타일의 부동 소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 IEC 60559:1989에 따라 어느 값과도, NaN과도 같지 않음에도 불구하고 동등하다고 간주되는 C# 스타일의 부동 소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | **schema** 요소가 가리키는 파일의 행 번호를 반환합니다. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | **schema** 요소가 가리키는 파일의 열 위치를 반환합니다. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../../system.xml/xmlnode/)\>\> [get_Markup](./get_markup/)() | [XmlNode](../../system.xml/xmlnode/) 객체 배열을 반환하며, 이는 **appinfo** 하위 노드를 나타냅니다. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | 이 스키마 객체와 함께 사용할 XmlSerializerNamespaces를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | 이 [XmlSchemaObject](../xmlschemaobject/)의 부모를 반환합니다. |
| [String](../../system/string/) [get_Source](./get_source/)() | 애플리케이션 정보의 원본을 반환합니다. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | 스키마를 로드한 파일의 원본 위치를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열 및 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/)의 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/)의 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | **schema** 요소가 가리키는 파일의 행 번호를 설정합니다. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | **schema** 요소가 가리키는 파일의 열 위치를 설정합니다. |
| void [set_Markup](./set_markup/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../../system.xml/xmlnode/)\>\>\&) | **appinfo** 하위 노드를 나타내는 [XmlNode](../../system.xml/xmlnode/) 객체 배열을 설정합니다. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | 이 스키마 객체와 함께 사용할 XmlSerializerNamespaces를 설정합니다. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | 이 [XmlSchemaObject](../xmlschemaobject/)의 부모를 설정합니다. |
| void [set_Source](./set_source/)(const [String](../../system/string/)\&) | 애플리케이션 정보의 원본을 설정합니다. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | 스키마를 로드한 파일의 원본 위치를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운트 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | [XmlSchemaObject](../xmlschemaobject/) 클래의 새 인스턴스를 초기화합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입별칭

| 타입별칭 | 설명 |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스 인스턴스에 대한 공유 포인터 별칭입니다. |

## 비고

이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용해 이 타입의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하십시오. 

## 참조

* 클래스 [XmlSchemaObject](../xmlschemaobject/)
* 네임스페이스 [System::Xml::Schema](../)
* 라이브러리 [Aspose.Slides](../../)