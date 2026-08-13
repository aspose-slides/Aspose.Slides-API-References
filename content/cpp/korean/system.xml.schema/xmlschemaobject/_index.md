---
title: XmlSchemaObject
second_title: Aspose.Slides for C++ API 참조
description: Xml 스키마 객체 모델 계층 구조의 루트 클래스를 나타내며 XmlSchema 클래스와 같은 클래스들의 기본 클래스 역할을 합니다.
type: docs
weight: 677
url: /ko/system.xml.schema/xmlschemaobject/
---
## XmlSchemaObject 클래스

Represents the root class for the [Xml](../../system.xml/) schema object model hierarchy and serves as a base class for classes such as the [XmlSchema](../xmlschema/) 클래스.

```cpp
class XmlSchemaObject : public System::Object
```

## 메서드

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(또 NaN도) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(또 NaN도) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| **int32_t** [get_LineNumber](./get_linenumber/)() | **schema** 요소가 참조하는 파일의 행 번호를 반환합니다. |
| **int32_t** [get_LinePosition](./get_lineposition/)() | **schema** 요소가 참조하는 파일의 행 위치를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](./get_namespaces/)() | 이 스키마 객체와 함께 사용할 XmlSerializerNamespaces를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](./)\> [get_Parent](./get_parent/)() | 이 [XmlSchemaObject](./)의 부모를 반환합니다. |
| [String](../../system/string/) [get_SourceUri](./get_sourceuri/)() | 스키마를 로드한 파일의 원본 위치를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문장의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입을 복제할 수 있게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로 아무것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로 아무것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_LineNumber](./set_linenumber/)(**int32_t**) | **schema** 요소가 참조하는 파일의 행 번호를 설정합니다. |
| void [set_LinePosition](./set_lineposition/)(**int32_t**) | **schema** 요소가 참조하는 파일의 행 위치를 설정합니다. |
| void [set_Namespaces](./set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | 이 스키마 객체와 함께 사용할 XmlSerializerNamespaces를 설정합니다. |
| void [set_Parent](./set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](./)\>\&) | 이 [XmlSchemaObject](./)의 부모를 설정합니다. |
| void [set_SourceUri](./set_sourceuri/)(const [String](../../system/string/)\&) | 스키마를 로드한 파일의 원본 위치를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문장의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
|  [XmlSchemaObject](./xmlschemaobject/)() | [XmlSchemaObject](./) 클래스의 새 인스턴스를 초기화합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 타입정의

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스 인스턴스에 대한 공유 포인터 별칭입니다. |
## 주석

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## 참조

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Xml::Schema](../)
* 라이브러리 [Aspose.Slides](../../)