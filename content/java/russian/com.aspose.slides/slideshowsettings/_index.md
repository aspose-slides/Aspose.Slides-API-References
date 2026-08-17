---
title: SlideShowSettings
second_title: Справочник API Aspose.Slides для Java
description: Представляет настройки показа слайдов для презентации.
type: docs
url: /ru/com.aspose.slides/slideshowsettings/
---
**Наследование:**
java.lang.Object
```
public class SlideShowSettings
```

Представляет настройки показа слайдов для презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Получает или задает тип показа слайдов. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Получает или задает тип показа слайдов. |
| [getLoop()](#getLoop--) | Циклический показ слайдов |
| [setLoop(boolean value)](#setLoop-boolean-) | Циклический показ слайдов |
| [getShowNarration()](#getShowNarration--) | Показывать озвучивание в показе слайдов |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Показывать озвучивание в показе слайдов |
| [getShowAnimation()](#getShowAnimation--) | Показывать анимацию в показе слайдов |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Показывать анимацию в показе слайдов |
| [getPenColor()](#getPenColor--) | Цвет пера для показа слайдов |
| [getSlides()](#getSlides--) | Диапазон слайдов |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Диапазон слайдов |
| [getUseTimings()](#getUseTimings--) | Использовать тайминги в показе слайдов |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Использовать тайминги в показе слайдов |
| [getShowMediaControls()](#getShowMediaControls--) | Показывать элементы управления медиа |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Показывать элементы управления медиа |

### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

Получает или задает тип показа слайдов. Представлен следующим SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) предки: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) и [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // установить тип "Browsed at a kiosk (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // установить тип "Browsed by individual (window)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // установить тип "Presented by a speaker (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращает:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

Получает или задает тип показа слайдов. Представлен следующим SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) предки: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) и [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // установить тип "Browsed at a kiosk (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // установить тип "Browsed by individual (window)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // установить тип "Presented by a speaker (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

Циклический показ слайдов

**Возвращает:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

Циклический показ слайдов

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

Показывать озвучивание в показе слайдов

**Возвращает:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

Показывать озвучивание в показе слайдов

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

Показывать анимацию в показе слайдов

**Возвращает:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

Показывать анимацию в показе слайдов

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

Цвет пера для показа слайдов

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

Диапазон слайдов

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SlidesRange slidesRange = new SlidesRange();
>      slidesRange.setStart(1);
>      slidesRange.setEnd(3);
>      pres.getSlideShowSettings().setSlides(slidesRange);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращает:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

Диапазон слайдов

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SlidesRange slidesRange = new SlidesRange();
>      slidesRange.setStart(1);
>      slidesRange.setEnd(3);
>      pres.getSlideShowSettings().setSlides(slidesRange);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

Использовать тайминги в показе слайдов

**Возвращает:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

Использовать тайминги в показе слайдов

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

Показывать элементы управления медиа

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

Показывать элементы управления медиа

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |