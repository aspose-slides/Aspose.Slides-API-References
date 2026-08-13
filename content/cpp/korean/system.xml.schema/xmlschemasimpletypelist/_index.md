---
title: XmlSchemaSimpleTypeList
second_title: Aspose.Slides for C++ API 레퍼런스
description: XML 스키마에서 리스트 요소를 나타내며, World Wide Web Consortium (W3C) 에서 정의한 대로입니다. 이 클래스를 사용하여 지정된 데이터 유형의 값 목록으로 simpleType 요소를 정의할 수 있습니다.
type: docs
weight: 859
url: /ko/system.xml.schema/xmlschemasimpletypelist/
---
## XmlSchemaSimpleTypeList 클래스

Represents the **list** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This **클래스** can be used to define a **simpleType** element as a list of values of a specified data type.

```cpp
class XmlSchemaSimpleTypeList : public System::Xml::Schema::XmlSchemaSimpleTypeContent
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미론을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어느 값과도 같지 않지만, 두 NaN을 동일하다고 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어느 값과도 같지 않지만, 두 NaN을 동일하다고 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | **annotation** 속성을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_BaseItemType](./get_baseitemtype/)() | [XmlSchemaSimpleTypeList::get_ItemType](./get_itemtype/) 및 [XmlSchemaSimpleTypeList::get_ItemTypeName](./get_itemtypename/) 값에 따라 **simpleType** 요소의 유형을 나타내는 [XmlSchemaSimpleType](../xmlschemasimpletype/)를 반환합니다. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | 문자열 ID를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_ItemType](./get_itemtype/)() | **simpleType** 요소를 반환합니다. 이 요소는 기본 값으로 지정된 유형에서 파생됩니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_ItemTypeName](./get_itemtypename/)() | 이 스키마(또는 지정된 네임스페이스로 표시된 다른 스키마)에서 정의된 내장 데이터 유형 또는 **simpleType** 요소의 이름을 반환합니다. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | **schema** 요소가 참조하는 파일의 행 번호를 반환합니다. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | **schema** 요소가 참조하는 파일의 행 위치를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | 이 스키마 객체와 함께 사용할 XmlSerializerNamespaces를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | 이 [XmlSchemaObject](../xmlschemaobject/)의 부모를 반환합니다. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | 스키마를 로드한 파일의 소스 위치를 반환합니다. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | 현재 스키마의 대상 네임스페이스에 속하지 않는 정규화된 속성을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠금합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사를 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사를 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조에 따라 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조에 따라 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | **annotation** 속성을 설정합니다. |
| void [set_BaseItemType](./set_baseitemtype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\>\&) | [XmlSchemaSimpleTypeList::get_ItemType](./get_itemtype/)와 [XmlSchemaSimpleTypeList::get_ItemTypeName](./get_itemtypename/) 값에 따라 **simpleType** 요소의 유형을 나타내는 [XmlSchemaSimpleType](../xmlschemasimpletype/)를 설정합니다. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | 문자열 ID를 설정합니다. |
| void [set_ItemType](./set_itemtype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\>\&) | 기본 값으로 지정된 유형에서 파생된 **simpleType** 요소를 설정합니다. |
| void [set_ItemTypeName](./set_itemtypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 이 스키마(또는 지정된 네임스페이스에 의해 표시된 다른 스키마)에서 정의된 내장 데이터 유형 또는 **simpleType** 요소의 이름을 설정합니다. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | **schema** 요소가 참조하는 파일의 행 번호를 설정합니다. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | **schema** 요소가 참조하는 파일의 행 위치를 설정합니다. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | 이 스키마 객체와 함께 사용할 XmlSerializerNamespaces를 설정합니다. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | 이 [XmlSchemaObject](../xmlschemaobject/)의 부모를 설정합니다. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | 스키마를 로드한 파일의 소스 위치를 설정합니다. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | 현재 스키마의 대상 네임스페이스에 속하지 않는 정규화된 속성을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 템플릿 인수 n번째를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | [XmlSchemaObject](../xmlschemaobject/) 클래스를 새 인스턴스로 초기화합니다. |
|  [XmlSchemaSimpleTypeList](./xmlschemasimpletypelist/)() | [XmlSchemaSimpleTypeList](./) 클래스를 새 인스턴스로 초기화합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스의 인스턴스에 대한 공유 포인터 별칭입니다. |

## 비고

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

## 참조

* 클래스 [XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)
* 네임스페이스 [System::Xml::Schema](../)
* 라이브러리 [Aspose.Slides](../../)