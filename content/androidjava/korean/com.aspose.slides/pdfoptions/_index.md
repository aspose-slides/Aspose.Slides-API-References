---
title: PdfOptions
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 프레젠테이션을 PDF 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
type: docs
url: /ko/com.aspose.slides/pdfoptions/
---
**상속:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)  
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

프레젠테이션을 PDF 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // PdfOptions 클래스를 인스턴스화합니다
>      PdfOptions pdfOptions = new PdfOptions();
>      // Jpeg 품질을 설정합니다
>      pdfOptions.setJpegQuality((byte)90);
>      // 메타파일 동작을 설정합니다
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // 텍스트 압축 수준을 설정합니다
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // PDF 표준을 정의합니다
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // 프레젠테이션을 PDF로 저장합니다
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // PowerPoint 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // PdfOptions 클래스를 인스턴스화합니다
>      PdfOptions pdfOptions = new PdfOptions();
>      // 숨겨진 슬라이드를 추가합니다
>      pdfOptions.setShowHiddenSlides(true);
>      // 프레젠테이션을 PDF로 저장합니다
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // PowerPoint 파일을 나타내는 Presentation 객체를 인스턴스화합니다
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // PdfOptions 클래스를 인스턴스화합니다
>      PdfOptions pdfOptions = new PdfOptions();
>      // PDF 비밀번호 및 접근 권한을 설정합니다
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // 프레젠테이션을 PDF로 저장합니다
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // 슬라이드 유형 및 크기 설정
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructors

| 생성자 | 설명 |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | 기본 생성자. |
## Methods

