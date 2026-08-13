---
title: XmlWriterSettings
second_title: Aspose.Slides for C++ API 레퍼런스
description: "XmlWriter::Create 메서드에 의해 생성된 XmlWriter 객체에서 지원할 기능 집합을 지정합니다."
type: docs
weight: 586
url: /ko/system.xml/xmlwritersettings/
---
## XmlWriterSettings 클래스

특정 [XmlWriter](../xmlwriter/) 객체가 [XmlWriter::Create](../xmlwriter/create/) 메서드에 의해 생성된 경우 지원할 기능 집합을 지정합니다.

```cpp
class XmlWriterSettings : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | [XmlWriterSettings](./) 인스턴스의 복사본을 생성합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | XML 작성기가 문서의 모든 문자들이 W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets)의 "2.2 Characters" 섹션을 준수하는지 확인해야 하는지를 나타내는 값을 반환합니다. |
| **bool** [get_CloseOutput](./get_closeoutput/)() | [XmlWriter::Close](../xmlwriter/close/) 메서드가 호출될 때 [XmlWriter](../xmlwriter/)가 기본 스트림 또는 TextWriter도 닫도록 할지 여부를 나타내는 값을 반환합니다. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | XML 작성기가 XML 출력에 대해 검사하는 준수 수준을 반환합니다. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | [XmlWriter](../xmlwriter/)가 URI 속성을 이스케이프하지 않는지를 나타내는 값을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | 사용할 텍스트 인코딩 유형을 반환합니다. |
| **bool** [get_Indent](./get_indent/)() | 요소를 들여쓰기 할지 여부를 나타내는 값을 반환합니다. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | 들여쓰기 시 사용할 문자 문자열을 반환합니다. 이 설정은 [XmlWriterSettings::set_Indent](./set_indent/) 값이 **true** 로 설정된 경우에 사용됩니다. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | [XmlWriter](../xmlwriter/)가 XML 콘텐츠를 쓸 때 중복 네임스페이스 선언을 제거할지 여부를 나타내는 값을 반환합니다. 기본 동작은 작성기가 네임스페이스 해결기에 존재하는 모든 네임스페이스 선언을 출력하는 것입니다. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | 줄 바꿈에 사용할 문자 문자열을 반환합니다. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | 출력에서 줄 바꿈을 정규화할지 여부를 나타내는 값을 반환합니다. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | 속성을 새 줄에 쓸지 여부를 나타내는 값을 반환합니다. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | XML 선언을 생략할지 여부를 나타내는 값을 반환합니다. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | [XmlWriter](../xmlwriter/) 출력물을 직렬화하는 데 사용되는 메서드를 반환합니다. |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | [XmlWriter::Close](../xmlwriter/close/) 메서드가 호출될 때 [XmlWriter](../xmlwriter/)가 모든 닫히지 않은 요소 태그에 닫는 태그를 추가할지 여부를 나타내는 값을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형을 복제할 수 있게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체와 nullptr를 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [Reset](./reset/)() | 설정 클래스의 멤버를 기본값으로 재설정합니다. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | XML 작성기가 문서의 모든 문자가 W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets)의 "2.2 Characters" 섹션을 준수하는지 확인하도록 하는 값을 설정합니다. |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | [XmlWriter::Close](../xmlwriter/close/) 메서드가 호출될 때 [XmlWriter](../xmlwriter/)가 기본 스트림 또는 TextWriter도 닫도록 하는 값을 설정합니다. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | XML 작성기가 XML 출력에 대해 검사하는 준수 수준을 설정합니다. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | [XmlWriter](../xmlwriter/)가 URI 속성을 이스케이프하지 않도록 하는 값을 설정합니다. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | 사용할 텍스트 인코딩 유형을 설정합니다. |
| void [set_Indent](./set_indent/)(**bool**) | 요소를 들여쓰기 할지 여부를 나타내는 값을 설정합니다. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | 들여쓰기 시 사용할 문자 문자열을 설정합니다. 이 설정은 [XmlWriterSettings::set_Indent](./set_indent/) 값이 **true** 로 설정된 경우에 사용됩니다. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | [XmlWriter](../xmlwriter/)가 XML 콘텐츠를 쓸 때 중복 네임스페이스 선언을 제거할지 여부를 설정합니다. 기본 동작은 작성기가 네임스페이스 해결기에 존재하는 모든 네임스페이스 선언을 출력하는 것입니다. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | 줄 바꿈에 사용할 문자 문자열을 설정합니다. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | 출력에서 줄 바꿈을 정규화할지 여부를 나타내는 값을 설정합니다. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | 속성을 새 줄에 쓸지 여부를 나타내는 값을 설정합니다. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | XML 선언을 생략할지 여부를 나타내는 값을 설정합니다. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | [XmlWriter::Close](../xmlwriter/close/) 메서드가 호출될 때 [XmlWriter](../xmlwriter/)가 모든 닫히지 않은 요소 태그에 닫는 태그를 추가할지 여부를 나타내는 값을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유 포인터 대신 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운터를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운터를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운터를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운터를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
|  [XmlWriterSettings](./xmlwritersettings/)() | [XmlWriterSettings](./) 클래스의 새 인스턴스를 초기화합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스 인스턴스에 대한 공유 포인터 별칭입니다. |

## 비고

이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용하여 이 타입의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하도록 사용하십시오.

## 참조

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)