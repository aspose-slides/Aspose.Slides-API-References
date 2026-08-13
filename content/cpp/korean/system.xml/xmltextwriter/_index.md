---
title: XmlTextWriter
second_title: C++용 Aspose.Slides API 레퍼런스
description: W3C 확장 가능한 마크업 언어(XML) 1.0 및 XML 네임스페이스 권고 사항을 준수하는 XML 데이터를 포함하는 스트림이나 파일을 빠르고 캐시되지 않으며 순방향 전용 방식으로 생성하는 라이터를 나타냅니다.
type: docs
weight: 521
url: /ko/system.xml/xmltextwriter/
---
## XmlTextWriter 클래스

W3C 확장 가능한 마크업 언어(XML) 1.0 및 XML 네임스페이스 권고 사항을 준수하는 XML 데이터를 포함하는 스트림이나 파일을 빠르고 캐시되지 않으며 순방향 전용 방식으로 생성하는 라이터를 나타냅니다.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## 메서드

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Closes this stream and the underlying stream. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | 지정된 파일 이름을 사용하여 새로운 [XmlWriter](../xmlwriter/) 인스턴스를 만듭니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 파일 이름과 [XmlWriterSettings](../xmlwritersettings/) 객체를 사용하여 새로운 [XmlWriter](../xmlwriter/) 인스턴스를 만듭니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 지정된 스트림을 사용하여 새로운 [XmlWriter](../xmlwriter/) 인스턴스를 만듭니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 스트림과 [XmlWriterSettings](../xmlwritersettings/) 객체를 사용하여 새로운 [XmlWriter](../xmlwriter/) 인스턴스를 만듭니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 지정된 TextWriter를 사용하여 새로운 [XmlWriter](../xmlwriter/) 인스턴스를 만듭니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | TextWriter와 [XmlWriterSettings](../xmlwritersettings/) 객체를 사용하여 새로운 [XmlWriter](../xmlwriter/) 인스턴스를 만듭니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | 지정된 [Text::StringBuilder](../../system.text/stringbuilder/)를 사용하여 새로운 [XmlWriter](../xmlwriter/) 인스턴스를 만듭니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | [Text::StringBuilder](../../system.text/stringbuilder/) 및 [XmlWriterSettings](../xmlwritersettings/) 객체를 사용하여 새로운 [XmlWriter](../xmlwriter/) 인스턴스를 만듭니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | 지정된 [XmlWriter](../xmlwriter/) 객체를 사용하여 새로운 [XmlWriter](../xmlwriter/) 인스턴스를 만듭니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 지정된 [XmlWriter](../xmlwriter/) 및 [XmlWriterSettings](../xmlwritersettings/) 객체를 사용하여 새로운 [XmlWriter](../xmlwriter/) 인스턴스를 만듭니다. |
| void [Dispose](../xmlwriter/dispose/)() override | [XmlWriter](../xmlwriter/) 클래스의 현재 인스턴스가 사용한 모든 리소스를 해제합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, 포함 NaN도 같지 않지만, C# 스타일 부동 소수점 비교를 모방하여 두 NaN을 동일한 것으로 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, 포함 NaN도 같지 않지만, C# 스타일 부동 소수점 비교를 모방하여 두 NaN을 동일한 것으로 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| void [Flush](./flush/)() override | 버퍼에 있는 내용을 기본 스트림에 플러시하고, 또한 기본 스트림을 플러시합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | 기본 스트림 객체를 반환합니다. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | 출력 형식이 어떻게 되는지 나타냅니다. |
| **int32_t** [get_Indentation](./get_indentation/)() | [XmlTextWriter::set_Formatting](./set_formatting/)가 [Formatting::Indented](../formatting/)로 설정된 경우 계층 구조의 각 레벨마다 쓸 IndentChars 수를 반환합니다. |
| char16_t [get_IndentChar](./get_indentchar/)() | [XmlTextWriter::set_Formatting](./set_formatting/)가 [Formatting::Indented](../formatting/)으로 설정된 경우 들여쓰기에 사용할 문자를 반환합니다. |
| **bool** [get_Namespaces](./get_namespaces/)() | 네임스페이스 지원 여부를 나타내는 값을 반환합니다. |
| char16_t [get_QuoteChar](./get_quotechar/)() | 속성 값에 인용부호를 붙이는 데 사용할 문자를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | [XmlWriter](../xmlwriter/) 인스턴스를 생성하는 데 사용된 [XmlWriterSettings](../xmlwritersettings/) 객체를 반환합니다. |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | 작성기의 상태를 반환합니다. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | 현재 **xml:lang** 범위를 반환합니다. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | 현재 **xml:space** 범위를 나타내는 XmlSpace를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | 현재 네임스페이스 범위에서 지정된 네임스페이스 URI에 대해 가장 가까운 접두사를 반환합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 형식의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고, 새로운 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고, 새로운 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조를 통해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조를 통해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | 출력 형식이 어떻게 되는지 나타냅니다. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | [XmlTextWriter::set_Formatting](./set_formatting/)가 [Formatting::Indented](../formatting/)로 설정된 경우 계층 구조의 각 레벨마다 쓸 IndentChars 수를 설정합니다. |
| void [set_IndentChar](./set_indentchar/)(char16_t) | [XmlTextWriter::set_Formatting](./set_formatting/)가 [Formatting::Indented](../formatting/)로 설정된 경우 들여쓰기에 사용할 문자를 설정합니다. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | 네임스페이스 지원 여부를 나타내는 값을 설정합니다. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | 속성 값을 인용부호로 감싸는 데 사용할 문자를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 포인터가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | 파생 클래스에서 재정의될 경우, [XmlReader](../xmlreader/) 현재 위치에 있는 모든 속성을 기록합니다. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 지정된 로컬 이름, 네임스페이스 URI 및 값을 가진 속성을 기록합니다. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 지정된 로컬 이름과 값을 가진 속성을 기록합니다. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 지정된 접두사, 로컬 이름, 네임스페이스 URI 및 값을 가진 속성을 기록합니다. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 지정된 바이너리 바이트를 base64로 인코딩하고 결과 텍스트를 기록합니다. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 지정된 바이너리 바이트를 binhex으로 인코딩하고 결과 텍스트를 기록합니다. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | 지정된 텍스트를 포함하는 **...** 블록을 기록합니다. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | 지정된 유니코드 문자 값에 대한 문자 엔티티 생성을 강제합니다. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | 텍스트를 버퍼 단위로 기록합니다. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | 지정된 텍스트를 포함하는 **** 주석을 기록합니다. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | 지정된 이름 및 선택적 속성을 사용하여 DOCTYPE 선언을 기록합니다. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 지정된 로컬 이름과 값을 가진 요소를 기록합니다. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 지정된 로컬 이름, 네임스페이스 URI 및 값을 가진 요소를 기록합니다. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 지정된 접두사, 로컬 이름, 네임스페이스 URI 및 값을 가진 요소를 기록합니다. |
| void [WriteEndAttribute](./writeendattribute/)() override | 이전 [XmlTextWriter::WriteStartAttribute](./writestartattribute/) 호출을 닫습니다. |
| void [WriteEndDocument](./writeenddocument/)() override | 열린 모든 요소 또는 속성을 닫고 작성기를 시작 상태로 되돌립니다. |
| void [WriteEndElement](./writeendelement/)() override | 하나의 요소를 닫고 해당 네임스페이스 범위를 팝합니다. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | 엔터티 참조를 **&name**; 형식으로 기록합니다. |
| void [WriteFullEndElement](./writefullendelement/)() override | 하나의 요소를 닫고 해당 네임스페이스 범위를 팝합니다. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | 지정된 이름을 기록하며, [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)에 따라 유효한 이름인지 확인합니다. |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | 지정된 이름을 기록하며, [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)에 따라 유효한 **NmToken**인지 확인합니다. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | 파생 클래스에서 재정의될 경우, 리더의 내용을 모두 작성기로 복사하고 리더를 다음 형제의 시작으로 이동합니다. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | XPathNavigator 객체의 모든 내용을 작성기로 복사합니다. XPathNavigator의 위치는 변하지 않습니다. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | 이름과 텍스트 사이에 공백을 두고 다음과 같이 처리 지시자를 기록합니다: **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | 네임스페이스 한정 이름을 기록합니다. 이 메서드는 지정된 네임스페이스에 대한 범위 내 접두사를 찾아냅니다. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | 문자 버퍼에서 원시 마크업을 수동으로 기록합니다. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | 문자열에서 원시 마크업을 수동으로 기록합니다. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | 속성 시작을 기록합니다. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 지정된 로컬 이름 및 네임스페이스 URI를 가진 속성 시작을 기록합니다. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | 지정된 로컬 이름을 가진 속성 시작을 기록합니다. |
| void [WriteStartDocument](./writestartdocument/)() override | 버전 "1.0"인 XML 선언을 기록합니다. |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | 버전 "1.0" 및 standalone 속성을 가진 XML 선언을 기록합니다. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | 지정된 시작 태그를 기록하고 주어진 네임스페이스와 접두사와 연결합니다. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 지정된 시작 태그를 기록하고 주어진 네임스페이스와 연결합니다. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 지정된 로컬 이름을 가진 시작 태그를 기록합니다. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | 주어진 텍스트 내용을 기록합니다. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | 서러게이트 문자 쌍에 대한 서러게이트 문자 엔티티를 생성하고 기록합니다. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 객체 값을 기록합니다. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | [String](../../system/string/) 값을 기록합니다. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | [Boolean](../../system/boolean/) 값을 기록합니다. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | [DateTime](../../system/datetime/) 값을 기록합니다. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | [DateTimeOffset](../../system/datetimeoffset/) 값을 기록합니다. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | [Double](../../system/double/) 값을 기록합니다. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | 단정밀 부동 소수점 숫자를 기록합니다. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | [Decimal](../../system/decimal/) 값을 기록합니다. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | [Int32](../../system/int32/) 값을 기록합니다. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | [Int64](../../system/int64/) 값을 기록합니다. |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | 주어진 공백을 기록합니다. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | 지정된 스트림 및 인코딩을 사용하여 [XmlTextWriter](./) 클래스의 인스턴스를 생성합니다. |
|  [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | 지정된 파일을 사용하여 [XmlTextWriter](./) 클래스의 인스턴스를 생성합니다. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 지정된 TextWriter를 사용하여 [XmlTextWriter](./) 클래스의 인스턴스를 생성합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 타입 별칭

| 타입 별칭 | 설명 |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스 인스턴스에 대한 공유 포인터 별칭입니다. |
## 비고

[XmlWriter](../xmlwriter/) 클래스를 대신 사용하는 것이 권장됩니다.

이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 또는 operator new를 사용하여 이 유형의 인스턴스를 생성하지 마십시오. 그렇게 하면 런타임 오류 또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 래핑하고 해당 포인터를 함수 인수로 전달하십시오.

## 참조

* 클래스 [XmlWriter](../xmlwriter/)
* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)