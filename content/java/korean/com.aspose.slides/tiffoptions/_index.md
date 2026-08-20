---
title: TiffOptions
second_title: Aspose.Slides for Java API 레퍼런스
description: 프레젠테이션을 TIFF 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
type: docs
url: /ko/com.aspose.slides/tiffoptions/
---
**상속:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**구현된 모든 인터페이스:**  
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)  
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

프레젠테이션을 TIFF 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // 프레젠테이션을 TIFF 문서로 저장합니다
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // TiffOptions 클래스를 인스턴스화합니다
>      TiffOptions opts = new TiffOptions();
>      // 압축 유형을 설정합니다
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // 압축 유형
>      // Default - 기본 압축 방식(LZW)을 지정합니다.
>      // None - 압축을 사용하지 않음을 지정합니다.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // 깊이는 압축 유형에 따라 달라지며 수동으로 설정할 수 없습니다.
>      // 해상도 단위는 항상 2(인치당 도트)와 같습니다.
>      // 이미지 DPI 설정
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // 이미지 크기 설정
>      opts.setImageSize(new Dimension(1728, 1078));
>      // 지정된 이미지 크기로 프레젠테이션을 TIFF로 저장합니다
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      // ImagePixelFormat은 다음 값을 포함합니다(문서에 표시된 대로):
>      //Format1bppIndexed; // 1비트당 픽셀, 인덱스됨.
>      //Format4bppIndexed; // 4비트당 픽셀, 인덱스됨.
>      //Format8bppIndexed; // 8비트당 픽셀, 인덱스됨.
>      //Format24bppRgb; // 24비트당 픽셀, RGB.
>      //Format32bppArgb; // 32비트당 픽셀, ARGB.
> 
>      // 지정된 이미지 크기로 프레젠테이션을 TIFF로 저장합니다
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | 기본 생성자. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | 내보낸 문서에서 Ink 개체의 모양을 제어하는 옵션을 제공합니다. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [getImageSize()](#getImageSize--) | 생성된 TIFF 이미지의 크기를 지정합니다. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | 생성된 TIFF 이미지의 크기를 지정합니다. |
| [getDpiX()](#getDpiX--) | 인치당 도트 수로 가로 해상도를 지정합니다. |
| [setDpiX(long value)](#setDpiX-long-) | 인치당 도트 수로 가로 해상도를 지정합니다. |
| [getDpiY()](#getDpiY--) | 인치당 도트 수로 세로 해상도를 지정합니다. |
| [setDpiY(long value)](#setDpiY-long-) | 인치당 도트 수로 세로 해상도를 지정합니다. |
| [getCompressionType()](#getCompressionType--) | 압축 유형을 지정합니다. |
| [setCompressionType(int value)](#setCompressionType-int-) | 압축 유형을 지정합니다. |
| [getPixelFormat()](#getPixelFormat--) | 생성된 이미지의 픽셀 형식을 지정합니다. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | 생성된 이미지의 픽셀 형식을 지정합니다. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | 컬러 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | 컬러 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다. |

### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

기본 생성자.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

내보낸 문서에서 Ink 개체의 모양을 제어하는 옵션을 제공합니다. 읽기 전용 [IInkOptions](../../com.aspose.slides/iinkoptions)

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Dimension getImageSize()
```

생성된 TIFF 이미지의 크기를 지정합니다. 기본값은 0x0이며, 이는 생성된 이미지 크기가 프레젠테이션 슬라이드 크기 값을 기반으로 계산됨을 의미합니다. 읽기/쓰기 java.awt.Dimension.

**반환값:**  
java.awt.Dimension

### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public final void setImageSize(Dimension value)
```

생성된 TIFF 이미지의 크기를 지정합니다. 기본값은 0x0이며, 이는 생성된 이미지 크기가 프레젠테이션 슬라이드 크기 값을 기반으로 계산됨을 의미합니다. 읽기/쓰기 java.awt.Dimension.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

인치당 도트 수로 가로 해상도를 지정합니다. 읽기/쓰기 long.

**반환값:**  
long

### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

인치당 도트 수로 가로 해상도를 지정합니다. 읽기/쓰기 long.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

인치당 도트 수로 세로 해상도를 지정합니다. 읽기/쓰기 long.

**반환값:**  
long

### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

인치당 도트 수로 세로 해상도를 지정합니다. 읽기/쓰기 long.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

압축 유형을 지정합니다. 읽기/쓰기 [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**반환값:**  
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

압축 유형을 지정합니다. 읽기/쓰기 [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

생성된 이미지의 픽셀 형식을 지정합니다. 읽기/쓰기 [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**반환값:**  
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

생성된 이미지의 픽셀 형식을 지정합니다. 읽기/쓰기 [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
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

프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public final int getBwConversionMode()
```

컬러 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다. 이 옵션은 CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) 가 [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) 또는 [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) 로 설정된 경우에만 적용됩니다. 읽기/쓰기 [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). 기본값은 [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환값:**  
int

### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public final void setBwConversionMode(int value)
```

컬러 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다. 이 옵션은 CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) 가 [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) 또는 [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) 로 설정된 경우에만 적용됩니다. 읽기/쓰기 [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). 기본값은 [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |