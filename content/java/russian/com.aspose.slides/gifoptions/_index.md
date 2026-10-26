---
title: GifOptions
second_title: Aspose.Slides для Java справочник API
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
>      gifOptions.setFrameSize(new Dimension(960, 720)); // размер полученного GIF
>      gifOptions.setDefaultDelay(2000); // как долго каждый слайд будет отображаться, пока не будет переключён на следующий
>      gifOptions.setTransitionFps(35); // увеличить FPS для лучшего качества анимации перехода
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
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Получает или задает размер кадра. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Определяет, будут ли экспортированы скрытые слайды. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Определяет, будут ли экспортированы скрытые слайды. |
| [getTransitionFps()](#getTransitionFps--) | Получает или задает частоту кадров перехода [frames/sec]. Значение по умолчанию: 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Получает или задает частоту кадров перехода [frames/sec]. Значение по умолчанию: 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Получает или задает время задержки по умолчанию [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Получает или задает время задержки по умолчанию [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

Инициализирует новый экземпляр класса GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Dimension getFrameSize()
```

Получает или задает размер кадра.

--------------------

Если размер пуст, значение будет получено из [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Возвращаемое значение:**  
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public final void setFrameSize(Dimension value)
```

Получает или задает размер кадра.

--------------------

Если размер пуст, значение будет получено из [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

Определяет, будут ли экспортированы скрытые слайды. Значение по умолчанию: false.

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


**Возвращаемое значение:**  
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

Определяет, будут ли экспортированы скрытые слайды. Значение по умолчанию: false.

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

Получает или задает частоту кадров перехода [frames/sec]. Значение по умолчанию: 25.

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


**Возвращаемое значение:**  
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```

Получает или задает частоту кадров перехода [frames/sec]. Значение по умолчанию: 25.

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

Получает или задает время задержки по умолчанию [ms]. Это значение будет использовано, если [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) не задано. Значение по умолчанию: 1000.

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

**Возвращаемое значение:**  
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

Получает или задает время задержки по умолчанию [ms]. Это значение будет использовано, если [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) не задано. Значение по умолчанию: 1000.

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