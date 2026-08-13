---
title: XmlSchemaSet
second_title: Aspose.Slides for C++ API 레퍼런스
description: XML 스키마 정의 언어 (XSD) 스키마의 캐시를 포함합니다.
type: docs
weight: 781
url: /ko/system.xml.schema/xmlschemaset/
---
## XmlSchemaSet 클래스

XML [Schema](../) 정의 언어 (XSD) 스키마의 캐시를 포함합니다.

```cpp
class XmlSchemaSet : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [String](../../system/string/)\&) | 지정된 URL에 있는 XML [Schema](../) 정의 언어 (XSD) 스키마를 [XmlSchemaSet](./)에 추가합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | [XmlReader](../../system.xml/xmlreader/)에 포함된 XML [Schema](../) 정의 언어 (XSD) 스키마를 [XmlSchemaSet](./)에 추가합니다. |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](./)\>\&) | 주어진 [XmlSchemaSet](./)에 있는 모든 XML [Schema](../) 정의 언어 (XSD) 스키마를 [XmlSchemaSet](./)에 추가합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | 주어진 [XmlSchema](../xmlschema/)를 [XmlSchemaSet](./)에 추가합니다. |
| void [Compile](./compile/)() | [XmlSchemaSet](./)에 추가된 XML [Schema](../) 정의 언어 (XSD) 스키마를 하나의 논리적인 스키마로 컴파일합니다. |
| **bool** [Contains](./contains/)([String](../../system/string/)) | 지정된 대상 네임스페이스 URI를 가진 XML [Schema](../) 정의 언어 (XSD) 스키마가 [XmlSchemaSet](./)에 있는지 여부를 나타냅니다. |
| **bool** [Contains](./contains/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | 지정된 XML [Schema](../) 정의 언어 (XSD) [XmlSchema](../xmlschema/) 객체가 [XmlSchemaSet](./)에 있는지 여부를 나타냅니다. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\&, **int32_t**) | [XmlSchemaSet](./)에서 모든 [XmlSchema](../xmlschema/) 객체를 지정된 배열에 복사합니다. 지정된 인덱스부터 시작합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 취급하는 C# 스타일 부동소수점 비교를 모방합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 취급하는 C# 스타일 부동소수점 비교를 모방합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\> [get_CompilationSettings](./get_compilationsettings/)() | [XmlSchemaSet](./)에 대한 [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)를 반환합니다. |
| **int32_t** [get_Count](./get_count/)() | [XmlSchemaSet](./)에 있는 논리적인 XML [Schema](../) 정의 언어 (XSD) 스키마 수를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalAttributes](./get_globalattributes/)() | [XmlSchemaSet](./)에 있는 모든 XML [Schema](../) 정의 언어 (XSD) 스키마의 전역 속성을 모두 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalElements](./get_globalelements/)() | [XmlSchemaSet](./)에 있는 모든 XML [Schema](../) 정의 언어 (XSD) 스키마의 전역 요소를 모두 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalTypes](./get_globaltypes/)() | [XmlSchemaSet](./)에 있는 모든 XML [Schema](../) 정의 언어 (XSD) 스키마의 전역 단순 및 복합 타입을 모두 반환합니다. |
| **bool** [get_IsCompiled](./get_iscompiled/)() | [XmlSchemaSet](./)에 있는 XML [Schema](../) 정의 언어 (XSD) 스키마가 컴파일되었는지 여부를 나타내는 값을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | 새 XML [Schema](../) 정의 언어 (XSD) 스키마를 로드할 때 [XmlSchemaSet](./)에서 사용하는 기본 [XmlNameTable](../../system.xml/xmlnametable/)를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 지원합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 지원합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스를 복사 생성할 수 있게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로는 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스를 복사 생성할 수 있게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | 지정된 XML [Schema](../) 정의 언어 (XSD) 스키마를 [XmlSchemaSet](./)에서 제거합니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| **bool** [RemoveRecursive](./removerecursive/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | 지정된 XML [Schema](../) 정의 언어 (XSD) 스키마와 그것이 가져오는 모든 스키마를 [XmlSchemaSet](./)에서 제거합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Reprocess](./reprocess/)([SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>) | [XmlSchemaSet](./)에 이미 존재하는 XML [Schema](../) 정의 언어 (XSD) 스키마를 다시 처리합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)() | [XmlSchemaSet](./)에 있는 모든 XML [Schema](../) 정의 언어 (XSD) 스키마 컬렉션을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)([String](../../system/string/)) | [XmlSchemaSet](./)에서 주어진 네임스페이스에 속하는 모든 XML [Schema](../) 정의 언어 (XSD) 스키마 컬렉션을 반환합니다. |
| void [set_CompilationSettings](./set_compilationsettings/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\>\&) | [XmlSchemaSet](./)에 대한 [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)를 설정합니다. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | 스키마의 include 및 import 요소에서 참조되는 네임스페이스 또는 위치를 해결하는 데 사용되는 [XmlResolver](../../system.xml/xmlresolver/)를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 대신)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | XML [Schema](../) 정의 언어 (XSD) 스키마 검증 오류에 대한 정보를 받기 위한 이벤트 핸들러를 추가합니다. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | XML [Schema](../) 정의 언어 (XSD) 스키마 검증 오류에 대한 정보를 받기 위한 이벤트 핸들러를 제거합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
|  [XmlSchemaSet](./xmlschemaset/)() | [XmlSchemaSet](./) 클래스를 새 인스턴스로 초기화합니다. |
|  [XmlSchemaSet](./xmlschemaset/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&) | 지정된 [XmlNameTable](../../system.xml/xmlnametable/)를 사용하여 [XmlSchemaSet](./) 클래스의 새 인스턴스를 초기화합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입 정의

| 타입 별명 | 설명 |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스 인스턴스에 대한 공유 포인터 별명입니다. |

## 비고

이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용해서만 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용해 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인자로 전달해서 사용하십시오. 

## 참고

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Xml::Schema](../)
* 라이브러리 [Aspose.Slides](../../)