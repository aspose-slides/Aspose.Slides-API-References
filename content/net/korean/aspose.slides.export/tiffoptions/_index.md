---
title: TiffOptions
second_title: Aspose.Sildes for .NET API 참조
description: 프레젠테이션을 TIFF 형식으로 저장하는 방법을 제어하는 옵션을 제공합니다.
type: docs
weight: 4570
url: /ko/aspose.slides.export/tiffoptions/
---
## TiffOptions 클래스

프레젠테이션을 TIFF 형식으로 저장하는 방법을 제어하는 옵션을 제공합니다.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TiffOptions](tiffoptions)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | 컬러 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다. 이 옵션은 [`CompressionType`](./compressiontype)가 CCITT4 또는 CCITT3으로 설정된 경우에만 적용됩니다. 읽기/쓰기 [`BlackWhiteConversionMode`](../blackwhiteconversionmode). 기본값은 Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | 압축 유형을 지정합니다. 읽기/쓰기 [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | 소스 폰트를 찾을 수 없는 경우 사용할 폰트를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | 인치당 도트 수로 가로 해상도를 지정합니다. 읽기/쓰기 UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | 인치당 도트 수로 세로 해상도를 지정합니다. 읽기/쓰기 UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | 그라디언트의 시각 스타일을 반환하거나 설정합니다. 읽기/쓰기 [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | 생성된 TIFF 이미지의 크기를 지정합니다. 기본값은 0x0이며, 이는 생성된 이미지 크기가 프레젠테이션 슬라이드 크기를 기준으로 계산된다는 의미입니다. 읽기/쓰기 Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다. 읽기 전용 [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | 생성된 이미지의 픽셀 형식을 지정합니다. 읽기/쓰기 [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | 진행률 업데이트를 백분율로 저장하기 위한 콜백 객체를 나타냅니다. [`IProgressCallback`](../../aspose.slides/iprogresscallback)를 참조하십시오. |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다. 읽기/쓰기 Boolean. 기본값은 **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | 경고를 수신하고 로드 프로세스를 계속 진행할지 중단할지를 결정하는 객체를 반환하거나 설정합니다. 읽기/쓰기 [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### 예제

다음 예제는 기본 크기로 PowerPoint를 TIFF로 변환하는 방법을 보여줍니다.

```csharp
[C#]
// 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // 프레젠테이션을 TIFF 문서로 저장합니다
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

다음 예제는 사용자 지정 크기로 PowerPoint를 TIFF로 변환하는 방법을 보여줍니다.

```csharp
[C#]
// Presentation 파일을 나타내는 Presentation 객체를 인스턴스화합니다
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // TiffOptions 클래스를 인스턴스화합니다
    TiffOptions opts = new TiffOptions();
    // 압축 유형 설정
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // 압축 유형들
    // Default - 기본 압축 방식(LZW)을 지정합니다.
    // None - 압축을 하지 않음을 지정합니다.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // 깊이는 압축 유형에 따라 달라지며 수동으로 설정할 수 없습니다.
    // 해상도 단위는 항상 “2”(인치당 도트)와 같습니다.
    // 이미지 DPI 설정
    opts.DpiX = 200;
    opts.DpiY = 100;
    // 이미지 크기 설정
    opts.ImageSize = new Size(1728, 1078);
    // 지정된 이미지 크기로 프레젠테이션을 TIFF로 저장합니다
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

다음 예제는 사용자 지정 이미지 픽셀 형식으로 PowerPoint를 TIFF로 변환하는 방법을 보여줍니다.

```csharp
[C#]
// Presentation 파일을 나타내는 Presentation 객체를 인스턴스화합니다
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat은 다음 값을 포함합니다(문서에서 볼 수 있음):
    Format1bppIndexed; // 픽셀당 1비트, 인덱스된.
    Format4bppIndexed; // 픽셀당 4비트, 인덱스된.
    Format8bppIndexed; // 픽셀당 8비트, 인덱스된.
    Format24bppRgb; // 픽셀당 24비트, RGB.
    Format32bppArgb; // 픽셀당 32비트, ARGB.
    */
    // 지정된 이미지 크기로 프레젠테이션을 TIFF로 저장합니다
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### 참고

* 클래스 [SaveOptions](../saveoptions)
* 인터페이스 [ITiffOptions](../itiffoptions)
* 네임스페이스 [Aspose.Slides.Export](../../aspose.slides.export)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->