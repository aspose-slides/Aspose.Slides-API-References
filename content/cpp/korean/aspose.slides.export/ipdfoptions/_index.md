---
title: IPdfOptions
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션을 PDF 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
type: docs
weight: 274
url: /ko/aspose.slides.export/ipdfoptions/
---
## IPdfOptions 클래스

Provides options that control how a presentation is saved in Pdf format.

```cpp
class IPdfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C#-스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C#-스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() | 사용자가 접근으로 문서를 열 때 부여되어야 할 접근 권한을 지정하는 플래그 집합을 포함합니다. [PdfAccessPermissions](../pdfaccesspermissions/)를 참조하십시오. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() | 사용자 정의 폰트 패밀리 이름 배열을 반환합니다. [Aspose.Slides](../../aspose.slides/)가 일반으로 간주해야 합니다. [System::String](../../system/string/)[]를 읽으십시오. |
| virtual **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() | 지정된 투명 색을 이미지에 적용합니다 (**true**인 경우). |
| virtual **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() | 각 이미지에 대해 가장 효과적인 압축(기본 압축이 아니라)을 자동으로 선택해야 하는지 여부를 나타냅니다. **bool**.true 로 설정하면 프레젠테이션의 모든 이미지에 대해 가장 적합한 압축 알고리즘이 선택되어 결과 PDF 문서의 크기가 작아집니다. |
| virtual [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() | 생성된 PDF 문서에 대한 원하는 준수 수준입니다. [PdfCompliance](../pdfcompliance/)를 읽으십시오. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | 소스 폰트를 찾을 수 없는 경우 사용되는 폰트를 반환합니다. [System::String](../../system/string/)를 읽으십시오. |
| virtual **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() | 각 슬라이드에 검은 프레임을 그리려면 **bool**를 true로 설정합니다. **bool**를 읽으십시오. |
| virtual **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() | 폰트의 모든 문자들을 포함할지, 일부만 포함할지 결정합니다. **bool**를 읽으십시오. |
| virtual **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() | ASCII 문자 32-127에 대해 true로 설정하면 True Type 폰트를 포함합니다. [Fonts](../../aspose.slides/fonts/)는 127보다 큰 문자 코드는 항상 포함됩니다. **bool**를 읽으십시오. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | 그라디언트의 시각적 스타일을 반환합니다. [GradientStyle](../../aspose.slides/gradientstyle/)를 읽으십시오. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() | 이미지 투명 색을 가져옵니다. |
| virtual **bool** [get_IncludeOleData](./get_includeoledata/)() | 프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 true로 설정합니다. **bool**를 읽으십시오. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | [Ink](../../aspose.slides.ink/) 객체의 외관을 제어하는 옵션을 제공합니다. 읽기 전용 [IInkOptions](../iinkoptions/) |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | PDF 문서 내 JPEG 이미지 품질을 결정하는 값을 반환합니다. **uint8_t**를 읽으십시오. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | PDF 문서를 보호하기 위해 사용자 비밀번호를 설정합니다. [System::String](../../system/string/)를 읽으십시오. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | 진행 상황을 백분율로 저장하기 위한 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)를 참조하십시오. |
| virtual **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() | 폰트가 굵게 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장해야 하는지 여부를 나타냅니다. 이 방법은 특정 폰트에 대해 결과 PDF의 텍스트 품질을 향상시킬 수 있습니다. **bool**를 읽으십시오. |
| virtual **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() | 프레젠테이션에서 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true로 설정합니다. **bool**를 읽으십시오. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 **false**입니다. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다. **bool**를 읽으십시오. 기본값은 **false**입니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 방식을 가져옵니다 [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual **float** [get_SufficientResolution](./get_sufficientresolution/)() | PDF 문서 내 이미지 해상도를 결정하는 값을 반환합니다. |
| virtual [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() | 문서의 모든 텍스트 콘텐츠에 사용할 압축 유형을 지정합니다. [PdfTextCompression](../pdftextcompression/)를 읽으십시오. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | 경고를 받고 로드 과정이 계속될지 중단될지를 결정하는 객체를 반환합니다. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)를 읽으십시오. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 버전입니다. 사용자 정의 객체의 해싱을 활성화합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 버전입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사 버전입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 버전입니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) | 문서를 사용자 접근으로 열 때 부여될 접근 권한을 지정하는 플래그 집합을 포함합니다. [PdfAccessPermissions](../pdfaccesspermissions/)를 참조하십시오. |
| virtual void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | 사용자 정의 폰트 패밀리 이름 배열을 설정합니다. [Aspose.Slides](../../aspose.slides/)가 일반으로 간주해야 합니다. [System::String](../../system/string/)[]를 기록하십시오. |
| virtual void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) | 지정된 투명 색을 이미지에 적용합니다 (**true**인 경우). |
| virtual void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) | 각 이미지에 대해 가장 효과적인 압축(기본 압축이 아니라)을 자동으로 선택해야 하는지 여부를 나타냅니다. **bool**.true 로 설정하면 프레젠테이션의 모든 이미지에 대해 가장 적합한 압축 알고리즘이 선택되어 결과 PDF 문서의 크기가 작아집니다. |
| virtual void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) | 생성된 PDF 문서에 대한 원하는 준수 수준을 지정합니다. [PdfCompliance](../pdfcompliance/)를 기록하십시오. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | 소스 폰트를 찾을 수 없을 경우 사용할 폰트를 설정합니다. [System::String](../../system/string/)에 기록합니다. |
| virtual void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) | 각 슬라이드 주위에 검은 프레임을 그리려면 **bool**를 true로 설정합니다. **bool**를 기록하십시오. |
| virtual void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) | 폰트의 모든 문자를 포함할지, 일부만 포함할지 결정합니다. **bool**를 기록하십시오. |
| virtual void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) | ASCII 문자 32-127에 대해 True Type 폰트를 포함하려면 true로 설정합니다. [Fonts](../../aspose.slides/fonts/)는 127보다 큰 문자 코드는 항상 포함됩니다. **bool**를 기록하십시오. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | 그라디언트의 시각적 스타일을 설정합니다. [GradientStyle](../../aspose.slides/gradientstyle/)에 기록하십시오. |
| virtual void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) | 이미지 투명 색을 설정합니다. |
| virtual void [set_IncludeOleData](./set_includeoledata/)(**bool**) | 프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 **bool**를 true로 설정합니다. **bool**를 기록하십시오. |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | PDF 문서 내 JPEG 이미지 품질을 결정하는 값을 설정합니다. **uint8_t**를 기록하십시오. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | PDF 문서를 보호하기 위해 사용자 비밀번호를 설정합니다. [System::String](../../system/string/)에 기록하십시오. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | 진행 상황을 백분율로 저장하기 위한 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)를 참조하십시오. |
| virtual void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) | 폰트가 굵게 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장해야 하는지 여부를 나타냅니다. 이 방법은 특정 폰트에 대해 결과 PDF의 텍스트 품질을 향상시킬 수 있습니다. **bool**를 기록하십시오. |
| virtual void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) | 프레젠테이션에서 사용된 모든 메타파일을 PNG 이미지로 변환하려면 **bool**를 true로 설정합니다. **bool**를 기록하십시오. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 **false**입니다. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다. **bool**를 기록하십시오. 기본값은 **false**입니다. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 방식을 설정합니다 [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_SufficientResolution](./set_sufficientresolution/)(**float**) | PDF 문서 내 이미지 해상도를 결정하는 값을 설정합니다. |
| virtual void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) | 문서의 모든 텍스트 콘텐츠에 사용할 압축 유형을 지정합니다. [PdfTextCompression](../pdftextcompression/)에 기록하십시오. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 경고를 받고 로드 과정이 계속될지 중단될지를 결정하는 객체를 설정합니다. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)에 기록하십시오. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 대신 약한 포인터로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 버전입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제 기능을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [ISaveOptions](../isaveoptions/)
* 네임스페이스 [Aspose::Slides::Export](../)
* 라이브러리 [Aspose.Slides](../../)