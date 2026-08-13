---
title: XmlSchemaComplexType
second_title: Aspose.Slides for C++ API 레퍼런스
description: 복합 유형(complexType) 요소를 XML 스키마에서 World Wide Web Consortium(W3C)이 지정한 대로 나타냅니다. 이 클래스는 요소의 속성과 콘텐츠 집합을 결정하는 복합 유형을 정의합니다.
type: docs
weight: 300
url: /ko/system.xml.schema/xmlschemacomplextype/
---
## XmlSchemaComplexType 클래스


Represents the **complexType** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class defines a complex type that determines the set of attributes and content of an element.

```cpp
class XmlSchemaComplexType : public System::Xml::Schema::XmlSchemaType
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 개체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 개체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 개체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | **annotation** 속성을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AnyAttribute](./get_anyattribute/)() | [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) 구성 요소의 값을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Attributes](./get_attributes/)() | 복합 유형에 대한 속성 컬렉션을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeUses](./get_attributeuses/)() | 이 복합 유형 및 기본 유형의 모든 컴파일된 속성 컬렉션을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AttributeWildcard](./get_attributewildcard/)() | **anyAttribute**에 대한 포스트 컴파일 값(이 복합 유형 및 해당 기본 유형들에 대해)을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](../xmlschematype/get_baseschematype/)() | 포스트 컴파일 객체 유형 또는 내장 XML [Schema](../) 정의 언어(XSD) 데이터 유형, simpleType 요소, 또는 complexType 요소를 반환합니다. 이는 스키마 컴파일 후 인포셋 값입니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_BaseXmlSchemaType](../xmlschematype/get_basexmlschematype/)() | 이 스키마 유형의 기본 유형에 대한 포스트 컴파일 값을 반환합니다. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | **block** 속성을 반환합니다. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | 형식이 스키마 검증 후 정보 집합(infoset)으로 컴파일된 후의 값을 반환합니다. 이 값은 인스턴스 문서에서 **xsi:type**이 사용될 때 형식이 어떻게 적용되는지를 나타냅니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\> [get_ContentModel](./get_contentmodel/)() | 이 복합 유형의 포스트 컴파일 [XmlSchemaContentModel](../xmlschemacontentmodel/)을 반환합니다. |
| [XmlSchemaContentType](../xmlschemacontenttype/) [get_ContentType](./get_contenttype/)() | 포스트 컴파일 값을 보유하는 복합 유형의 컨텐츠 모델을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_ContentTypeParticle](./get_contenttypeparticle/)() | [XmlSchemaComplexType::get_ContentType](./get_contenttype/) 파티클의 포스트 컴파일 값을 보유하는 파티클을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](../xmlschematype/get_datatype/)() | 복합 유형 데이터 유형에 대한 포스트 컴파일 값을 반환합니다. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](../xmlschematype/get_derivedby/)() | 이 요소가 기본 유형에서 어떻게 파생되었는지에 대한 포스트 컴파일 정보를 반환합니다. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](../xmlschematype/get_final/)() | 추가 파생이 허용되는지를 나타내는 유형 파생의 최종 속성을 반환합니다. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](../xmlschematype/get_finalresolved/)() | [XmlSchemaType::get_Final](../xmlschematype/get_final/) 값에 대한 포스트 컴파일 해석을 반환합니다. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | 문자열 ID를 반환합니다. |
| **bool** [get_IsAbstract](./get_isabstract/)() | 인스턴스 문서에서 **complexType** 요소를 사용할 수 있는지 여부를 결정하는 정보를 반환합니다. |
| **bool** [get_IsMixed](./get_ismixed/)() override | 복합 유형이 혼합 콘텐츠 모델(콘텐츠 내 마크업)을 갖는지 여부를 결정하는 정보를 반환합니다. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | **schema** 요소가 참조하는 파일의 행 번호를 반환합니다. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | **schema** 요소가 참조하는 파일 내의 열 위치를 반환합니다. |
| [String](../../system/string/) [get_Name](../xmlschematype/get_name/)() | 유형의 이름을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | 이 스키마 객체와 함께 사용할 XmlSerializerNamespaces를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | 이 [XmlSchemaObject](../xmlschemaobject/)의 상위 요소를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_Particle](./get_particle/)() | [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) 또는 [XmlSchemaSequence](../xmlschemasequence/) 클래스 중 하나로 구성자 유형을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschematype/get_qualifiedname/)() | 이 유형의 **Name** 속성으로 만든 타입의 정규화된 이름을 반환합니다. 이는 스키마 컴파일 후 값입니다. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | 스키마를 로드한 파일의 소스 위치를 반환합니다. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](../xmlschematype/get_typecode/)() | 유형의 XmlTypeCode를 반환합니다. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | 현재 스키마의 대상 네임스페이스에 속하지 않는 정규화된 속성을 반환합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | 지정된 복합 유형의 내장 복합 유형을 나타내는 [XmlSchemaComplexType](./)을 반환합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 정규화된 이름으로 지정된 복합 유형의 내장 복합 유형을 나타내는 [XmlSchemaComplexType](./)를 반환합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 정규화된 이름으로 지정된 단순 유형의 내장 단순 유형을 나타내는 [XmlSchemaSimpleType](../xmlschemasimpletype/)를 반환합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | 지정된 단순 유형의 내장 단순 유형을 나타내는 [XmlSchemaSimpleType](../xmlschemasimpletype/)를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 개체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 개체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 개체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 개체가 targetType에 의해 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| static **bool** [IsDerivedFrom](../xmlschematype/isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | 지정된 파생 스키마 유형이 지정된 기본 스키마 유형으로부터 파생되었는지 여부를 나타내는 값을 반환합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금 기능을 제공합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않으며 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 개체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 개체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 개체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | **annotation** 속성을 설정합니다. |
| void [set_AnyAttribute](./set_anyattribute/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\>\&) | 복합 유형의 [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) 구성 요소 값을 설정합니다. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | **block** 속성을 설정합니다. |
| void [set_ContentModel](./set_contentmodel/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\>\&) | 이 복합 유형의 포스트 컴파일 [XmlSchemaContentModel](../xmlschemacontentmodel/)을 설정합니다. |
| void [set_Final](../xmlschematype/set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | 추가 파생이 허용되는지를 나타내는 유형 파생의 최종 속성을 설정합니다. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | 문자열 ID를 설정합니다. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | 인스턴스 문서에서 **complexType** 요소를 사용할 수 있는지 여부를 결정하는 정보를 설정합니다. |
| void [set_IsMixed](./set_ismixed/)(**bool**) override | 복합 유형에 혼합 콘텐츠 모델(콘텐츠 내 마크업)이 있는지 여부를 결정하는 정보를 설정합니다. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | **schema** 요소가 참조하는 파일의 행 번호를 설정합니다. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | **schema** 요소가 참조하는 파일 내의 열 위치를 설정합니다. |
| void [set_Name](../xmlschematype/set_name/)(const [String](../../system/string/)\&) | 유형의 이름을 설정합니다. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | 이 스키마 객체와 함께 사용할 XmlSerializerNamespaces를 설정합니다. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | 이 [XmlSchemaObject](../xmlschemaobject/)의 상위 요소를 설정합니다. |
| void [set_Particle](./set_particle/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\&) | [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) 또는 [XmlSchemaSequence](../xmlschemasequence/) 클래스 중 하나로 구성자 유형을 설정합니다. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | 스키마를 로드한 파일의 소스 위치를 설정합니다. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | 현재 스키마의 대상 네임스페이스에 속하지 않는 정규화된 속성을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 강한 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 개체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
|  [XmlSchemaComplexType](./xmlschemacomplextype/)() | [XmlSchemaComplexType](./) 클래스의 새 인스턴스를 초기화합니다. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | [XmlSchemaObject](../xmlschemaobject/) 클래스의 새 인스턴스를 초기화합니다. |
|  [XmlSchemaType](../xmlschematype/xmlschematype/)() | [XmlSchemaType](../xmlschematype/) 클래스의 새 인스턴스를 초기화합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## Typedefs

| Typedef | 설명 |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스 인스턴스에 대한 shared pointer의 별칭입니다. |

## 비고

이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들지 마십시오. 그렇지 않으면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달하십시오. 

## 참조

* 클래스 [XmlSchemaType](../xmlschematype/)
* 네임스페이스 [System::Xml::Schema](../)
* 라이브러리 [Aspose.Slides](../../)