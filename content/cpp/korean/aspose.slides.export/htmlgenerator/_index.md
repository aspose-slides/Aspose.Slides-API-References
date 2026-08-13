---
title: HtmlGenerator
second_title: Aspose.Slides for C++ API 레퍼런스
description: HTML 생성기.
type: docs
weight: 105
url: /ko/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator 클래스

HTML 생성기.

```cpp
class HtmlGenerator : public Aspose::Slides::Export::IHtmlGenerator
```

## 메서드

| Method | Description |
| --- | --- |
| void [AddAttributeValue](./addattributevalue/)([System::String](../../system/string/)) override | 속성 값을 인용하고 HTML 파일에 추가합니다. |
| void [AddAttributeValue](./addattributevalue/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) override | 속성 값을 인용하고 HTML 파일에 추가합니다. |
| void [AddAttributeValue](./addattributevalue/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | 속성 값을 인용하고 HTML 파일에 추가합니다. |
| void [AddHtml](./addhtml/)([System::String](../../system/string/)) override | 형식화된 HTML 텍스트를 추가합니다. |
| void [AddHtml](./addhtml/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) override | 형식화된 HTML 텍스트를 추가합니다. |
| void [AddHtml](./addhtml/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | 형식화된 HTML 텍스트를 추가합니다. |
| void [AddText](./addtext/)([System::String](../../system/string/)) override | 특수 문자를 HTML 엔터티로 대체하면서 일반 텍스트를 HTML 파일에 추가합니다. 줄 바꿈 및 공백은 대체되지 않습니다. |
| void [AddText](./addtext/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) override | 특수 문자를 HTML 엔터티로 대체하면서 일반 텍스트를 HTML 파일에 추가합니다. 줄 바꿈 및 공백은 대체되지 않습니다. |
| void [AddText](./addtext/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | 특수 문자를 HTML 엔터티로 대체하면서 일반 텍스트를 HTML 파일에 추가합니다. 줄 바꿈 및 공백은 대체되지 않습니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 동등하지 않지만, 두 NaN이 동등하다고 간주되는 C# 스타일 부동 소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 동등하지 않지만, 두 NaN이 동등하다고 간주되는 C# 스타일 부동 소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **int32_t** [get_NextSlideIndex](./get_nextslideindex/)() override | 현재 슬라이드 이후에 렌더링될 슬라이드의 인덱스를 반환하거나, 현재 마지막 슬라이드를 렌더링 중이면 -1을 반환합니다. 읽기 전용 **int32_t**. |
| **int32_t** [get_PreviousSlideIndex](./get_previousslideindex/)() override | 이전에 렌더링된 슬라이드의 인덱스를 반환하거나 첫 번째 슬라이드가 렌더링 중이면 -1을 반환합니다. 읽기 전용 **int32_t**. |
| [System::Drawing::SizeF](../../system.drawing/sizef/) [get_SlideImageSize](./get_slideimagesize/)() override | 슬라이드 이미지 크기를 반환합니다. 읽기 전용 [System::Drawing::SizeF](../../system.drawing/sizef/). |
| [SvgCoordinateUnit](../svgcoordinateunit/) [get_SlideImageSizeUnit](./get_slideimagesizeunit/)() override | 슬라이드 이미지 크기가 지정된 단위를 반환합니다. 읽기 전용 [SvgCoordinateUnit](../svgcoordinateunit/). |
| [System::String](../../system/string/) [get_SlideImageSizeUnitCode](./get_slideimagesizeunitcode/)() override | 슬라이드 이미지 크기가 지정된 단위의 CSS 코드를 반환합니다. 읽기 전용 [System::String](../../system/string/). |
| **int32_t** [get_SlideIndex](./get_slideindex/)() override | 현재 렌더링 중인 슬라이드의 인덱스를 반환합니다. 읽기 전용 **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사체. 커스텀 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사체. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자의 유사체. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠급니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사체. 커스텀 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고, 새로운 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않고, 새로운 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사체. 커스텀 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IHtmlGenerator](../ihtmlgenerator/)
* 네임스페이스 [Aspose::Slides::Export](../)
* 라이브러리 [Aspose.Slides](../../)