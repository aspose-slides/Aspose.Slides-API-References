---
title: GifOptions
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет параметры экспорта GIF.
type: docs
url: /ru/com.aspose.slides/gifoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Все реализованные интерфейсы:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

Представляет параметры экспорта GIF.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // размер полученного GIF
>      gifOptions.setDefaultDelay(2000); // как долго будет отображаться каждый слайд, пока он не будет заменён следующим
>      gifOptions.setTransitionFps(35); // увеличить FPS для лучшего качества анимации переходов
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GifOptions()](#GifOptions--) | Инициализирует новый экземпляр класса GifOptions. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Получает или задает размер кадра. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Получает или задает размер кадра. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Определяет, будут ли экспортироваться скрытые слайды. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Определяет, будут ли экспортироваться скрытые слайды. |
| [getTransitionFps()](#getTransitionFps--) | Получает или задает FPS перехода [кадров/сек] Значение по умолчанию — 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Получает или задает FPS перехода [кадров/сек] Значение по умолчанию — 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Получает или задает время задержки по умолчанию [мс]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Получает или задает время задержки по умолчанию [мс]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

Инициализирует новый экземпляр класса GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```

Получает или задает размер кадра.

--------------------

Если размер пуст, то значение будет взято из [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Возвращаемое значение:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```

Получает или задает размер кадра.

--------------------

Если размер пуст, то значение будет взято из [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

Определяет, будут ли экспортироваться скрытые слайды. Значение по умолчанию — false.

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


**Возвращаемое значение:** boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

Определяет, будут ли экспортироваться скрытые слайды. Значение по умолчанию — false.

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```

Получает или задает FPS перехода [кадров/сек] Значение по умолчанию — 25.

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

**Возвращаемое значение:** int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```

Получает или задает FPS перехода [кадров/сек] Значение по умолчанию — 25.

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

Получает или задает время задержки по умолчанию [мс]. Это значение будет использоваться, если [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) не задано. Значение по умолчанию — 1000.

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

**Возвращаемое значение:** int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

Получает или задает время задержки по умолчанию [мс]. Это значение будет использоваться, если [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) не задано. Значение по умолчанию — 1000.

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |