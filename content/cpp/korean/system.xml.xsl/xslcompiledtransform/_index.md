---
title: XslCompiledTransform
second_title: C++용 Aspose.Slides API 레퍼런스
description: XSLT 스타일 시트를 사용하여 XML 데이터를 변환합니다.
type: docs
weight: 53
url: /ko/system.xml.xsl/xslcompiledtransform/
---
## XslCompiledTransform 클래스

Transforms XML data using an XSLT style sheet.

```cpp
class XslCompiledTransform : public System::Object
```

## 메서드

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 시맨틱을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C#-style 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C#-style 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용. |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../../system.xml/xmlwritersettings/)\> [get_OutputSettings](./get_outputsettings/)() | 스타일 시트의 **xsl:output** 요소에서 파생된 출력 정보를 포함하는 [XmlWriterSettings](../../system.xml/xmlwritersettings/) 객체를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | [XmlReader](../../system.xml/xmlreader/)에 포함된 스타일 시트를 컴파일합니다. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | [XmlReader](../../system.xml/xmlreader/)에 포함된 XSLT 스타일 시트를 컴파일합니다. [XmlResolver](../../system.xml/xmlresolver/)은 모든 XSLT **import** 또는 **include** 요소를 해결하고 XSLT 설정은 스타일 시트에 대한 권한을 결정합니다. |
| void [Load](./load/)(const [String](../../system/string/)\&) | 지정된 URI에 위치한 스타일 시트를 로드하고 컴파일합니다. |
| void [Load](./load/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | URI로 지정된 XSLT 스타일 시트를 로드하고 컴파일합니다. [XmlResolver](../../system.xml/xmlresolver/)은 모든 XSLT **import** 또는 **include** 요소를 해결하고 XSLT 설정은 스타일 시트에 대한 권한을 결정합니다. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&) | IXPathNavigable 객체에 포함된 스타일 시트를 컴파일합니다. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>) | IXPathNavigable에 포함된 XSLT 스타일 시트를 컴파일합니다. [XmlResolver](../../system.xml/xmlresolver/)은 모든 XSLT **import** 또는 **include** 요소를 해결하고 XSLT 설정은 스타일 시트에 대한 권한을 결정합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하세요. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | IXPathNavigable 객체가 지정한 입력 문서를 사용하여 변환을 수행하고 결과를 [XmlWriter](../../system.xml/xmlwriter/)에 출력합니다. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | IXPathNavigable 객체가 지정한 입력 문서를 사용하여 변환을 수행하고 결과를 [XmlWriter](../../system.xml/xmlwriter/)에 출력합니다. [XsltArgumentList](../xsltargumentlist/)는 추가 런타임 인수를 제공합니다. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | IXPathNavigable 객체가 지정한 입력 문서를 사용하여 변환을 수행하고 결과를 TextWriter에 출력합니다. [XsltArgumentList](../xsltargumentlist/)는 추가 런타임 인수를 제공합니다. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | IXPathNavigable 객체가 지정한 입력 문서를 사용하여 변환을 수행하고 결과를 스트림에 출력합니다. [XsltArgumentList](../xsltargumentlist/)는 추가 런타임 인수를 제공합니다. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | [XmlReader](../../system.xml/xmlreader/) 객체가 지정한 입력 문서를 사용하여 변환을 수행하고 결과를 [XmlWriter](../../system.xml/xmlwriter/)에 출력합니다. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | [XmlReader](../../system.xml/xmlreader/) 객체가 지정한 입력 문서를 사용하여 변환을 수행하고 결과를 [XmlWriter](../../system.xml/xmlwriter/)에 출력합니다. [XsltArgumentList](../xsltargumentlist/)는 추가 런타임 인수를 제공합니다. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | [XmlReader](../../system.xml/xmlreader/) 객체가 지정한 입력 문서를 사용하여 변환을 수행하고 결과를 TextWriter에 출력합니다. [XsltArgumentList](../xsltargumentlist/)는 추가 런타임 인수를 제공합니다. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | [XmlReader](../../system.xml/xmlreader/) 객체가 지정한 입력 문서를 사용하여 변환을 수행하고 결과를 스트림에 출력합니다. [XsltArgumentList](../xsltargumentlist/)는 추가 런타임 인수를 제공합니다. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | URI가 지정한 입력 문서를 사용하여 변환을 수행하고 결과를 [XmlWriter](../../system.xml/xmlwriter/)에 출력합니다. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | URI가 지정한 입력 문서를 사용하여 변환을 수행하고 결과를 [XmlWriter](../../system.xml/xmlwriter/)에 출력합니다. [XsltArgumentList](../xsltargumentlist/)는 추가 런타임 인수를 제공합니다. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | URI가 지정한 입력 문서를 사용하여 변환을 수행하고 결과를 TextWriter에 출력합니다. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | URI가 지정한 입력 문서를 사용하여 변환을 수행하고 결과를 스트림에 출력합니다. [XsltArgumentList](../xsltargumentlist/)는 추가 런타임 인수를 제공합니다. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | URI가 지정한 입력 문서를 사용하여 변환을 수행하고 결과를 파일에 출력합니다. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | [XmlReader](../../system.xml/xmlreader/) 객체가 지정한 입력 문서를 사용하여 변환을 수행하고 결과를 [XmlWriter](../../system.xml/xmlwriter/)에 출력합니다. [XsltArgumentList](../xsltargumentlist/)는 추가 런타임 인수를 제공하고 [XmlResolver](../../system.xml/xmlresolver/)는 XSLT **document()** 함수를 해결합니다. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | IXPathNavigable 객체가 지정한 입력 문서를 사용하여 변환을 수행하고 결과를 [XmlWriter](../../system.xml/xmlwriter/)에 출력합니다. [XsltArgumentList](../xsltargumentlist/)는 추가 런타임 인수를 제공하고 [XmlResolver](../../system.xml/xmlresolver/)는 XSLT **document()** 함수를 해결합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하세요. |
|  [XslCompiledTransform](./xslcompiledtransform/)() | [XslCompiledTransform](./) 클래스의 새 인스턴스를 초기화합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입 정의

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스 인스턴스에 대한 공유 포인터의 별칭입니다. |

## 비고

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## 참조

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Xml::Xsl](../)
* 라이브러리 [Aspose.Slides](../../)