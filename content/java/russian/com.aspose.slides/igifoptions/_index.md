---
title: IGifOptions
second_title: Справочник API Aspose.Slides для Java
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
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Получает или задает размер кадра. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Определяет, будут ли скрытые слайды экспортированы. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Определяет, будут ли скрытые слайды экспортированы. |
| [getTransitionFps()](#getTransitionFps--) | Получает или задает FPS перехода [frames/sec]. Значение по умолчанию — 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Получает или задает FPS перехода [frames/sec]. Значение по умолчанию — 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Получает или задает время задержки по умолчанию [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Получает или задает время задержки по умолчанию [ms]. |

### getFrameSize() {#getFrameSize--}
```
public abstract Dimension getFrameSize()
```

Получает или задает размер кадра.

--------------------

Если размер пуст, то значение будет взято из [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Возвращает:**
java.awt.Dimension

### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public abstract void setFrameSize(Dimension value)
```

Получает или задает размер кадра.

--------------------

Если размер пуст, то значение будет взято из [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```

Определяет, будут ли скрытые слайды экспортированы. Значение по умолчанию — false.

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

**Возвращает:**
boolean

### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```

Определяет, будут ли скрытые слайды экспортированы. Значение по умолчанию — false.

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

**Возвращает:**
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```

Получает или задает время задержки по умолчанию [ms]. Это значение будет использовано, если [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) не установлен. Значение по умолчанию — 1000.

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

**Возвращает:**
int

### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public abstract void setDefaultDelay(int value)
```

Получает или задает время задержки по умолчанию [ms]. Это значение будет использовано, если [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) не установлен. Значение по умолчанию — 1000.

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