| 메서드 | 설명 |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 방식을 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 방식을 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [getTextCompression()](#getTextCompression--) | 문서의 모든 텍스트 내용에 사용할 압축 유형을 지정합니다. |
| [setTextCompression(int value)](#setTextCompression-int-) | 문서의 모든 텍스트 내용에 사용할 압축 유형을 지정합니다. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | 각 이미지에 대해 가장 효과적인 압축(기본 압축 대신)을 자동으로 선택해야 하는지 여부를 나타냅니다. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | 각 이미지에 대해 가장 효과적인 압축(기본 압축 대신)을 자동으로 선택해야 하는지 여부를 나타냅니다. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Aspose.Slides가 ASCII(33..127 코드 범위) 텍스트에 대해 일반 폰트를 포함할지 여부를 결정합니다. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Aspose.Slides가 ASCII(33..127 코드 범위) 텍스트에 대해 일반 폰트를 포함할지 여부를 결정합니다. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Aspose.Slides가 일반 폰트로 간주해야 하는 사용자 정의 폰트 패밀리 이름 배열을 반환하거나 설정합니다. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Aspose.Slides가 일반 폰트로 간주해야 하는 사용자 정의 폰트 패밀리 이름 배열을 반환하거나 설정합니다. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | 폰트의 모든 문자를 포함할지 또는 사용된 부분집합만 포함할지를 결정합니다. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | 폰트의 모든 문자를 포함할지 또는 사용된 부분집합만 포함할지를 결정합니다. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | 폰트가 굵게 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장해야 하는지 여부를 나타냅니다. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | 폰트가 굵게 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장해야 하는지 여부를 나타냅니다. |
| [getJpegQuality()](#getJpegQuality--) | PDF 문서 내 JPEG 이미지의 품질을 결정하는 값을 반환하거나 설정합니다. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF 문서 내 JPEG 이미지의 품질을 결정하는 값을 반환하거나 설정합니다. |
| [getCompliance()](#getCompliance--) | 생성된 PDF 문서에 대한 원하는 호환성 수준입니다. |
| [setCompliance(int value)](#setCompliance-int-) | 생성된 PDF 문서에 대한 원하는 호환성 수준입니다. |
| [getPassword()](#getPassword--) | PDF 문서를 보호하기 위한 사용자 암호를 설정합니다. |
| [setPassword(String value)](#setPassword-java.lang.String-) | PDF 문서를 보호하기 위한 사용자 암호를 설정합니다. |
| [getAccessPermissions()](#getAccessPermissions--) | 문서를 사용자 액세스로 열 때 부여될 액세스 권한을 지정하는 플래그 집합을 포함합니다. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | 문서를 사용자 액세스로 열 때 부여될 액세스 권한을 지정하는 플래그 집합을 포함합니다. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | 프레젠테이션에서 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | 프레젠테이션에서 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true. |
| [getSufficientResolution()](#getSufficientResolution--) | PDF 문서 내 이미지 해상도를 결정하는 값을 반환하거나 설정합니다. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | PDF 문서 내 이미지 해상도를 결정하는 값을 반환하거나 설정합니다. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 각 슬라이드 주변에 검은색 테두리를 그리려면 true. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 각 슬라이드 주변에 검은색 테두리를 그리려면 true. |
| [getImageTransparentColor()](#getImageTransparentColor--) | 이미지 투명 색상을 가져오거나 설정합니다. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | 이미지 투명 색상을 가져오거나 설정합니다. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | true인 경우 지정된 투명 색상을 이미지에 적용합니다. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | true인 경우 지정된 투명 색상을 이미지에 적용합니다. |
| [getIncludeOleData()](#getIncludeOleData--) | 프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 true. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | 프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 true. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

기본 생성자.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 방식을 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**  
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 방식을 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다. 읽기 전용 [IInkOptions](../../com.aspose.slides/iinkoptions)

**반환값:**  
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 false입니다.

**반환값:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 false입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

문서의 모든 텍스트 내용에 사용할 압축 유형을 지정합니다. 읽기/쓰기 [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

기본값은 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)입니다.

**반환값:**  
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

문서의 모든 텍스트 내용에 사용할 압축 유형을 지정합니다. 읽기/쓰기 [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

기본값은 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

각 이미지에 대해 가장 효과적인 압축(기본 압축 대신)을 자동으로 선택해야 하는지 여부를 나타냅니다. true로 설정하면 프레젠테이션의 모든 이미지에 대해 가장 적절한 압축 알고리즘이 선택되어 결과 PDF 문서의 크기가 작아집니다.

--------------------

최적 이미지 압축 비율 선택은 계산 비용이 많이 들고 추가 메모리를 사용하며, 기본값은 false입니다.

--------------------

기본값은 false입니다.

**반환값:**  
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

각 이미지에 대해 가장 효과적인 압축(기본 압축 대신)을 자동으로 선택해야 하는지 여부를 나타냅니다. true로 설정하면 프레젠테이션의 모든 이미지에 대해 가장 적절한 압축 알고리즘이 선택되어 결과 PDF 문서의 크기가 작아집니다.

--------------------

최적 이미지 압축 비율 선택은 계산 비용이 많이 들고 추가 메모리를 사용하며, 기본값은 false입니다.

--------------------

기본값은 false입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Aspose.Slides가 ASCII(33..127 코드 범위) 텍스트에 대해 일반 폰트를 포함할지 여부를 결정합니다. 127보다 큰 문자 코드는 항상 포함됩니다. 일반 폰트 목록에는 PDF 기본 14 폰트와 추가 사용자 지정 폰트가 포함됩니다. 읽기/쓰기 boolean.

--------------------

기본값은 **true**입니다.

**반환값:**  
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Aspose.Slides가 ASCII(33..127 코드 범위) 텍스트에 대해 일반 폰트를 포함할지 여부를 결정합니다. 127보다 큰 문자 코드는 항상 포함됩니다. 일반 폰트 목록에는 PDF 기본 14 폰트와 추가 사용자 지정 폰트가 포함됩니다. 읽기/쓰기 boolean.

--------------------

기본값은 **true**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Aspose.Slides가 일반 폰트로 간주해야 하는 사용자 정의 폰트 패밀리 이름 배열을 반환하거나 설정합니다. 읽기/쓰기 String[].

**반환값:**  
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Aspose.Slides가 일반 폰트로 간주해야 하는 사용자 정의 폰트 패밀리 이름 배열을 반환하거나 설정합니다. 읽기/쓰기 String[].

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

폰트의 모든 문자를 포함할지 또는 사용된 부분집합만 포함할지를 결정합니다. 읽기/쓰기 boolean.

--------------------

기본값은 **false**입니다.

**반환값:**  
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

폰트의 모든 문자를 포함할지 또는 사용된 부분집합만 포함할지를 결정합니다. 읽기/쓰기 boolean.

--------------------

기본값은 **false**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

폰트가 굵게 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장해야 하는지 여부를 나타냅니다. 이 방법은 특정 폰트에 대해 결과 PDF의 텍스트 품질을 향상시킬 수 있습니다. 읽기/쓰기 boolean.

--------------------

기본값은 **false**입니다.

**반환값:**  
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

폰트가 굵게 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장해야 하는지 여부를 나타냅니다. 이 방법은 특정 폰트에 대해 결과 PDF의 텍스트 품질을 향상시킬 수 있습니다. 읽기/쓰기 boolean.

--------------------

기본값은 **false**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

PDF 문서 내 JPEG 이미지의 품질을 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 byte.

--------------------

문서에 JPEG 이미지가 포함된 경우에만 영향을 미칩니다.

PDF 형식으로 저장할 때 이미지 품질을 설정하거나 가져오는 데 이 속성을 사용하십시오. 값은 0에서 100 사이이며, 0은 최악의 품질이지만 최대 압축, 100은 최고의 품질이지만 최소 압축을 의미합니다.

기본값은 **100**입니다.

**반환값:**  
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

PDF 문서 내 JPEG 이미지의 품질을 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 byte.

--------------------

문서에 JPEG 이미지가 포함된 경우에만 영향을 미칩니다.

PDF 형식으로 저장할 때 이미지 품질을 설정하거나 가져오는 데 이 속성을 사용하십시오. 값은 0에서 100 사이이며, 0은 최악의 품질이지만 최대 압축, 100은 최고의 품질이지만 최소 압축을 의미합니다.

기본값은 **100**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

생성된 PDF 문서에 대한 원하는 호환성 수준입니다. 읽기/쓰기 [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

기본값은 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)입니다.

**반환값:**  
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

생성된 PDF 문서에 대한 원하는 호환성 수준입니다. 읽기/쓰기 [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

기본값은 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

PDF 문서를 보호하기 위한 사용자 암호를 설정합니다. 읽기/쓰기 String.

**반환값:**  
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

PDF 문서를 보호하기 위한 사용자 암호를 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

문서를 사용자 액세스로 열 때 부여될 액세스 권한을 지정하는 플래그 집합을 포함합니다. [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions) 참고.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환값:**  
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

문서를 사용자 액세스로 열 때 부여될 액세스 권한을 지정하는 플래그 집합을 포함합니다. [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions) 참고.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

프레젠테이션에서 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true. 읽기/쓰기 boolean.

--------------------

기본값은 **true**입니다. PDF 문서는 벡터 그래픽과 래스터 이미지를 포함할 수 있습니다. SaveMetafilesAsPng이 true이면 원본 메타파일 이미지가 PNG 형식으로 변환되어 래스터 이미지로 PDF에 저장됩니다. false이면 원본 메타파일이 PDF 벡터 그래픽으로 변환됩니다. 각 접근 방식마다 장단점이 있습니다. 예를 들어 메타파일을 PNG로 변환하면 결과 문서 스케일링 시 품질 손실이 발생할 수 있습니다. PDF 벡터 그래픽으로 변환하면 PDF 뷰어에서 성능 문제가 발생할 수 있습니다.

**반환값:**  
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

프레젠테이션에서 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true. 읽기/쓰기 boolean.

--------------------

기본값은 **true**입니다. PDF 문서는 벡터 그래픽과 래스터 이미지를 포함할 수 있습니다. SaveMetafilesAsPng이 true이면 원본 메타파일 이미지가 PNG 형식으로 변환되어 래스터 이미지로 PDF에 저장됩니다. false이면 원본 메타파일이 PDF 벡터 그래픽으로 변환됩니다. 각 접근 방식마다 장단점이 있습니다. 예를 들어 메타파일을 PNG로 변환하면 결과 문서 스케일링 시 품질 손실이 발생할 수 있습니다. PDF 벡터 그래픽으로 변환하면 PDF 뷰어에서 성능 문제가 발생할 수 있습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

PDF 문서 내 이미지 해상도를 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 float.

값: 이 매개변수의 효과는 몇 가지 요소에 따라 다릅니다. 알고리즘은 속성 값, 원본 이미지 크기 및 이미지 프레임 크기를 기준으로 최적 출력 이미지 크기를 얻으려고 합니다. 유사한 속성 값을 사용하면 동일한 결과가 나올 수 있습니다. 눈에 보이는 효과를 얻으려면 16 또는 32 단계 사용을 권장합니다.

--------------------

속성은 파일 크기, 내보내기 시간 및 이미지 품질에 영향을 줍니다.

기본값은 **96**입니다.

**반환값:**  
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

PDF 문서 내 이미지 해상도를 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 float.

값: 이 매개변수의 효과는 몇 가지 요소에 따라 다릅니다. 알고리즘은 속성 값, 원본 이미지 크기 및 이미지 프레임 크기를 기준으로 최적 출력 이미지 크기를 얻으려고 합니다. 유사한 속성 값을 사용하면 동일한 결과가 나올 수 있습니다. 눈에 보이는 효과를 얻으려면 16 또는 32 단계 사용을 권장합니다.

--------------------

속성은 파일 크기, 내보내기 시간 및 이미지 품질에 영향을 줍니다.

기본값은 **96**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

각 슬라이드 주변에 검은색 테두리를 그리려면 true. 읽기/쓰기 boolean.

--------------------

기본값은 **false**입니다.

**반환값:**  
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

각 슬라이드 주변에 검은색 테두리를 그리려면 true. 읽기/쓰기 boolean.

--------------------

기본값은 **false**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

이미지 투명 색상을 가져오거나 설정합니다.

값: 이미지 투명 색상.

**반환값:**  
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

이미지 투명 색상을 가져오거나 설정합니다.

값: 이미지 투명 색상.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

true인 경우 지정된 투명 색상을 이미지에 적용합니다.

**반환값:**  
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

true인 경우 지정된 투명 색상을 이미지에 적용합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 true. 읽기/쓰기 boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

기본값은 **false**입니다.

**반환값:**  
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 true. 읽기/쓰기 boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

기본값은 **false**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |