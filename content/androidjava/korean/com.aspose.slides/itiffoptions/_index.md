---
title: ITiffOptions
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 프레젠테이션을 TIFF 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
type: docs
url: /ko/com.aspose.slides/itiffoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

프레젠테이션을 TIFF 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
## Methods

| 메서드 | 설명 |
| --- | --- |
| [getImageSize()](#getImageSize--) | 생성된 TIFF 이미지의 크기를 지정합니다. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | 생성된 TIFF 이미지의 크기를 지정합니다. |
| [getDpiX()](#getDpiX--) | 인치당 도트 수인 가로 해상도를 지정합니다. |
| [setDpiX(long value)](#setDpiX-long-) | 인치당 도트 수인 가로 해상도를 지정합니다. |
| [getDpiY()](#getDpiY--) | 인치당 도트 수인 세로 해상도를 지정합니다. |
| [setDpiY(long value)](#setDpiY-long-) | 인치당 도트 수인 세로 해상도를 지정합니다. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [getCompressionType()](#getCompressionType--) | 압축 유형을 지정합니다. |
| [setCompressionType(int value)](#setCompressionType-int-) | 압축 유형을 지정합니다. |
| [getPixelFormat()](#getPixelFormat--) | 생성된 이미지의 픽셀 형식을 지정합니다. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | 생성된 이미지의 픽셀 형식을 지정합니다. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | 컬러 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | 컬러 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다. |
| [getInkOptions()](#getInkOptions--) | 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다. |
### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

생성된 TIFF 이미지의 크기를 지정합니다. 기본값은 0x0이며, 이는 생성된 이미지 크기가 프레젠테이션 슬라이드 크기 값을 기반으로 계산됨을 의미합니다. 읽기/쓰기 [Size](../../com.aspose.slides.android/size).

**반환:**  
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

생성된 TIFF 이미지의 크기를 지정합니다. 기본값은 0x0이며, 이는 생성된 이미지 크기가 프레젠테이션 슬라이드 크기 값을 기반으로 계산됨을 의미합니다. 읽기/쓰기 [Size](../../com.aspose.slides.android/size).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |
### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

인치당 도트 수인 가로 해상도를 지정합니다. 읽기/쓰기 long.

**반환:**  
long
### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

인치당 도트 수인 가로 해상도를 지정합니다. 읽기/쓰기 long.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |
### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

인치당 도트 수인 세로 해상도를 지정합니다. 읽기/쓰기 long.

**반환:**  
long
### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

인치당 도트 수인 세로 해상도를 지정합니다. 읽기/쓰기 long.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 false입니다.

**반환:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 false입니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

압축 유형을 지정합니다. 읽기/쓰기 [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**반환:**  
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

압축 유형을 지정합니다. 읽기/쓰기 [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

생성된 이미지의 픽셀 형식을 지정합니다. 읽기/쓰기 [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**반환:**  
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

생성된 이미지의 픽셀 형식을 지정합니다. 읽기/쓰기 [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
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


**반환:**  
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |
### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```

컬러 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다. 이 옵션은 CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int))이 [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) 또는 [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) 로 설정된 경우에만 적용됩니다. 읽기/쓰기 [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). 기본값은 [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default)입니다.

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


**반환:**  
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```

컬러 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다. 이 옵션은 CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int))이 [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) 또는 [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) 로 설정된 경우에만 적용됩니다. 읽기/쓰기 [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). 기본값은 [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default)입니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다. 읽기 전용 [IInkOptions](../../com.aspose.slides/iinkoptions)

**반환:**  
[IInkOptions](../../com.aspose.slides/iinkoptions)