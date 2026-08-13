---
title: XmlNodeReader
second_title: Aspose.Slides for C++ API 레퍼런스
description: XML 데이터를 XmlNode에서 빠르고 캐시되지 않은 순방향 전용 접근을 제공하는 리더를 나타냅니다.
type: docs
weight: 365
url: /ko/system.xml/xmlnodereader/
---
## XmlNodeReader 클래스

[XmlNode](../xmlnode/) 안의 XML 데이터에 대한 빠르고 비캐시된 순방향 전용 접근을 제공하는 리더를 나타냅니다.

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [Close](./close/)() override | [XmlNodeReader::get_ReadState](./get_readstate/)을 [ReadState::Closed](../readstate/)으로 변경합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | 지정된 URI로 새 [XmlReader](../xmlreader/) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 지정된 URI와 설정을 사용하여 새 [XmlReader](../xmlreader/) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 지정된 URI, 설정 및 구문 분석을 위한 컨텍스트 정보를 사용하여 새 [XmlReader](../xmlreader/) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 지정된 스트림을 기본 설정으로 사용하여 새 [XmlReader](../xmlreader/) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 지정된 스트림과 설정으로 새 [XmlReader](../xmlreader/) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 지정된 스트림, 기본 URI 및 설정을 사용하여 새 [XmlReader](../xmlreader/) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 지정된 스트림, 설정 및 구문 분석을 위한 컨텍스트 정보를 사용하여 새 [XmlReader](../xmlreader/) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | 지정된 텍스트 리더를 사용하여 새 [XmlReader](../xmlreader/) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 지정된 텍스트 리더와 설정을 사용하여 새 [XmlReader](../xmlreader/) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 지정된 텍스트 리더, 설정 및 기본 URI를 사용하여 새 [XmlReader](../xmlreader/) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 지정된 텍스트 리더, 설정 및 구문 분석을 위한 컨텍스트 정보를 사용하여 새 [XmlReader](../xmlreader/) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | 지정된 XML 리더와 설정을 사용하여 새 [XmlReader](../xmlreader/) 인스턴스를 생성합니다. |
| void [Dispose](../xmlreader/dispose/)() override | [XmlReader](../xmlreader/) 클래스의 현재 인스턴스가 사용한 모든 리소스를 해제합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미에 따라 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부용도 전용입니다. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | 현재 노드의 속성 수를 반환합니다. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | 현재 노드의 기본 URI를 반환합니다. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | [XmlNodeReader](./)가 이진 콘텐츠 읽기 메서드를 구현하는지 여부를 나타내는 값을 반환합니다. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | [XmlReader](../xmlreader/)가 [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) 메서드를 구현하는지 여부를 나타내는 값을 반환합니다. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | 이 리더가 엔터티를 구문 분석하고 해결할 수 있는지 여부를 나타내는 값을 반환합니다. |
| **int32_t** [get_Depth](./get_depth/)() override | XML 문서에서 현재 노드의 깊이를 반환합니다. |
| **bool** [get_EOF](./get_eof/)() override | 리더가 스트림 끝에 위치해 있는지 여부를 나타내는 값을 반환합니다. |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | 현재 노드에 속성이 있는지 여부를 나타내는 값을 반환합니다. |
| **bool** [get_HasValue](./get_hasvalue/)() override | 현재 노드가 [XmlNodeReader::get_Value](./get_value/) 값을 가질 수 있는지 여부를 나타내는 값을 반환합니다. |
| **bool** [get_IsDefault](./get_isdefault/)() override | 현재 노드가 문서 유형 정의(DTD) 또는 스키마에 정의된 기본값에서 생성된 속성인지 여부를 나타내는 값을 반환합니다. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | 현재 노드가 빈 요소인지 여부를 나타내는 값을 반환합니다 (예: **<MyElement/>**). |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | 현재 노드의 로컬 이름을 반환합니다. |
| [String](../../system/string/) [get_Name](./get_name/)() override | 현재 노드의 정규화된 이름을 반환합니다. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | 리더가 위치한 노드의 네임스페이스 URI를 반환합니다 (W3C 네임스페이스 사양에 정의된 대로). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | 이 구현과 연결된 [XmlNameTable](../xmlnametable/)를 반환합니다. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | 현재 노드의 유형을 반환합니다. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | 현재 노드와 연결된 네임스페이스 접두사를 반환합니다. |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | 파생 클래스에서 재정의되면, 속성 노드 값에 사용되는 따옴표 문자를 가져옵니다. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | 리더의 상태를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | 현재 노드에 할당된 스키마 정보를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | 이 [XmlReader](../xmlreader/) 인스턴스를 생성하는 데 사용된 [XmlReaderSettings](../xmlreadersettings/) 객체를 반환합니다. |
| [String](../../system/string/) [get_Value](./get_value/)() override | 현재 노드의 텍스트 값을 반환합니다. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | 현재 노드의 유형을 반환합니다. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | 현재 **xml:lang** 범위를 반환합니다. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | 현재 **xml:space** 범위를 반환합니다. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | 지정된 이름을 가진 속성의 값을 반환합니다. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | 지정된 로컬 이름 및 네임스페이스 URI를 가진 속성의 값을 반환합니다. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | 지정된 인덱스를 가진 속성의 값을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | 파생 클래스에서 재정의되면, 지정된 인덱스를 가진 속성의 값을 가져옵니다. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | 파생 클래스에서 재정의되면, 지정된 [XmlReader::get_Name](../xmlreader/get_name/) 값을 가진 속성의 값을 가져옵니다. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | 파생 클래스에서 재정의되면, 지정된 [XmlReader::get_LocalName](../xmlreader/get_localname/) 및 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 값을 가진 속성의 값을 가져옵니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | 문자열 인수가 유효한 XML 이름인지 여부를 나타내는 값을 반환합니다. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | 문자열 인수가 유효한 XML 이름 토큰인지 여부를 나타내는 값을 반환합니다. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | [XmlReader::MoveToContent](../xmlreader/movetocontent/)을 호출하고 현재 콘텐츠 노드가 시작 태그 또는 빈 요소 태그인지 테스트합니다. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/)을 호출하고 현재 콘텐츠 노드가 시작 태그 또는 빈 요소 태그인지, 그리고 찾은 요소의 [XmlReader::get_Name](../xmlreader/get_name/) 값이 주어진 인수와 일치하는지 테스트합니다. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/)을 호출하고 현재 콘텐츠 노드가 시작 태그 또는 빈 요소 태그인지, 그리고 찾은 요소의 [XmlReader::get_LocalName](../xmlreader/get_localname/) 및 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 값이 주어진 문자열과 일치하는지 테스트합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | 현재 요소의 범위에서 네임스페이스 접두사를 해석합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 형식의 복제를 가능하게 합니다. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | 지정된 이름을 가진 속성으로 이동합니다. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | 지정된 로컬 이름 및 네임스페이스 URI를 가진 속성으로 이동합니다. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | 지정된 인덱스를 가진 속성으로 이동합니다. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | 현재 노드가 콘텐츠(공백이 아닌 텍스트, **CDATA**, **Element**, **EndElement**, **EntityReference**, 또는 **EndEntity**) 노드인지 확인합니다. 노드가 콘텐츠 노드가 아니면, 리더는 다음 콘텐츠 노드 또는 파일 끝까지 건너뜁니다. 다음 유형의 노드를 건너뜁니다: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, 또는 **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | 현재 속성 노드를 포함하는 요소로 이동합니다. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | 첫 번째 속성으로 이동합니다. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | 다음 속성으로 이동합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| **bool** [Read](./read/)() override | 스트림에서 다음 노드를 읽습니다. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | 속성 값을 하나 이상의 **[Text](../../system.text/)**, **EntityReference**, 또는 **EndEntity** 노드로 구문 분석합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 지정된 유형의 객체로 콘텐츠를 읽습니다. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 콘텐츠를 읽고 Base64 디코드된 바이너리 바이트를 반환합니다. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 콘텐츠를 읽고 BinHex 디코드된 바이너리 바이트를 반환합니다. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | 현재 위치의 텍스트 콘텐츠를 [Boolean](../../system/boolean/)로 읽습니다. |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | 현재 위치의 텍스트 콘텐츠를 [DateTime](../../system/datetime/) 객체로 읽습니다. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | 현재 위치의 텍스트 콘텐츠를 [DateTimeOffset](../../system/datetimeoffset/) 객체로 읽습니다. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | 현재 위치의 텍스트 콘텐츠를 [Decimal](../../system/decimal/) 객체로 읽습니다. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | 현재 위치의 텍스트 콘텐츠를 배정밀도 부동 소수점 숫자로 읽습니다. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | 현재 위치의 텍스트 콘텐츠를 단정밀도 부동 소수점 숫자로 읽습니다. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | 현재 위치의 텍스트 콘텐츠를 32비트 부호 있는 정수로 읽습니다. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | 현재 위치의 텍스트 콘텐츠를 64비트 부호 있는 정수로 읽습니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | 현재 위치의 텍스트 콘텐츠를 [Object](../../system/object/)로 읽습니다. |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | 현재 위치의 텍스트 콘텐츠를 [String](../../system/string/) 객체로 읽습니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 요청된 형식으로 요소 내용을 읽습니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI가 현재 요소와 일치하는지 확인한 후, 요청된 형식으로 요소 내용을 읽습니다. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 요소를 읽고 Base64 콘텐츠를 디코드합니다. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 요소를 읽고 BinHex 콘텐츠를 디코드합니다. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | 현재 요소를 읽고 내용을 [Boolean](../../system/boolean/) 객체로 반환합니다. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI가 현재 요소와 일치하는지 확인한 후, 현재 요소를 읽고 내용을 [Boolean](../../system/boolean/) 객체로 반환합니다. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | 현재 요소를 읽고 내용을 [DateTime](../../system/datetime/) 객체로 반환합니다. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI가 현재 요소와 일치하는지 확인한 후, 현재 요소를 읽고 내용을 [DateTime](../../system/datetime/) 객체로 반환합니다. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | 현재 요소를 읽고 내용을 [Decimal](../../system/decimal/) 객체로 반환합니다. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI가 현재 요소와 일치하는지 확인한 후, 현재 요소를 읽고 내용을 [Decimal](../../system/decimal/) 객체로 반환합니다. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | 현재 요소를 읽고 내용을 배정밀도 부동소수점 숫자로 반환합니다. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI가 현재 요소와 일치하는지 확인한 후, 현재 요소를 읽고 내용을 배정밀도 부동소수점 숫자로 반환합니다. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | 현재 요소를 읽고 내용을 단정밀도 부동소수점 숫자로 반환합니다. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI가 현재 요소와 일치하는지 확인한 후, 현재 요소를 읽고 내용을 단정밀도 부동소수점 숫자로 반환합니다. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | 현재 요소를 읽고 내용을 32비트 부호 있는 정수로 반환합니다. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI가 현재 요소와 일치하는지 확인한 후, 현재 요소를 읽고 내용을 32비트 부호 있는 정수로 반환합니다. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | 현재 요소를 읽고 내용을 64비트 부호 있는 정수로 반환합니다. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI가 현재 요소와 일치하는지 확인한 후, 현재 요소를 읽고 내용을 64비트 부호 있는 정수로 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | 현재 요소를 읽고 내용을 [Object](../../system/object/) 로 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI가 현재 요소와 일치하는지 확인한 후, 현재 요소를 읽고 내용을 [Object](../../system/object/) 로 반환합니다. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | 현재 요소를 읽고 내용을 [String](../../system/string/) 객체로 반환합니다. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI가 현재 요소와 일치하는지 확인한 후, 현재 요소를 읽고 내용을 [String](../../system/string/) 객체로 반환합니다. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | 텍스트 전용 요소를 읽습니다. 그러나 더 간단한 방법을 제공하므로 [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) 메서드를 사용하는 것이 권장됩니다. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | 텍스트 전용 요소를 읽기 전에 찾은 요소의 [XmlReader::get_Name](../xmlreader/get_name/) 값이 주어진 문자열과 일치하는지 확인합니다. 그러나 더 간단한 방법을 제공하므로 [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) 메서드를 사용하는 것이 권장됩니다. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | 텍스트 전용 요소를 읽기 전에 찾은 요소의 [XmlReader::get_LocalName](../xmlreader/get_localname/) 및 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 값이 주어진 문자열과 일치하는지 확인합니다. 그러나 더 간단한 방법을 제공하므로 [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) 메서드를 사용하는 것이 권장됩니다. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | 현재 콘텐츠 노드가 끝 태그인지 확인하고 리더를 다음 노드로 이동합니다. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | 파생 클래스에서 재정의될 때, 마크업을 포함한 모든 콘텐츠를 문자열로 읽습니다. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | 파생 클래스에서 재정의될 때, 이 노드와 그 모든 자식을 나타내는 마크업을 포함한 콘텐츠를 읽습니다. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | 현재 노드가 요소인지 확인하고 리더를 다음 노드로 이동합니다. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | 현재 콘텐츠 노드가 주어진 [XmlReader::get_Name](../xmlreader/get_name/) 값을 가진 요소인지 확인하고 리더를 다음 노드로 이동합니다. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | 현재 콘텐츠 노드가 주어진 [XmlReader::get_LocalName](../xmlreader/get_localname/)와 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 값을 가진 요소인지 확인하고 리더를 다음 노드로 이동합니다. |
| [String](../../system/string/) [ReadString](./readstring/)() override | 요소 또는 텍스트 노드의 내용을 문자열로 읽습니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | 현재 노드와 모든 하위 노드를 읽는 데 사용할 수 있는 새로운 [XmlReader](../xmlreader/) 인스턴스를 반환합니다. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | [XmlReader](../xmlreader/)를 지정된 정규화된 이름을 가진 다음 하위 요소로 이동시킵니다. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](../xmlreader/)를 지정된 로컬 이름과 네임스페이스 URI를 가진 다음 하위 요소로 이동시킵니다. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | 지정된 정규화된 이름을 가진 요소가 발견될 때까지 읽습니다. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI를 가진 요소가 발견될 때까지 읽습니다. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | [XmlReader](../xmlreader/)를 지정된 정규화된 이름을 가진 다음 형제 요소로 이동시킵니다. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](../xmlreader/)를 지정된 로컬 이름과 네임스페이스 URI를 가진 다음 형제 요소로 이동시킵니다. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | XML 문서에 포함된 대용량 텍스트 스트림을 읽습니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [ResolveEntity](./resolveentity/)() override | **EntityReference** 노드에 대한 엔터티 참조를 해결합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하세요. |
| void [Skip](./skip/)() override | 현재 노드의 하위 항목을 건너뜁니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 경비 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하세요. |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | 지정된 [XmlNode](../xmlnode/)를 사용하여 [XmlNodeReader](./) 클래스의 인스턴스를 생성합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스 인스턴스에 대한 공유 포인터 별칭입니다. |
## 비고

이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 이 유형의 인스턴스를 만들거나 operator new를 사용하지 마십시오. 그렇지 않으면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고 해당 포인터를 함수 인수로 전달하십시오. 

## 관련 항목

* 클래스 [XmlReader](../xmlreader/)
* 클래스 [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)