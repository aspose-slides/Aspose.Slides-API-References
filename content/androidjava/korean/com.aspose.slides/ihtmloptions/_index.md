---
title: IHtmlOptions
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: HTML 내보내기 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ihtmloptions/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

HTML 내보내기 옵션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | HTML 템플릿을 반환하거나 설정합니다. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | HTML 템플릿을 반환하거나 설정합니다. |
| [getSlideImageFormat()](#getSlideImageFormat--) | 슬라이드 이미지 형식 옵션을 반환하거나 설정합니다. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | 슬라이드 이미지 형식 옵션을 반환하거나 설정합니다. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [getJpegQuality()](#getJpegQuality--) | PDF 문서 내 JPEG 이미지 품질을 결정하는 값을 반환하거나 설정합니다. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF 문서 내 JPEG 이미지 품질을 결정하는 값을 반환하거나 설정합니다. |
| [getPicturesCompression()](#getPicturesCompression--) | 그림 압축 수준을 나타냅니다. 읽기/쓰기 [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 그림 압축 수준을 나타냅니다. 읽기/쓰기 [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 잘린 부분이 문서에 남아 있는지를 나타내는 부울 플래그입니다. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 잘린 부분이 문서에 남아 있는지를 나타내는 부울 플래그입니다. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | SVG 컨테이너에서 width 및 height 속성을 제외하려면 true로 설정합니다. 이렇게 하면 레이아웃이 반응형이 됩니다. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | SVG 컨테이너에서 width 및 height 속성을 제외하려면 true로 설정합니다. 이렇게 하면 레이아웃이 반응형이 됩니다. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 텍스트가 합자를 사용하지 않고 렌더링되는지를 나타내는 값을 가져오거나 설정합니다. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 텍스트가 합자를 사용하지 않고 렌더링되는지를 나타내는 값을 가져오거나 설정합니다. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

HTML 템플릿을 반환하거나 설정합니다. 읽기/쓰기 [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**반환:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

HTML 템플릿을 반환하거나 설정합니다. 읽기/쓰기 [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

슬라이드 이미지 형식 옵션을 반환하거나 설정합니다. 읽기/쓰기 [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**반환:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

슬라이드 이미지 형식 옵션을 반환하거나 설정합니다. 읽기/쓰기 [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

PDF 문서 내 JPEG 이미지 품질을 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 byte.

--------------------

문서에 JPEG 이미지가 포함된 경우에만 적용됩니다.

이 속성을 사용하여 PDF 형식으로 저장할 때 문서 내부 이미지의 품질을 가져오거나 설정합니다. 값은 0에서 100까지이며, 0은 최저 품질이지만 최대 압축을 의미하고, 100은 최고 품질이지만 최소 압축을 의미합니다.

기본값은 **95**입니다.

**반환:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

PDF 문서 내 JPEG 이미지 품질을 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 byte.

--------------------

문서에 JPEG 이미지가 포함된 경우에만 적용됩니다.

이 속성을 사용하여 PDF 형식으로 저장할 때 문서 내부 이미지의 품질을 가져오거나 설정합니다. 값은 0에서 100까지이며, 0은 최저 품질이지만 최대 압축을 의미하고, 100은 최고 품질이지만 최소 압축을 의미합니다.

기본값은 **95**입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

그림 압축 수준을 나타냅니다. 읽기/쓰기 [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**반환:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

그림 압축 수준을 나타냅니다. 읽기/쓰기 [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

잘린 부분이 문서에 남아 있는지를 나타내는 부울 플래그입니다. true이면 잘린 부분이 제거되고, false이면 문서에 직렬화됩니다(파일이 커질 수 있음). 읽기/쓰기 boolean.

**반환:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

잘린 부분이 문서에 남아 있는지를 나타내는 부울 플래그입니다. true이면 잘린 부분이 제거되고, false이면 문서에 직렬화됩니다(파일이 커질 수 있음). 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

SVG 컨테이너에서 width 및 height 속성을 제외하려면 true로 설정합니다. 이렇게 하면 레이아웃이 반응형이 됩니다. false이면 제외하지 않습니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

SVG 컨테이너에서 width 및 height 속성을 제외하려면 true로 설정합니다. 이렇게 하면 레이아웃이 반응형이 됩니다. false이면 제외하지 않습니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

텍스트가 합자를 사용하지 않고 렌더링되는지를 나타내는 값을 가져오거나 설정합니다. true로 설정하면 렌더링 출력에서 합자가 비활성화됩니다. 기본값은 false입니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

텍스트가 합자를 사용하지 않고 렌더링되는지를 나타내는 값을 가져오거나 설정합니다. true로 설정하면 렌더링 출력에서 합자가 비활성화됩니다. 기본값은 false입니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

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
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
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
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다. 읽기 전용 [IInkOptions](../../com.aspose.slides/iinkoptions)

**반환:**
[IInkOptions](../../com.aspose.slides/iinkoptions)