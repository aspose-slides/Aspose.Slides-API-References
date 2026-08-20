---
title: Html5Options
second_title: Aspose.Slides for Java API 레퍼런스
description: HTML5 내보내기 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/html5options/
---
**상속:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**구현된 모든 인터페이스:**
[com.aspose.slides.IHtml5Options](../../com.aspose.slides/ihtml5options)
```
public class Html5Options extends SaveOptions implements IHtml5Options
```

HTML5 내보내기 옵션을 나타냅니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Html5Options()](#Html5Options--) | 기본 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | 전환 애니메이션 옵션을 가져오거나 설정합니다. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | 전환 애니메이션 옵션을 가져오거나 설정합니다. |
| [getAnimateShapes()](#getAnimateShapes--) | 도형 애니메이션 옵션을 가져오거나 설정합니다. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | 도형 애니메이션 옵션을 가져오거나 설정합니다. |
| [getEmbedImages()](#getEmbedImages--) | 이미지 임베드 옵션을 가져오거나 설정합니다. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | 이미지 임베드 옵션을 가져오거나 설정합니다. |
| [getOutputPath()](#getOutputPath--) | 외부 리소스가 저장될 위치를 결정합니다. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | 외부 리소스가 저장될 위치를 결정합니다. |
| [getPicturesCompression()](#getPicturesCompression--) | 사진 압축 수준을 나타냅니다 |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 사진 압축 수준을 나타냅니다 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 텍스트가 합자를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 텍스트가 합자를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### Html5Options() {#Html5Options--}
```
public Html5Options()
```

기본 생성자.

### getAnimateTransitions() {#getAnimateTransitions--}
```
public final boolean getAnimateTransitions()
```

전환 애니메이션 옵션을 가져오거나 설정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public final void setAnimateTransitions(boolean value)
```

전환 애니메이션 옵션을 가져오거나 설정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public final boolean getAnimateShapes()
```

도형 애니메이션 옵션을 가져오거나 설정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public final void setAnimateShapes(boolean value)
```

도형 애니메이션 옵션을 가져오거나 설정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public final boolean getEmbedImages()
```

이미지 임베드 옵션을 가져오거나 설정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public final void setEmbedImages(boolean value)
```

이미지 임베드 옵션을 가져오거나 설정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public final String getOutputPath()
```

외부 리소스가 저장될 위치를 결정합니다. 읽기/쓰기 String.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public final void setOutputPath(String value)
```

외부 리소스가 저장될 위치를 결정합니다. 읽기/쓰기 String.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

사진 압축 수준을 나타냅니다

**반환:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

사진 압축 수준을 나타냅니다

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

텍스트가 합자를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져오거나 설정합니다. true로 설정하면 렌더링된 출력에서 합자가 비활성화됩니다. 기본값은 false입니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // 텍스트 렌더링에서 합자를 비활성화합니다
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

텍스트가 합자를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져오거나 설정합니다. true로 설정하면 렌더링된 출력에서 합자가 비활성화됩니다. 기본값은 false입니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // 텍스트 렌더링에서 합자를 비활성화합니다
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | boolean |  |

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
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**
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
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |