---
title: HtmlOptions
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: HTML 내보내기 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/htmloptions/
---
**상속:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**모든 구현된 인터페이스:**  
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

HTML 내보내기 옵션을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | 콜백을 지정하는 새로운 HtmlOptions 개체를 생성합니다. |
| [HtmlOptions()](#HtmlOptions--) | 단일 HTML 파일로 저장하기 위한 새로운 HtmlOptions 개체를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [getHtmlFormatter()](#getHtmlFormatter--) | HTML 템플릿을 반환하거나 설정합니다. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | HTML 템플릿을 반환하거나 설정합니다. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 텍스트가 합자를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 텍스트가 합자를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getSlideImageFormat()](#getSlideImageFormat--) | 슬라이드 이미지 형식 옵션을 반환하거나 설정합니다. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | 슬라이드 이미지 형식 옵션을 반환하거나 설정합니다. |
| [getJpegQuality()](#getJpegQuality--) | PDF 문서 내 JPEG 이미지 품질을 결정하는 값을 반환하거나 설정합니다. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF 문서 내 JPEG 이미지 품질을 결정하는 값을 반환하거나 설정합니다. |
| [getPicturesCompression()](#getPicturesCompression--) | 그림 압축 수준을 나타냅니다 |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 그림 압축 수준을 나타냅니다 |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 잘린 부분이 문서의 일부로 남아 있는지 여부를 나타내는 부울 플래그입니다. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 잘린 부분이 문서의 일부로 남아 있는지 여부를 나타내는 부울 플래그입니다. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | svg 컨테이너에서 width 및 height 속성을 제외하려면 true - 레이아웃을 반응형으로 만듭니다. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | svg 컨테이너에서 width 및 height 속성을 제외하려면 true - 레이아웃을 반응형으로 만듭니다. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

콜백을 지정하는 새로운 HtmlOptions 개체를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | 프로젝트 저장을 제어하는 콜백 객체. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

단일 HTML 파일로 저장하기 위한 새로운 HtmlOptions 개체를 생성합니다.

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

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

HTML 템플릿을 반환하거나 설정합니다. 읽기/쓰기 [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**반환값:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

HTML 템플릿을 반환하거나 설정합니다. 읽기/쓰기 [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

텍스트가 합자를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져오거나 설정합니다. true 로 설정하면 렌더링 출력에서 합자가 비활성화됩니다. 기본적으로 이 속성은 false 로 설정됩니다.

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

**반환값:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

텍스트가 합자를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져오거나 설정합니다. true 로 설정하면 렌더링 출력에서 합자가 비활성화됩니다. 기본적으로 이 속성은 false 로 설정됩니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

슬라이드 이미지 형식 옵션을 반환하거나 설정합니다. 읽기/쓰기 [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**반환값:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

슬라이드 이미지 형식 옵션을 반환하거나 설정합니다. 읽기/쓰기 [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

PDF 문서 내 JPEG 이미지 품질을 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 byte.

--------------------

문서에 JPEG 이미지가 포함된 경우에만 영향을 미칩니다.

PDF 형식으로 저장할 때 문서 내부 이미지의 품질을 가져오거나 설정하려면 이 속성을 사용하십시오. 값은 0에서 100 사이이며, 0은 최악의 품질이지만 최대 압축을, 100은 최상의 품질이지만 최소 압축을 의미합니다.

기본값은 **95**입니다.

**반환값:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

PDF 문서 내 JPEG 이미지 품질을 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 byte.

--------------------

문서에 JPEG 이미지가 포함된 경우에만 영향을 미칩니다.

PDF 형식으로 저장할 때 문서 내부 이미지의 품질을 가져오거나 설정하려면 이 속성을 사용하십시오. 값은 0에서 100 사이이며, 0은 최악의 품질이지만 최대 압축을, 100은 최상의 품질이지만 최소 압축을 의미합니다.

기본값은 **95**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

그림 압축 수준을 나타냅니다

**반환값:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

그림 압축 수준을 나타냅니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

잘린 부분이 문서의 일부로 남아 있는지 여부를 나타내는 부울 플래그입니다. true이면 잘린 부분이 제거되고, false이면 문서에 직렬화되어 파일 크기가 커질 수 있습니다.

**반환값:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

잘린 부분이 문서의 일부로 남아 있는지 여부를 나타내는 부울 플래그입니다. true이면 잘린 부분이 제거되고, false이면 문서에 직렬화되어 파일 크기가 커질 수 있습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

svg 컨테이너에서 width 및 height 속성을 제외하려면 true - 레이아웃을 반응형으로 만듭니다. 그렇지 않으면 false. 읽기/쓰기 boolean.

**반환값:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

svg 컨테이너에서 width 및 height 속성을 제외하려면 true - 레이아웃을 반응형으로 만듭니다. 그렇지 않으면 false. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |