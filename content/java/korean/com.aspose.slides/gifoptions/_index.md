---
title: GifOptions
second_title: Aspose.Slides for Java API 레퍼런스
description: GIF 내보내기 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/gifoptions/
---
**상속:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

GIF 내보내기 옵션을 나타냅니다.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new Dimension(960, 720)); // 생성된 GIF의 크기
>      gifOptions.setDefaultDelay(2000); // 각 슬라이드가 다음 슬라이드로 전환될 때까지 표시되는 시간
>      gifOptions.setTransitionFps(35); // 전환 애니메이션 품질을 높이기 위해 FPS를 증가시킵니다
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 생성자

| Constructor | Description |
| --- | --- |
| [GifOptions()](#GifOptions--) | GifOptions 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| Method | Description |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | 프레임 크기를 가져오거나 설정합니다. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | 프레임 크기를 가져오거나 설정합니다. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 숨겨진 슬라이드를 내보낼지 여부를 결정합니다. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 숨겨진 슬라이드를 내보낼지 여부를 결정합니다. |
| [getTransitionFps()](#getTransitionFps--) | 전환 FPS [frames/sec]를 가져오거나 설정합니다. 기본값은 25입니다. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | 전환 FPS [frames/sec]를 가져오거나 설정합니다. 기본값은 25입니다. |
| [getDefaultDelay()](#getDefaultDelay--) | 기본 지연 시간 [ms]을 가져오거나 설정합니다. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | 기본 지연 시간 [ms]을 가져오거나 설정합니다. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

GifOptions 클래스의 새 인스턴스를 초기화합니다.

### getFrameSize() {#getFrameSize--}
```
public final Dimension getFrameSize()
```

프레임 크기를 가져오거나 설정합니다.

--------------------

크기가 비어 있으면 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)에서 값을 가져옵니다.

**반환값:**  
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public final void setFrameSize(Dimension value)
```

프레임 크기를 가져오거나 설정합니다.

--------------------

크기가 비어 있으면 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)에서 값을 가져옵니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

숨겨진 슬라이드를 내보낼지 여부를 결정합니다. 기본값은 false입니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환값:**  
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

숨겨진 슬라이드를 내보낼지 여부를 결정합니다. 기본값은 false입니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```

전환 FPS [frames/sec]를 가져오거나 설정합니다. 기본값은 25입니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**  
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```

전환 FPS [frames/sec]를 가져오거나 설정합니다. 기본값은 25입니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

기본 지연 시간 [ms]을 가져오거나 설정합니다. [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-)가 설정되지 않은 경우 이 값이 사용됩니다. 기본값은 1000입니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**  
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

기본 지연 시간 [ms]을 가져오거나 설정합니다. [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-)가 설정되지 않은 경우 이 값이 사용됩니다. 기본값은 1000입니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |