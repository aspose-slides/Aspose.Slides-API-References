---
title: PdfOptions
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션이 PDF 형식으로 저장되는 방식을 제어하는 옵션을 제공합니다.
type: docs
weight: 573
url: /ko/aspose.slides.export/pdfoptions/
---
## PdfOptions 클래스

Provides options that control how a presentation is saved in Pdf format.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | 문서를 사용자가 열 때 부여될 액세스 권한을 지정하는 플래그 집합을 포함합니다. [PdfAccessPermissions](../pdfaccesspermissions/)를 참고하십시오. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | [Aspose.Slides](../../aspose.slides/)가 공통으로 간주하도록 하는 사용자 정의 폰트 패밀리 이름 배열을 반환합니다. 읽기 [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | 지정된 투명 색을 이미지에 적용합니다. **true**인 경우. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | 각 이미지에 대해 기본 압축 대신 가장 효율적인 압축을 자동으로 선택해야 하는지 여부를 나타냅니다. **bool**.true 로 설정하면 프레젠테이션의 모든 이미지에 대해 가장 적절한 압축 알고리즘이 선택되어 결과 PDF 문서의 크기가 작아집니다. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | 생성된 PDF 문서에 대한 원하는 준수 수준입니다. 읽기 [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | 소스 폰트를 찾을 수 없는 경우 사용되는 폰트를 반환합니다. 읽기 [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | 각 슬라이드 주변에 검은 프레임을 그리려면 true. 읽기 **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | 폰트의 모든 문자를 포함할지 아니면 사용된 부분만 포함할지 결정합니다. 읽기 **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | [Aspose.Slides](../../aspose.slides/)가 ASCII (33..127 코드 범위) 텍스트에 대한 공통 폰트를 포함할지 결정합니다. 127보다 큰 문자 코드는 항상 [Fonts](../../aspose.slides/fonts/)됩니다. 공통 폰트 목록에는 PDF의 기본 14 폰트와 추가 사용자 지정 폰트가 포함됩니다. 읽기 **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | 그라디언트의 시각적 스타일을 반환합니다. 읽기 [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | 이미지 투명 색을 가져옵니다. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | 프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 true. 읽기 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | 내보낸 문서에서 [Ink](../../aspose.slides.ink/) 객체의 모양을 제어하는 옵션을 제공합니다. 읽기 전용 [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | PDF 문서 내 JPEG 이미지 품질을 결정하는 값을 반환합니다. 읽기 **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | PDF 문서를 보호하기 위한 사용자 비밀번호를 설정합니다. 읽기 [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 진행 상황을 백분율로 저장하는 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)를 참고하십시오. |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | 폰트가 굵게 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장할지 여부를 나타냅니다. 이 방법은 특정 폰트에 대해 결과 PDF의 텍스트 품질을 향상시킬 수 있습니다. 읽기 **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | 프레젠테이션에서 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true. 읽기 **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 **false**입니다. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다. 읽기 **bool**. 기본값은 **false**입니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져옵니다 [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | PDF 문서 내 이미지 해상도를 결정하는 값을 반환합니다. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | 문서의 모든 텍스트 콘텐츠에 사용할 압축 유형을 지정합니다. 읽기 [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 경고를 받고 로드 프로세스가 계속될지 중단될지를 결정하는 객체를 반환하거나 설정합니다. 읽기 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 지정 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문장의 잠금 기능을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 지정 타입 복제를 가능하게 합니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| [PdfOptions](./pdfoptions/)() | 기본 생성자. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체와 nullptr를 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | 문서가 사용자 접근으로 열릴 때 부여되어야 할 접근 권한을 지정하는 플래그 집합을 포함합니다. [PdfAccessPermissions](../pdfaccesspermissions/)를 참고하십시오. |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | [Aspose.Slides](../../aspose.slides/)가 일반으로 간주해야 하는 사용자 정의 글꼴 패밀리 이름 배열을 설정합니다. [System::String](../../system/string/)[]에 기록합니다. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | **true**인 경우 지정된 투명 색상을 이미지에 적용합니다. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | 각 이미지에 대해 가장 효과적인 압축(기본 압축 대신)이 자동으로 선택되어야 하는지 여부를 나타냅니다. **bool**.true 로 설정하면 프레젠테이션의 모든 이미지에 대해 가장 적절한 압축 알고리즘이 선택되어 결과 PDF 문서의 크기가 작아집니다. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | 생성된 PDF 문서에 대한 원하는 호환성 수준입니다. [PdfCompliance](../pdfcompliance/)에 기록합니다. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 원본 글꼴을 찾을 수 없는 경우 사용할 글꼴을 설정합니다. [System::String](../../system/string/)에 기록합니다. |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | 각 슬라이드에 검은 프레임을 그리려면 **bool**를 true로 설정합니다. **bool**에 기록합니다. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | 글꼴의 모든 문자를 포함할지, 사용된 부분집합만 포함할지 결정합니다. **bool**에 기록합니다. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | [Aspose.Slides](../../aspose.slides/)가 ASCII(33..127 코드 범위) 텍스트에 대해 일반 글꼴을 포함할지 결정합니다. 127보다 큰 문자 코드에 대해서는 [Fonts](../../aspose.slides/fonts/)가 항상 포함됩니다. 일반 글꼴 목록에는 PDF 기본 14 글꼴과 추가 사용자 지정 글꼴이 포함됩니다. **bool**에 기록합니다. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | 그라디언트의 시각적 스타일을 설정합니다. [GradientStyle](../../aspose.slides/gradientstyle/)에 기록합니다. |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | 이미지 투명 색상을 설정합니다. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | 프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 true로 설정합니다. **bool**에 기록합니다. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | PDF 문서 내 JPEG 이미지의 품질을 결정하는 값을 설정합니다. **uint8_t**에 기록합니다. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | PDF 문서를 보호하기 위해 사용자 비밀번호를 설정합니다. [System::String](../../system/string/)에 기록합니다. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 백분율로 저장 진행 업데이트를 위한 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)를 참조하십시오. |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | 글꼴이 굵게 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장할지 여부를 나타냅니다. 이 방법은 특정 글꼴에 대해 결과 PDF의 텍스트 품질을 향상시킬 수 있습니다. **bool**에 기록합니다. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | 프레젠테이션에 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true로 설정합니다. **bool**에 기록합니다. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 **false**입니다. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | 프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다. **bool**에 기록합니다. 기본값은 **false**입니다. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | 프레젠테이션을 [ISlidesLayoutOptions](../islideslayoutoptions/) 내보낼 때 슬라이드가 페이지에 배치되는 모드를 설정합니다. |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | PDF 문서 내 이미지 해상도를 결정하는 값을 설정합니다. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | 문서의 모든 텍스트 내용에 사용할 압축 유형을 지정합니다. [PdfTextCompression](../pdftextcompression/)에 기록합니다. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 경고를 수신하고 로드 프로세스가 계속될지 중단될지를 결정하는 객체를 반환하거나 설정합니다. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)에 기록합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 대신)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하면 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 비고

다음 예제는 사용자 지정 옵션으로 PowerPoint를 PDF로 변환하는 방법을 보여줍니다.
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// PdfOptions 클래스를 인스턴스화합니다
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Jpeg 품질을 설정합니다
pdfOptions->set_JpegQuality(90);
// 메타파일에 대한 동작을 설정합니다
pdfOptions->set_SaveMetafilesAsPng(true);
// 텍스트 압축 수준을 설정합니다
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// PDF 표준을 정의합니다
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// 프레젠테이션을 PDF로 저장합니다
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
다음 예제는 숨겨진 슬라이드를 포함하여 PowerPoint를 PDF로 변환하는 방법을 보여줍니다.
```cpp
// PowerPoint 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// PdfOptions 클래스를 인스턴스화합니다
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// 숨겨진 슬라이드를 추가합니다
pdfOptions->set_ShowHiddenSlides(true);
// 프레젠테이션을 PDF로 저장합니다
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
다음 예제는 비밀번호로 보호된 PDF로 PowerPoint를 변환하는 방법을 보여줍니다.
```cpp
// PowerPoint 파일을 나타내는 Presentation 객체를 인스턴스화합니다
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// PDF 비밀번호와 접근 권한을 설정합니다
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// 프레젠테이션을 PDF로 저장합니다
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
다음 예제는 노트를 포함하여 PowerPoint를 PDF로 변환하는 방법을 보여줍니다.
```cpp
// 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Setting Slide Type and Size
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## 참조

* 클래스 [SaveOptions](../saveoptions/)
* 클래스 [IPdfOptions](../ipdfoptions/)
* 네임스페이스 [Aspose::Slides::Export](../)
* 라이브러리 [Aspose.Slides](../../)