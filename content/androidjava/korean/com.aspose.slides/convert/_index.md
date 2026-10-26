---
title: Convert
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 변환을 목적으로 하는 메서드 그룹을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/convert/
---
**상속:**
java.lang.Object
```
public class Convert
```

[Presentation](../../com.aspose.slides/presentation)를 변환하기 위한 메서드 그룹을 나타냅니다.

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Convert()](#Convert--) |  |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation)를 전달된 출력 경로 확장자를 사용하여 필요한 내보내기 형식을 결정합니다. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation)를 PDF로 변환합니다. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | [Presentation](../../com.aspose.slides/presentation)를 PDF로 변환합니다. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation)를 PDF로 변환합니다. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | [Presentation](../../com.aspose.slides/presentation)를 PDF로 변환합니다. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation)를 SVG로 변환합니다. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | [Presentation](../../com.aspose.slides/presentation)를 SVG로 변환합니다. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | [Presentation](../../com.aspose.slides/presentation)를 SVG로 변환합니다. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | [Presentation](../../com.aspose.slides/presentation)를 SVG로 변환합니다. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | [Presentation](../../com.aspose.slides/presentation)를 SVG로 변환합니다. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | 입력 프레젠테이션을 JPEG 형식 이미지 세트로 변환합니다. |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | 입력 프레젠테이션을 JPEG 형식 이미지 세트로 변환합니다. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | 입력 프레젠테이션을 JPEG 형식 이미지 세트로 변환합니다. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | 입력 프레젠테이션을 PNG 형식 이미지 세트로 변환합니다. |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | 입력 프레젠테이션을 PNG 형식 이미지 세트로 변환합니다. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | 입력 프레젠테이션을 PNG 형식 이미지 세트로 변환합니다. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | 입력 프레젠테이션을 TIFF 형식 이미지 세트로 변환합니다. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | 입력 프레젠테이션을 사용자 지정 옵션으로 TIFF 형식으로 변환합니다. |

### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

[Presentation](../../com.aspose.slides/presentation)를 전달된 출력 경로 확장자를 사용하여 필요한 내보내기 형식을 결정합니다.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| presPath | java.lang.String | 입력 프레젠테이션의 경로 |
| outPath | java.lang.String | 출력 경로 |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

[Presentation](../../com.aspose.slides/presentation)를 PDF로 변환합니다.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| presPath | java.lang.String | 입력 프레젠테이션의 경로 |
| outPath | java.lang.String | 출력 경로 |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

[Presentation](../../com.aspose.slides/presentation)를 PDF로 변환합니다.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| presPath | java.lang.String | 입력 프레젠테이션의 경로 |
| outPath | java.lang.String | 출력 경로 |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | PDF 출력 옵션 |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

[Presentation](../../com.aspose.slides/presentation)를 PDF로 변환합니다.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 입력 프레젠테이션 |
| outPath | java.lang.String | 출력 경로 |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

[Presentation](../../com.aspose.slides/presentation)를 PDF로 변환합니다.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.setCompliance(PdfCompliance.PdfUa);
>      Convert.toPdf(pres, "output.pdf", pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 입력 프레젠테이션 |
| outPath | java.lang.String | 출력 경로 |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | PDF 출력 옵션 |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

[Presentation](../../com.aspose.slides/presentation)를 SVG로 변환합니다.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| presPath | java.lang.String | 입력 프레젠테이션의 경로 |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

[Presentation](../../com.aspose.slides/presentation)를 SVG로 변환합니다.

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| presPath | java.lang.String | 입력 프레젠테이션의 경로 |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | 프레젠테이션의 각 슬라이드에 대한 SVG 출력 경로를 반환하는 콜백 |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

[Presentation](../../com.aspose.slides/presentation)를 SVG로 변환합니다.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, new Convert.GetOutPathCallback() {
>          public String invoke(Slide slide, int index) {
>              return String.format("pres_%d-out.svg", index);
>          }
>      });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 입력 프레젠테이션 |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | 프레젠테이션의 각 슬라이드에 대한 SVG 출력 경로를 반환하는 콜백 |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

[Presentation](../../com.aspose.slides/presentation)를 SVG로 변환합니다.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      SVGOptions svgOptions = new SVGOptions();
>      svgOptions.setVectorizeText(true);
>      Convert.toSvg(pres, svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 입력 프레젠테이션 |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 내보내기 옵션 |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

[Presentation](../../com.aspose.slides/presentation)를 SVG로 변환합니다.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      SVGOptions svgOptions = new SVGOptions();
>      svgOptions.setVectorizeText(true);
>      Convert.toSvg(pres, new Convert.GetOutPathCallback() {
>          public String invoke(Slide slide, int index) {
>              return String.format("pres_%d-out.svg", index);
>          }
>      }, svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 입력 프레젠테이션 |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | 프레젠테이션의 각 슬라이드에 대한 SVG 출력 경로를 반환하는 콜백 |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 내보내기 옵션 |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

입력 프레젠테이션을 JPEG 형식 이미지 세트로 변환합니다. 출력 파일 이름을 "myPath/myFilename.jpeg" 로 지정하면 결과가 "myPath/myFilename_N.jpeg" 파일 세트로 저장되며, N은 슬라이드 번호입니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 입력 프레젠테이션. |
| outputFileName | java.lang.String | 출력 파일 이름. |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```

입력 프레젠테이션을 JPEG 형식 이미지 세트로 변환합니다. 출력 파일 이름을 "myPath/myFilename.jpeg" 로 지정하면 결과가 "myPath/myFilename_N.jpeg" 파일 세트로 저장되며, N은 슬라이드 번호입니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 입력 프레젠테이션 |
| outputFileName | java.lang.String | 출력 파일 이름. |
| imageSize | [Size](../../com.aspose.slides.android/size) | 생성된 각 이미지의 크기. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

입력 프레젠테이션을 JPEG 형식 이미지 세트로 변환합니다. 출력 파일 이름을 "myPath/myFilename.jpeg" 로 지정하면 결과가 "myPath/myFilename_N.jpeg" 파일 세트로 저장되며, N은 슬라이드 번호입니다.

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  IRenderingOptions options = new RenderingOptions();
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", 2f, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 입력 프레젠테이션. |
| outputFileName | java.lang.String | 출력 파일 이름. |
| scale | float | 원본 슬라이드 크기에 비례하여 출력 이미지에 적용되는 스케일링 팩터. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 렌더링 옵션. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

입력 프레젠테이션을 PNG 형식 이미지 세트로 변환합니다. 출력 파일 이름을 "myPath/myFilename.png" 로 지정하면 결과가 "myPath/myFilename_N.png" 파일 세트로 저장되며, N은 슬라이드 번호입니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 입력 프레젠테이션. |
| outputFileName | java.lang.String | 출력 파일 이름. |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```

입력 프레젠테이션을 PNG 형식 이미지 세트로 변환합니다. 출력 파일 이름을 "myPath/myFilename.png" 로 지정하면 결과가 "myPath/myFilename_N.png" 파일 세트로 저장되며, N은 슬라이드 번호입니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 입력 프레젠테이션 |
| outputFileName | java.lang.String | 출력 파일 이름. |
| imageSize | [Size](../../com.aspose.slides.android/size) | 생성된 각 이미지의 크기. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

입력 프레젠테이션을 PNG 형식 이미지 세트로 변환합니다. 출력 파일 이름을 "myPath/myFilename.png" 로 지정하면 결과가 "myPath/myFilename_N.png" 파일 세트로 저장되며, N은 슬라이드 번호입니다.

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions= new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  IRenderingOptions options = new RenderingOptions();
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", 2f, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 입력 프레젠테이션. |
| outputFileName | java.lang.String | 출력 파일 이름. |
| scale | float | 원본 슬라이드 크기에 비례하여 출력 이미지에 적용되는 스케일링 팩터. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 렌더링 옵션. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

입력 프레젠테이션을 TIFF 형식 이미지 세트로 변환합니다. 출력 파일 이름을 "myPath/myFilename.tiff" 로 지정하면 결과가 "myPath/myFilename_N.tiff" 파일 세트로 저장되며, N은 슬라이드 번호입니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 입력 프레젠테이션. |
| outputFileName | java.lang.String | 출력 파일 이름. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

입력 프레젠테이션을 사용자 지정 옵션으로 TIFF 형식으로 변환합니다. 출력 파일 이름을 "myPath/myFilename.tiff" 로 지정하고 multipage가 false인 경우 결과가 "myPath/myFilename_N.tiff" 파일 세트로 저장되며, N은 슬라이드 번호입니다. 반대로 multipage가 true인 경우 결과는 다중 페이지 "myPath/myFilename.tiff" 문서가 됩니다.

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions= new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  ITiffOptions options = new TiffOptions();
>  options.setCompressionType(TiffCompressionTypes.CCITT3);
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "pres.tiff", options, false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 입력 프레젠테이션. |
| outputFileName | java.lang.String | 출력 파일 이름. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | TIFF 저장 옵션. |
| multipage | boolean | 생성된 TIFF 문서가 다중 페이지인지 여부를 지정합니다. |