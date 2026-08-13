---
title: ITextFrame
second_title: Aspose.Slides for C++ API 레퍼런스
description: TextFrame을(를) 나타냅니다.
type: docs
weight: 4070
url: /ko/aspose.slides/itextframe/
---
## ITextFrame 클래스

[TextFrame](../textframe/)을(를) 나타냅니다.

```cpp
class ITextFrame : public Aspose::Slides::ISlideComponent
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() | 포함된 하이퍼링크에 대한 쉬운 액세스를 제공합니다. 읽기 전용 [IHyperlinkQueries](../ihyperlinkqueries/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraph](../iparagraph/)\> [get_Paragraph](./get_paragraph/)(**int32_t**) | 지정된 인덱스의 프레임에서 단락을 반환합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphCollection](../iparagraphcollection/)\> [get_Paragraphs](./get_paragraphs/)() | 프레임 내 모든 단락의 목록을 반환합니다. 읽기 전용 [IParagraphCollection](../iparagraphcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [get_ParentCell](./get_parentcell/)() | 부모 셀을 반환하거나, 부모 객체가 [ICell](../icell/) 인터페이스를 구현하지 않으면 null을 반환합니다. 읽기 전용 [ICell](../icell/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_ParentShape](./get_parentshape/)() | 부모 도형을 반환하며, 부모 객체가 [IShape](../ishape/) 인터페이스를 구현하지 않으면 null을 반환합니다. 읽기 전용 [IShape](../ishape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../ibaseslide/). |
| virtual [System::String](../../system/string/) [get_Text](./get_text/)() | [TextFrame](../textframe/)의 일반 텍스트를 가져옵니다. 읽기 [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\> [get_TextFrameFormat](./get_textframeformat/)() | 이 [TextFrame](../textframe/) 객체의 서식 객체를 반환합니다. 읽기 전용 [ITextFrameFormat](../itextframeformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual void [HighlightRegex](./highlightregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) | 정규식의 모든 일치를 지정된 색상으로 강조 표시합니다. |
| virtual void [HighlightRegex](./highlightregex/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextHighlightingOptions](../itexthighlightingoptions/)\>) | 정규식의 모든 일치를 지정된 색상으로 강조 표시합니다. |
| virtual void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/)) | 샘플 텍스트의 모든 일치를 지정된 색상으로 강조 표시합니다. |
| virtual void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextHighlightingOptions](../itexthighlightingoptions/)\>) | 샘플 텍스트의 모든 일치를 지정된 색상으로 강조 표시합니다. |
| virtual void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) | 샘플 텍스트의 모든 일치를 지정된 색상으로 강조 표시합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| virtual void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() | 모든 단락에서 동일한 서식이 적용된 실행을 결합합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금 기능을 제공합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사 구축을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사 구축을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [ReplaceRegex](./replaceregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) | 정규식의 모든 일치를 지정된 문자열로 교체합니다. |
| virtual void [ReplaceText](./replacetext/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) | 지정된 텍스트의 모든 발생을 다른 지정 텍스트로 교체합니다. |
| virtual void [set_Text](./set_text/)([System::String](../../system/string/)) | [TextFrame](../textframe/)의 일반 텍스트를 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [SplitTextByColumns](./splittextbycolumns/)() | [ITextFrame](./)의 텍스트 내용을 문자열 배열로 분할합니다. 각 요소는 프레임 내 별도의 텍스트 열에 해당합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제 기능을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [ISlideComponent](../islidecomponent/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)