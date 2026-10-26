---
title: IGifOptions
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет параметры экспорта GIF.
type: docs
url: /ru/com.aspose.slides/igifoptions/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Представляет параметры экспорта GIF.
## Методы

| Метод | Описание |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Получает или задает размер кадра. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Получает или задает размер кадра. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Определяет, будут ли экспортированы скрытые слайды. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Определяет, будут ли экспортированы скрытые слайды. |
| [getTransitionFps()](#getTransitionFps--) | Получает или задает FPS перехода [frames/sec]. Значение по умолчанию — 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Получает или задает FPS перехода [frames/sec]. Значение по умолчанию — 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Получает или задает время задержки по умолчанию [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Получает или задает время задержки по умолчанию [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```


Получает или задает размер кадра.

--------------------

Если размер пуст, значение будет получено из [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Возврат:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```


Получает или задает размер кадра.

--------------------

Если размер пуст, значение будет получено из [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


Определяет, будут ли экспортированы скрытые слайды. Значение по умолчанию — false.

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


**Возврат:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```


Определяет, будут ли экспортированы скрытые слайды. Значение по умолчанию — false.

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


**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```


Получает или задает FPS перехода [frames/sec]. Значение по умолчанию — 25.

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

**Возврат:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```


Получает или задает FPS перехода [frames/sec]. Значение по умолчанию — 25.

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

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```


Получает или задает время задержки по умолчанию [ms]. Это значение будет использовано, если [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) не задано. Значение по умолчанию — 1000.

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

**Возврат:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public abstract void setDefaultDelay(int value)
```


Получает или задает время задержки по умолчанию [ms]. Это значение будет использовано, если [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) не задано. Значение по умолчанию — 1000.

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

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |