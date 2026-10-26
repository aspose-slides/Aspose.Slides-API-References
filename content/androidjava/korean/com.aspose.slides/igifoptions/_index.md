---
title: IGifOptions
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: GIF 내보내기 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/igifoptions/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

GIF 내보내기 옵션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | 프레임 크기를 가져오거나 설정합니다. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | 프레임 크기를 가져오거나 설정합니다. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 숨겨진 슬라이드가 내보내질지 여부를 결정합니다. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 숨겨진 슬라이드가 내보내질지 여부를 결정합니다. |
| [getTransitionFps()](#getTransitionFps--) | 전환 FPS[frames/sec]를 가져오거나 설정합니다. 기본값은 25입니다. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | 전환 FPS[frames/sec]를 가져오거나 설정합니다. 기본값은 25입니다. |
| [getDefaultDelay()](#getDefaultDelay--) | 기본 지연 시간[ms]을 가져오거나 설정합니다. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | 기본 지연 시간[ms]을 가져오거나 설정합니다. |
### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```

프레임 크기를 가져오거나 설정합니다.

--------------------

크기가 비어 있으면 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)에서 값이 가져와집니다.

**반환:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```

프레임 크기를 가져오거나 설정합니다.

--------------------

크기가 비어 있으면 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)에서 값이 가져와집니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
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
public abstract void setExportHiddenSlides(boolean value)
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```

전환 FPS[frames/sec]를 가져오거나 설정합니다. 기본값은 25입니다.

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
public abstract void setTransitionFps(int value)
```

전환 FPS[frames/sec]를 가져오거나 설정합니다. 기본값은 25입니다.

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |
### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```

기본 지연 시간[ms]을 가져오거나 설정합니다. 이 값은 [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-)가 설정되지 않은 경우 사용됩니다. 기본값은 1000입니다.

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
public abstract void setDefaultDelay(int value)
```

기본 지연 시간[ms]을 가져오거나 설정합니다. 이 값은 [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-)가 설정되지 않은 경우 사용됩니다. 기본값은 1000입니다.

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |