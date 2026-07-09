---
title: PdfOptions
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 프레젠테이션을 Pdf 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
type: docs
weight: 4330
url: /ko/aspose.slides.export/pdfoptions/
---
## PdfOptions 클래스

프레젠테이션을 PDF 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfOptions](pdfoptions)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | 문서가 사용자 액세스로 열릴 때 부여되어야 하는 액세스 권한을 지정하는 플래그 집합을 포함합니다. [`PdfAccessPermissions`](../pdfaccesspermissions)을(를) 참조하십시오. |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Aspose.Slides가 공통으로 간주해야 하는 사용자 정의 폰트 패밀리 이름 배열을 반환하거나 설정합니다. 읽기/쓰기 String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | `true`인 경우 지정된 투명 색상을 이미지에 적용합니다. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | 각 이미지에 대해 기본 압축 대신 가장 효과적인 압축을 자동으로 선택해야 하는지 여부를 나타냅니다. Boolean.true로 설정하면 프레젠테이션의 모든 이미지에 대해 가장 적합한 압축 알고리즘이 선택되어 결과 PDF 문서의 크기가 작아집니다. 최상의 이미지 압축 비율 선택은 계산 비용이 많이 들고 추가 메모리를 사용하며, 기본값은 Boolean.false입니다. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | 생성된 PDF 문서에 대한 원하는 적합성 수준입니다. 읽기/쓰기 [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | 소스 폰트를 찾을 수 없는 경우 사용할 폰트를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | `true`인 경우 각 슬라이드 주변에 검은 프레임을 그립니다. 읽기/쓰기 Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | 폰트의 모든 문자들을 포함시킬지 아니면 사용된 부분집합만 포함시킬지 결정합니다. 읽기/쓰기 Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Aspose.Slides가 ASCII(33..127 코드 범위) 텍스트에 대해 일반 폰트를 포함시킬지 여부를 결정합니다. 127보다 큰 문자 코드는 항상 포함됩니다. 일반 폰트 목록에는 PDF의 기본 14 폰트와 추가 사용자 지정 폰트가 포함됩니다. 읽기/쓰기 Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | 그라디언트의 시각 스타일을 반환하거나 설정합니다. 읽기/쓰기 [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | 이미지 투명 색상을 가져오거나 설정합니다. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | `true`인 경우 프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환합니다. 읽기/쓰기 Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | 내보낸 문서에서 잉크 객체의 모양을 제어하는 옵션을 제공합니다. 읽기 전용 [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | PDF 문서 내 JPEG 이미지의 품질을 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | PDF 문서를 보호하기 위한 사용자 비밀번호를 설정합니다. 읽기/쓰기 String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | 저장 진행률 업데이트를 백분율로 제공하는 콜백 객체를 나타냅니다. [`IProgressCallback`](../../aspose.slides/iprogresscallback)을(를) 참조하십시오. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | 폰트가 굵은 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장할지 여부를 나타냅니다. 이 방법은 특정 폰트에 대해 결과 PDF의 텍스트 품질을 향상시킬 수 있습니다. 읽기/쓰기 Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | `true`인 경우 프레젠테이션에서 사용된 모든 메타파일을 PNG 이미지로 변환합니다. 읽기/쓰기 Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 `false`입니다. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다. 읽기/쓰기 Boolean. 기본값은 **false**입니다. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | PDF 문서 내 이미지 해상도를 결정하는 값을 반환하거나 설정합니다. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | 문서 내 모든 텍스트 내용에 사용할 압축 유형을 지정합니다. 읽기/쓰기 [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | 경고를 수신하고 로드 프로세스를 계속할지 중단할지를 결정하는 객체를 반환하거나 설정합니다. 읽기/쓰기 [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### 예제

다음 예제는 사용자 지정 옵션으로 PowerPoint를 PDF로 변환하는 방법을 보여줍니다.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// PdfOptions 클래스를 인스턴스화합니다
	PdfOptions pdfOptions = new PdfOptions();
	// Jpeg 품질을 설정합니다
	pdfOptions.JpegQuality = 90;
	// 메타파일에 대한 동작을 설정합니다
	pdfOptions.SaveMetafilesAsPng = true;
	// 텍스트 압축 수준을 설정합니다
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// PDF 표준을 정의합니다
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// 프레젠테이션을 PDF로 저장합니다
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

다음 예제는 숨겨진 슬라이드를 포함하여 PowerPoint를 PDF로 변환하는 방법을 보여줍니다.

```csharp
[C#]
// PowerPoint 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// PdfOptions 클래스를 인스턴스화합니다
	PdfOptions pdfOptions = new PdfOptions();
	// 숨겨진 슬라이드를 추가합니다
	pdfOptions.ShowHiddenSlides = true;
	// 프레젠테이션을 PDF로 저장합니다
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

다음 예제는 PowerPoint를 암호로 보호된 PDF로 변환하는 방법을 보여줍니다.

```csharp
[C#]
// PowerPoint 파일을 나타내는 Presentation 객체를 인스턴스화합니다
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// PdfOptions 클래스를 인스턴스화합니다
	PdfOptions pdfOptions = new PdfOptions();
	// PDF 비밀번호와 액세스 권한을 설정합니다
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// 프레젠테이션을 PDF로 저장합니다
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

다음 예제는 노트를 포함하여 PowerPoint를 PDF로 변환하는 방법을 보여줍니다.

```csharp
[C#]
// 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// 슬라이드 유형 및 크기 설정
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### 참고

* 클래스 [SaveOptions](../saveoptions)
* 인터페이스 [IPdfOptions](../ipdfoptions)
* 네임스페이스 [Aspose.Slides.Export](../../aspose.slides.export)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->