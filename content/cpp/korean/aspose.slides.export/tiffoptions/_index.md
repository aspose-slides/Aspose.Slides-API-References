---
title: TiffOptions
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션을 TIFF 형식으로 저장하는 방법을 제어하는 옵션을 제공합니다.
type: docs
weight: 768
url: /ko/aspose.slides.export/tiffoptions/
---
## TiffOptions 클래스

프레젠테이션을 TIFF 형식으로 저장하는 방법을 제어하는 옵션을 제공합니다.

```cpp
class TiffOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::ITiffOptions
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 유형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 유형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() override | 색상 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다. 이 옵션은 [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/)가 [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) 또는 [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) 로 설정된 경우에만 적용됩니다. 읽기 [BlackWhiteConversionMode](../blackwhiteconversionmode/). 기본값은 [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/)입니다. |
| [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() override | 압축 유형을 지정합니다. 읽기 [TiffCompressionTypes](../tiffcompressiontypes/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | 소스 글꼴을 찾을 수 없는 경우 사용되는 글꼴을 반환합니다. [System::String](../../system/string/)을 읽습니다. |
| **uint32_t** [get_DpiX](./get_dpix/)() override | 수평 해상도를 인치당 도트 수로 지정합니다. **uint32_t**을 읽습니다. |
| **uint32_t** [get_DpiY](./get_dpiy/)() override | 수직 해상도를 인치당 도트 수로 지정합니다. **uint32_t**을 읽습니다. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | 그라디언트의 시각적 스타일을 반환합니다. [GradientStyle](../../aspose.slides/gradientstyle/)을 읽습니다. |
| [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() override | 생성된 TIFF 이미지의 크기를 지정합니다. 기본값은 0x0이며, 이는 생성된 이미지 크기가 프레젠테이션 슬라이드 크기 값을 기준으로 계산됨을 의미합니다. [System::Drawing::Size](../../system.drawing/size/)을 읽습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | [Ink](../../aspose.slides.ink/) 객체의 내보낸 문서에서의 모양을 제어하는 옵션을 제공합니다. 읽기 전용 [IInkOptions](../iinkoptions/) |
| [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() override | 생성된 이미지의 픽셀 형식을 지정합니다. [ImagePixelFormat](../imagepixelformat/)을 읽습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 진행률 업데이트를 백분율로 저장하기 위한 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)를 참조하십시오. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 **false**입니다. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다. **bool**을 읽습니다. 기본값은 **false**입니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져옵니다 [ISlidesLayoutOptions](../islideslayoutoptions/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 경고를 수신하고 로드 프로세스를 계속할지 중단할지를 결정하는 객체를 반환하거나 설정합니다. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)을 읽습니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 구현입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 구현입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사 구현입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 구현입니다. 사용자 정의 타입의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체와 nullptr를 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) override | 색상 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다. 이 옵션은 [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/)가 [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) 또는 [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) 로 설정된 경우에만 적용됩니다. [BlackWhiteConversionMode](../blackwhiteconversionmode/)을 씁니다. 기본값은 [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/)입니다. |
| void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) override | 압축 유형을 지정합니다. [TiffCompressionTypes](../tiffcompressiontypes/)을 씁니다. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 소스 글꼴을 찾을 수 없는 경우 사용되는 글꼴을 설정합니다. [System::String](../../system/string/)을 씁니다. |
| void [set_DpiX](./set_dpix/)(**uint32_t**) override | 수평 해상도를 인치당 도트 수로 지정합니다. **uint32_t**을 씁니다. |
| void [set_DpiY](./set_dpiy/)(**uint32_t**) override | 수직 해상도를 인치당 도트 수로 지정합니다. **uint32_t**을 씁니다. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | 그라디언트의 시각적 스타일을 설정합니다. [GradientStyle](../../aspose.slides/gradientstyle/)을 씁니다. |
| void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) override | 생성된 TIFF 이미지의 크기를 지정합니다. 기본값은 0x0이며, 이는 생성된 이미지 크기가 프레젠테이션 슬라이드 크기 값을 기준으로 계산됨을 의미합니다. [System::Drawing::Size](../../system.drawing/size/)을 씁니다. |
| void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) override | 생성된 이미지의 픽셀 형식을 지정합니다. [ImagePixelFormat](../imagepixelformat/)을 씁니다. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 진행률 업데이트를 백분율로 저장하기 위한 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)를 참조하십시오. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 **false**입니다. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다. **bool**을 씁니다. 기본값은 **false**입니다. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 설정합니다 [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 경고를 수신하고 로드 프로세스를 계속할지 중단할지를 결정하는 객체를 반환하거나 설정합니다. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)을 씁니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | **uint32_t** 타입의 n번째 템플릿 인자를 약한 포인터(공유 포인터가 아니라)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
|  [TiffOptions](./tiffoptions/)() | 기본 생성자. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 구현입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 및 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 비고

다음 예제는 기본 크기로 PowerPoint를 TIFF로 변환하는 방법을 보여줍니다.  
```cpp
// 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

// 프레젠테이션을 TIFF 문서로 저장합니다
presentation->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);
```
다음 예제는 사용자 지정 크기로 PowerPoint를 TIFF로 변환하는 방법을 보여줍니다.  
```cpp
// 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
auto pres = System::MakeObject<Presentation>(u"Convert_Tiff_Custom.pptx");

// TiffOptions 클래스를 인스턴스화합니다
System::SharedPtr<TiffOptions> opts = System::MakeObject<TiffOptions>();
// 압축 유형을 설정합니다
opts->set_CompressionType(TiffCompressionTypes::Default);

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
opts->set_SlidesLayoutOptions(slidesLayoutOptions);

// 압축 유형
// Default - 기본 압축 방식(LZW)을 지정합니다.
// None - 압축을 사용하지 않음을 지정합니다.
// CCITT3
// CCITT4
// LZW
// RLE
// 깊이는 압축 유형에 따라 달라지며 수동으로 설정할 수 없습니다.
// 해상도 단위는 항상 "2"(인치당 도트)입니다.
// 이미지 DPI 설정
opts->set_DpiX(200);
opts->set_DpiY(100);
// 이미지 크기 설정
opts->set_ImageSize(System::Drawing::Size(1728, 1078));
// 지정된 이미지 크기로 프레젠테이션을 TIFF로 저장합니다
pres->Save(u"TiffWithCustomSize_out.tiff", SaveFormat::Tiff, opts);
```
다음 예제는 사용자 지정 이미지 픽셀 형식으로 PowerPoint를 TIFF로 변환하는 방법을 보여줍니다.  
```cpp
// 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_PixelFormat(ImagePixelFormat::Format8bppIndexed);

// 지정된 이미지 크기로 프레젠테이션을 TIFF로 저장합니다
presentation->Save(u"Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat::Tiff, options);
```

## 참고

* 클래스 [SaveOptions](../saveoptions/)
* 클래스 [ITiffOptions](../itiffoptions/)
* 네임스페이스 [Aspose::Slides::Export](../)
* 라이브러리 [Aspose.Slides](../../)