---
title: HtmlOptions
second_title: Aspose.Slides for C++ API 참조
description: HTML 내보내기 옵션을 나타냅니다.
type: docs
weight: 118
url: /ko/aspose.slides.export/htmloptions/
---
## HtmlOptions 클래스

HTML 내보내기 옵션을 나타냅니다.

```cpp
class HtmlOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::IHtmlOptions
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C#-스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C#-스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | 소스 폰트를 찾을 수 없는 경우 사용되는 폰트를 반환합니다. 읽기 [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | 잘린 부분이 문서에 남아 있는지를 나타내는 불리언 플래그입니다. true인 경우 잘린 부분이 제거되고, false인 경우 문서에 직렬화됩니다(파일 크기가 커질 수 있습니다). |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | 텍스트가 합자(ligature)를 사용하지 않고 렌더링되는지를 나타내는 값을 가져옵니다. **true**로 설정하면 렌더링 결과에서 합자가 비활성화됩니다. 기본값은 **false**입니다. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | 그라디언트의 시각적 스타일을 반환합니다. 읽기 [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\> [get_HtmlFormatter](./get_htmlformatter/)() override | HTML 템플릿을 반환합니다. 읽기 [IHtmlFormatter](../ihtmlformatter/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | 내보낸 문서에서 [Ink](../../aspose.slides.ink/) 객체의 모양을 제어하는 옵션을 제공합니다. 읽기 전용 [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | PDF 문서 내 JPEG 이미지의 품질을 결정하는 값을 반환합니다. 읽기 **uint8_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | 그림 압축 수준을 나타냅니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 진행 상황을 백분율로 저장하는 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/) 참조. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 **false**입니다. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다. 읽기 **bool**. 기본값은 **false**입니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\> [get_SlideImageFormat](./get_slideimageformat/)() override | 슬라이드 이미지 형식 옵션을 반환합니다. 읽기 [ISlideImageFormat](../islideimageformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져옵니다 [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **bool** [get_SvgResponsiveLayout](./get_svgresponsivelayout/)() override | svg 컨테이너에서 너비와 높이 속성을 제외하려면 true(레이아웃이 반응형이 됩니다). 그렇지 않으면 false. 읽기 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 경고를 수신하고 로드 과정이 계속될지 중단될지를 결정하는 객체를 반환하거나 설정합니다. 읽기 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 지정 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
|  [HtmlOptions](./htmloptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | 콜백을 지정하는 새로운 [HtmlOptions](./) 객체를 생성합니다. |
|  [HtmlOptions](./htmloptions/)() | 단일 HTML 파일로 저장하기 위한 새로운 [HtmlOptions](./) 객체를 생성합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠금을 수행합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 지정 유형의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조에 따라 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조에 따라 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 소스 폰트를 찾을 수 없는 경우 사용되는 폰트를 설정합니다. [System::String](../../system/string/)을 씁니다. |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | 잘린 부분이 문서에 남아 있는지를 나타내는 불리언 플래그를 설정합니다. true인 경우 잘린 부분이 제거되고, false인 경우 문서에 직렬화됩니다(파일 크기가 커질 수 있습니다). |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | 텍스트를 합자를 사용하지 않고 렌더링할지를 나타내는 값을 설정합니다. **true**로 설정하면 렌더링 결과에서 합자가 비활성화됩니다. 기본값은 **false**입니다. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | 그라디언트의 시각적 스타일을 설정합니다. [GradientStyle](../../aspose.slides/gradientstyle/)을 씁니다. |
| void [set_HtmlFormatter](./set_htmlformatter/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\>) override | HTML 템플릿을 설정합니다. [IHtmlFormatter](../ihtmlformatter/)를 씁니다. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | PDF 문서 내 JPEG 이미지의 품질을 결정하는 값을 설정합니다. **uint8_t**를 씁니다. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | 그림 압축 수준을 설정합니다. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 진행 상황을 백분율로 저장하는 콜백 객체를 설정합니다. [IProgressCallback](../../aspose.slides/iprogresscallback/) 참조. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 설정합니다. 기본값은 **false**입니다. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 설정합니다. **bool**를 씁니다. 기본값은 **false**입니다. |
| void [set_SlideImageFormat](./set_slideimageformat/)([System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\>) override | 슬라이드 이미지 형식 옵션을 설정합니다. [ISlideImageFormat](../islideimageformat/)를 씁니다. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 설정합니다 [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SvgResponsiveLayout](./set_svgresponsivelayout/)(**bool**) override | svg 컨테이너에서 너비와 높이 속성을 제외하려면 true(레이아웃이 반응형이 됩니다). 그렇지 않으면 false. **bool**를 씁니다. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 경고를 수신하고 로드 과정이 계속될지 중단될지를 결정하는 객체를 설정합니다. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)를 씁니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유 포인터 대신)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 지정 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [SaveOptions](../saveoptions/)
* 클래스 [IHtmlOptions](../ihtmloptions/)
* 네임스페이스 [Aspose::Slides::Export](../)
* 라이브러리 [Aspose.Slides](../../)