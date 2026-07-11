---
title: LayoutSlide
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет макетный слайд.
type: docs
url: /ru/com.aspose.slides/layoutslide/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Все реализованные интерфейсы:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Представляет макетный слайд.
## Методы

| Метод | Описание |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter макетного слайда. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Возвращает менеджер заполнителей макетного слайда. |
| [getMasterSlide()](#getMasterSlide--) | Возвращает или задает главный слайд для макета. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Возвращает или задает главный слайд для макета. |
| [remove()](#remove--) | Удаляет макет из презентации. |
| [getThemeManager()](#getThemeManager--) | Возвращает переопределяющий менеджер тем. |
| [getLayoutType()](#getLayoutType--) | Возвращает тип макета этого макетного слайда. |
| [getDependingSlides()](#getDependingSlides--) | Возвращает массив со всеми слайдами, которые зависят от этого макетного слайда. |
| [hasDependingSlides()](#hasDependingSlides--) | Возвращает true, если существует хотя бы один слайд, зависящий от этого макетного слайда. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет. |
| [getDrawingGuides()](#getDrawingGuides--) | Возвращает коллекцию направляющих рисования для макетного слайда. |
### getHeaderFooterManager() {#getHeaderFooterManager--}}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Возвращает менеджер HeaderFooter макетного слайда. Только для чтения [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Возвращает:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

Возвращает менеджер заполнителей макетного слайда. Только для чтения [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Возвращает:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}}
```
public final IMasterSlide getMasterSlide()
```

Возвращает или задает главный слайд для макета. Чтение/запись [IMasterSlide](../../com.aspose.slides/imasterslide).

**Возвращает:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

Возвращает или задает главный слайд для макета. Чтение/запись [IMasterSlide](../../com.aspose.slides/imasterslide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### remove() {#remove--}}
```
public final void remove()
```

Удаляет макет из презентации.
### getThemeManager() {#getThemeManager--}}
```
public final IOverrideThemeManager getThemeManager()
```

Возвращает переопределяющий менеджер тем. Только для чтения [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Возвращает:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}}
```
public final byte getLayoutType()
```

Возвращает тип макета этого макетного слайда. Только для чтения [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Возвращает:**
byte
### getDependingSlides() {#getDependingSlides--}}
```
public final ISlide[] getDependingSlides()
```

Возвращает массив со всеми слайдами, которые зависят от этого макетного слайда.

**Возвращает:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}}
```
public final boolean hasDependingSlides()
```

Возвращает true, если существует хотя бы один слайд, зависящий от этого макетного слайда. Только для чтения  boolean .

**Возвращает:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}}
```
public boolean getShowMasterShapes()
```

Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет. Чтение/запись  boolean .

**Возвращает:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет. Чтение/запись  boolean .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Возвращает коллекцию направляющих рисования для макетного слайда. Только для чтения [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Добавление новой вертикальной направляющей рисования слева от центра слайда
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)