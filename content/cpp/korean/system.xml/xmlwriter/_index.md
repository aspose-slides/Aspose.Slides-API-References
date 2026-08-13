---
title: XmlWriter
second_title: Aspose.Slides for C++ API 레퍼런스
description: XML 데이터를 포함하는 스트림 또는 파일을 생성하기 위해 빠르고 캐시되지 않으며 순방향 전용 방식을 제공하는 작성자를 나타냅니다.
type: docs
weight: 573
url: /ko/system.xml/xmlwriter/
---
## XmlWriter 클래스

Represents a writer that provides a fast, non-cached, forward-only way to generate streams or files that contain XML data.

```cpp
class XmlWriter : public System::IDisposable
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual void [Close](./close/)() | 파생 클래스에서 재정의될 경우, 이 스트림 및 기본 스트림을 닫습니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | 지정된 파일 이름을 사용하여 새로운 [XmlWriter](./) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 파일 이름 및 [XmlWriterSettings](../xmlwritersettings/) 객체를 사용하여 새로운 [XmlWriter](./) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 지정된 스트림을 사용하여 새로운 [XmlWriter](./) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 스트림 및 [XmlWriterSettings](../xmlwritersettings/) 객체를 사용하여 새로운 [XmlWriter](./) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 지정된 TextWriter를 사용하여 새로운 [XmlWriter](./) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | TextWriter와 [XmlWriterSettings](../xmlwritersettings/) 객체를 사용하여 새로운 [XmlWriter](./) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | 지정된 [Text::StringBuilder](../../system.text/stringbuilder/)을 사용하여 새로운 [XmlWriter](./) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | [Text::StringBuilder](../../system.text/stringbuilder/)와 [XmlWriterSettings](../xmlwritersettings/) 객체를 사용하여 새로운 [XmlWriter](./) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | 지정된 [XmlWriter](./) 객체를 사용하여 새로운 [XmlWriter](./) 인스턴스를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 지정된 [XmlWriter](./) 및 [XmlWriterSettings](../xmlwritersettings/) 객체를 사용하여 새로운 [XmlWriter](./) 인스턴스를 생성합니다. |
| void [Dispose](./dispose/)() override | [XmlWriter](./) 클래스의 현재 인스턴스가 사용한 모든 리소스를 해제합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미론을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 모방하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 모방하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual void [Flush](./flush/)() | 파생 클래스에서 재정의될 경우, 버퍼에 있는 내용을 기본 스트림에 플러시하고 기본 스트림도 플러시합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | [XmlWriterSettings](../xmlwritersettings/) 객체를 반환하며, 이는 이 [XmlWriter](./) 인스턴스를 만드는 데 사용되었습니다. |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | 파생 클래스에서 재정의될 경우, 작성기의 상태를 가져옵니다. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | 파생 클래스에서 재정의될 경우, 현재 **xml:lang** 범위를 가져옵니다. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | 파생 클래스에서 재정의될 경우, 현재 **xml:space** 범위를 나타내는 XmlSpace를 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | 파생 클래스에서 재정의될 경우, 현재 네임스페이스 범위에서 해당 네임스페이스 URI에 대해 정의된 가장 가까운 접두사를 반환합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하며 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하며 하위 클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr과 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | 파생 클래스에서 재정의될 경우, 현재 [XmlReader](../xmlreader/) 위치에서 발견된 모든 속성을 출력합니다. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 지정된 로컬 이름, 네임스페이스 URI 및 값을 가진 속성을 작성합니다. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 지정된 로컬 이름 및 값을 가진 속성을 출력합니다. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 지정된 접두사, 로컬 이름, 네임스페이스 URI 및 값을 가진 속성을 출력합니다. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 파생 클래스에서 재정의될 경우, 지정된 바이너리 바이트를 Base64로 인코딩하고 결과 텍스트를 출력합니다. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 파생 클래스에서 재정의될 경우, 지정된 바이너리 바이트를 **BinHex**으로 인코딩하고 결과 텍스트를 출력합니다. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | 파생 클래스에서 재정의될 경우, 지정된 텍스트를 포함하는 **...** 블록을 출력합니다. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | 파생 클래스에서 재정의될 경우, 지정된 유니코드 문자 값에 대한 문자 엔터티 생성을 강제합니다. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | 파생 클래스에서 재정의될 경우, 텍스트를 한 번에 하나의 버퍼씩 씁니다. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | 파생 클래스에서 재정의될 경우, 지정된 텍스트를 포함하는 주석 ****을 출력합니다. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 지정된 이름 및 선택적 속성을 가진 DOCTYPE 선언을 작성합니다. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 지정된 로컬 이름 및 값을 가진 요소를 작성합니다. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 지정된 로컬 이름, 네임스페이스 URI 및 값을 가진 요소를 작성합니다. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 지정된 접두사, 로컬 이름, 네임스페이스 URI 및 값을 가진 요소를 작성합니다. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | 파생 클래스에서 재정의될 경우, 이전 XmlWriter::WriteStartAttribute(String,String) 호출을 종료합니다. |
| virtual void [WriteEndDocument](./writeenddocument/)() | 파생 클래스에서 재정의될 경우, 열려 있는 모든 요소나 속성을 닫고 작성기를 시작 상태로 되돌립니다. |
| virtual void [WriteEndElement](./writeendelement/)() | 파생 클래스에서 재정의될 경우, 하나의 요소를 닫고 해당 네임스페이스 범위를 팝합니다. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 엔터티 참조를 **&name**; 형식으로 출력합니다. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | 파생 클래스에서 재정의될 경우, 하나의 요소를 닫고 해당 네임스페이스 범위를 팝합니다. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 지정된 이름을 W3C XML 1.0 권고안([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name))에 따라 유효한 이름인지 확인하며 출력합니다. |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 지정된 이름을 W3C XML 1.0 권고안([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name))에 따라 유효한 NmToken인지 확인하며 출력합니다. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | 파생 클래스에서 재정의될 경우, 리더의 모든 내용을 작성기로 복사하고 리더를 다음 형제 시작 위치로 이동합니다. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | XPathNavigator 객체의 모든 내용을 작성기로 복사합니다. XPathNavigator의 위치는 변경되지 않습니다. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | 파생 클래스에서 재정의될 경우, 이름과 텍스트 사이에 공백을 두고 **<?name text?>** 형식의 처리 지시문을 출력합니다. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 네임스페이스가 지정된 이름을 출력합니다. 이 메서드는 주어진 네임스페이스에 대한 현재 스코프의 접두사를 조회합니다. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | 파생 클래스에서 재정의될 경우, 문자 버퍼에서 원시 마크업을 수동으로 작성합니다. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 문자열에서 원시 마크업을 수동으로 작성합니다. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 지정된 로컬 이름 및 네임스페이스 URI로 속성 시작을 작성합니다. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 지정된 접두사, 로컬 이름 및 네임스페이스 URI로 속성 시작을 작성합니다. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | 지정된 로컬 이름으로 속성 시작을 작성합니다. |
| virtual void [WriteStartDocument](./writestartdocument/)() | 파생 클래스에서 재정의될 경우, 버전 "1.0"을 가진 XML 선언을 작성합니다. |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | 파생 클래스에서 재정의될 경우, 버전 "1.0" 및 standalone 속성을 가진 XML 선언을 작성합니다. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 지정된 시작 태그를 작성하고 주어진 네임스페이스와 연결합니다. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 지정된 시작 태그를 작성하고 주어진 네임스페이스와 접두사와 연결합니다. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 지정된 로컬 이름으로 시작 태그를 작성합니다. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | 파생 클래스에서 재정의될 경우, 지정된 텍스트 내용을 작성합니다. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | 파생 클래스에서 재정의될 경우, 서러게이트 문자 쌍에 대한 서러게이트 문자 엔터티를 생성하고 작성합니다. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 객체 값을 작성합니다. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | [String](../../system/string/) 값을 작성합니다. |
| virtual void [WriteValue](./writevalue/)(**bool**) | [Boolean](../../system/boolean/) 값을 작성합니다. |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | [DateTime](../../system/datetime/) 값을 작성합니다. |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | [DateTimeOffset](../../system/datetimeoffset/) 값을 작성합니다. |
| virtual void [WriteValue](./writevalue/)(**double**) | [Double](../../system/double/) 값을 작성합니다. |
| virtual void [WriteValue](./writevalue/)(**float**) | 단정도 부동소수점 숫자를 작성합니다. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | [Decimal](../../system/decimal/) 값을 작성합니다. |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | [Int32](../../system/int32/) 값을 작성합니다. |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | [Int64](../../system/int64/) 값을 작성합니다. |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | 파생 클래스에서 재정의될 경우, 지정된 공백을 출력합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 타입 별칭

| 타입 별칭 | 설명 |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스의 인스턴스에 대한 공유 포인터 별칭입니다. |
## 참고

* 클래스 [IDisposable](../../system/idisposable/)
* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)