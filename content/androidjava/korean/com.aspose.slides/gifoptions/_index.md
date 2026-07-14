---
title: GifOptions
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: GIF 내보내기 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/gifoptions/
---
**상속:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**모든 구현된 인터페이스:**  
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
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // 결과 GIF의 크기
>      gifOptions.setDefaultDelay(2000); // 각 슬라이드가 다음 슬라이드로 전환될 때까지 표시되는 시간
>      gifOptions.setTransitionFps(35); // 전환 애니메이션 품질 향상을 위해 FPS 증가
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GifOptions()](#GifOptions--) | GifOptions 클래스의 새로운 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | 프레임 크기를 가져오거나 설정합니다. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | 프레임 크기를 가져오거나 설정합니다. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 숨겨진 슬라이드가 내보내질지 여부를 결정합니다. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 숨겨진 슬라이드가 내보내질지 여부를 결정합니다. |
| [getTransitionFps()](#getTransitionFps--) | 전환 FPS[프레임/초]를 가져오거나 설정합니다. 기본값은 25입니다. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | 전환 FPS[프레임/초]를 가져오거나 설정합니다. 기본값은 25입니다. |
| [getDefaultDelay()](#getDefaultDelay--) | 기본 지연 시간[ms]을 가져오거나 설정합니다. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | 기본 지연 시간[ms]을 가져오거나 설정합니다. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

GifOptions 클래스의 새로운 인스턴스를 초기화합니다.

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```

프레임 크기를 가져오거나 설정합니다.

--------------------

크기가 비어 있으면 값은 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)에서 가져옵니다.

**반환:**  
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```

프레임 크기를 가져오거나 설정합니다.

--------------------

크기가 비어 있으면 값은 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)에서 가져옵니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

숨겨진 슬라이드가 내보내질지 여부를 결정합니다. 기본값은 false입니다.

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


**반환:**  
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

숨겨진 슬라이드가 내보내질지 여부를 결정합니다. 기본값은 false입니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```

전환 FPS[프레임/초]를 가져오거나 설정합니다. 기본값은 25입니다.

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


**반환:**  
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```

전환 FPS[프레임/초]를 가져오거나 설정합니다. 기본값은 25입니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

기본 지연 시간[ms]을 가져오거나 설정합니다. [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-)가 설정되지 않은 경우 이 값을 사용합니다. 기본값은 1000입니다.

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

**반환:**  
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

기본 지연 시간[ms]을 가져오거나 설정합니다. [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-)가 설정되지 않은 경우 이 값을 사용합니다. 기본값은 1000입니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |