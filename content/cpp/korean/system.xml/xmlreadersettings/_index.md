---
title: XmlReaderSettings
second_title: Aspose.Slides for C++ API 참조
description: "XmlReader::Create 메서드로 생성된 XmlReader 객체에 대해 지원할 기능 집합을 지정합니다."
type: docs
weight: 443
url: /ko/system.xml/xmlreadersettings/
---
## XmlReaderSettings 클래스

[XmlReader::Create](../xmlreader/create/) 메서드가 만든 [XmlReader](../xmlreader/) 객체에 대해 지원할 기능 집합을 지정합니다.

```cpp
class XmlReaderSettings : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | [XmlReaderSettings](./) 인스턴스의 복사본을 생성합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | 문자 검사 수행 여부를 나타내는 값을 반환합니다. |
| **bool** [get_CloseInput](./get_closeinput/)() | 리더가 닫힐 때 기본 스트림이나 TextReader를 닫아야 하는지를 나타내는 값을 반환합니다. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | [XmlReader](../xmlreader/)가 준수할 호환 수준을 반환합니다. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | DTD 처리 방식을 결정하는 값을 반환합니다. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | 주석을 무시할지 여부를 나타내는 값을 반환합니다. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | 처리 지시자를 무시할지 여부를 나타내는 값을 반환합니다. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | 중요하지 않은 공백을 무시할지 여부를 나타내는 값을 반환합니다. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | [XmlReader](../xmlreader/) 객체의 행 번호 오프셋을 반환합니다. |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | [XmlReader](../xmlreader/) 객체의 행 위치 오프셋을 반환합니다. |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | 엔터티 확장으로 인해 문서에 허용될 수 있는 최대 문자 수를 나타내는 값을 반환합니다. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | XML 문서에 허용될 최대 문자 수를 나타내는 값을 반환합니다. 0 값은 XML 문서 크기에 제한이 없음을 의미합니다. 0이 아닌 값은 문자 단위의 최대 크기를 지정합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | 원자화된 문자열 비교에 사용되는 [XmlNameTable](../xmlnametable/)를 반환합니다. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | 문서 유형 정의(DTD) 처리를 금지할지 여부를 나타내는 값을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | 스키마 검증을 수행할 때 사용할 XmlSchemaSet을 반환합니다. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | 스키마 검증 설정을 나타내는 값을 반환합니다. 이 설정은 [XmlReader](../xmlreader/) 객체에 적용됩니다([XmlReaderSettings::get_ValidationType](./get_validationtype/) 값은 [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | 읽는 동안 [XmlReader](../xmlreader/)가 검증 또는 형식 할당을 수행할지 여부를 나타내는 값을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 동일합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 동일합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 동일합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 동일합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/)의 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/)의 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [Reset](./reset/)() | 설정 클래스의 멤버를 기본값으로 재설정합니다. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | 문자 검사 수행 여부를 나타내는 값을 설정합니다. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | 리더가 닫힐 때 기본 스트림이나 TextReader를 닫을지 여부를 나타내는 값을 설정합니다. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | [XmlReader](../xmlreader/)가 준수할 호환 수준을 설정합니다. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | DTD 처리 방식을 결정하는 값을 설정합니다. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | 주석을 무시할지 여부를 나타내는 값을 설정합니다. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | 처리 지시자를 무시할지 여부를 나타내는 값을 설정합니다. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | 중요하지 않은 공백을 무시할지 여부를 나타내는 값을 설정합니다. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | [XmlReader](../xmlreader/) 객체의 행 번호 오프셋을 설정합니다. |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | [XmlReader](../xmlreader/) 객체의 행 위치 오프셋을 설정합니다. |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | 엔터티 확장으로 인해 문서에 허용될 수 있는 최대 문자 수를 설정합니다. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | XML 문서에 허용될 최대 문자 수를 설정합니다. 0 값은 XML 문서 크기에 제한이 없음을 의미하고, 0이 아닌 값은 문자 단위의 최대 크기를 지정합니다. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | 원자화된 문자열 비교에 사용되는 [XmlNameTable](../xmlnametable/)를 설정합니다. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | 문서 유형 정의(DTD) 처리를 금지할지 여부를 나타내는 값을 설정합니다. |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | 스키마 검증을 수행할 때 사용할 XmlSchemaSet을 설정합니다. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | 스키마 검증 설정을 나타내는 값을 설정합니다. 이 설정은 스키마를 검증하는 [XmlReader](../xmlreader/) 객체에 적용됩니다([XmlReaderSettings::get_ValidationType](./get_validationtype/) 값은 [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | 읽는 동안 [XmlReader](../xmlreader/)가 검증 또는 형식 할당을 수행할지 여부를 나타내는 값을 설정합니다. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | 외부 문서에 접근하는 데 사용되는 [XmlResolver](../xmlresolver/)를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 대신)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운터를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운터를 감소시키고 반환합니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 동일합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | 리더가 검증 오류를 만나면 발생하는 이벤트 핸들러를 추가합니다. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | 리더가 검증 오류를 만나면 발생하는 이벤트 핸들러를 제거합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운터를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운터를 감소시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
|  [XmlReaderSettings](./xmlreadersettings/)() | [XmlReaderSettings](./) 클래스의 새 인스턴스를 초기화합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스 인스턴스에 대한 공유 포인터 별칭입니다. |

## 비고

이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수만 사용하여 할당해야 합니다. 스택이나 operator new를 사용하여 이 유형의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하십시오. 

## 참조

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)