---
title: SlideShowSettings
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет настройки слайдшоу для презентации.
type: docs
url: /ru/com.aspose.slides/slideshowsettings/
---
**Наследование:**
java.lang.Object
```
public class SlideShowSettings
```

Представляет параметры слайдшоу для презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Получает или задает тип слайдшоу. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Получает или задает тип слайдшоу. |
| [getLoop()](#getLoop--) | Повтор слайдшоу |
| [setLoop(boolean value)](#setLoop-boolean-) | Повтор слайдшоу |
| [getShowNarration()](#getShowNarration--) | Показывать озвучку в слайдшоу |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Показывать озвучку в слайдшоу |
| [getShowAnimation()](#getShowAnimation--) | Показывать анимацию в слайдшоу |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Показывать анимацию в слайдшоу |
| [getPenColor()](#getPenColor--) | Цвет пера для слайдшоу |
| [getSlides()](#getSlides--) | Диапазон слайдов |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Диапазон слайдов |
| [getUseTimings()](#getUseTimings--) | Использовать тайминги в слайдшоу |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Использовать тайминги в слайдшоу |
| [getShowMediaControls()](#getShowMediaControls--) | Показывать элементы управления медиа |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Показывать элементы управления медиа |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

Получает или задает тип слайдшоу. Представлено следующим  SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancestors: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) and [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

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

**Возвращаемое значение:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

Получает или задает тип слайдшоу. Представлено следующим  SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancestors: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) and [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

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

Повтор слайдшоу

**Возвращаемое значение:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

Повтор слайдшоу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

Показывать озвучку в слайдшоу

**Возвращаемое значение:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
``` 
public final void setShowNarration(boolean value)
```

Показывать озвучку в слайдшоу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

Показывать анимацию в слайдшоу

**Возвращаемое значение:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

Показывать анимацию в слайдшоу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

Цвет пера для слайдшоу

**Возвращаемое значение:**
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


**Возвращаемое значение:**
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

Использовать тайминги в слайдшоу

**Возвращаемое значение:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

Использовать тайминги в слайдшоу

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

**Возвращаемое значение:**
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