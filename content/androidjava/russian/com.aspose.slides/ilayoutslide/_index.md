---
title: ILayoutSlide
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет макетный слайд.
type: docs
url: /ru/com.aspose.slides/ilayoutslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Представляет макетный слайд.
## Методы

| Метод | Описание |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter макетного слайда. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Возвращает менеджер placeholder макетного слайда. |
| [getMasterSlide()](#getMasterSlide--) | Возвращает или задает master slide для макета. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Возвращает или задает master slide для макета. |
| [getLayoutType()](#getLayoutType--) | Возвращает тип макета этого макетного слайда. |
| [hasDependingSlides()](#hasDependingSlides--) | Возвращает true, если существует хотя бы один слайд, зависящий от этого макетного слайда. |
| [getDependingSlides()](#getDependingSlides--) | Возвращает массив со всеми слайдами, зависящими от этого макетного слайда. |
| [remove()](#remove--) | Удаляет макет из презентации. |
| [getDrawingGuides()](#getDrawingGuides--) | Возвращает коллекцию руководств по рисованию для макетного слайда. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Возвращает менеджер HeaderFooter макетного слайда. Только для чтения [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Возвращаемое значение:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```


Возвращает менеджер placeholder макетного слайда. Только для чтения [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Возвращаемое значение:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```


Возвращает или задает master slide для макета. Чтение/запись [IMasterSlide](../../com.aspose.slides/imasterslide).

**Возвращаемое значение:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```


Возвращает или задает master slide для макета. Чтение/запись [IMasterSlide](../../com.aspose.slides/imasterslide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```


Возвращает тип макета этого макетного слайда. Только для чтения [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Возвращаемое значение:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Возвращает true, если существует хотя бы один слайд, зависящий от этого макетного слайда. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Возвращает массив со всеми слайдами, зависящими от этого макетного слайда.

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - массив со всеми слайдами, зависящими от этого макетного слайда
### remove() {#remove--}
```
public abstract void remove()
```


Удаляет макет из презентации.
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Возвращает коллекцию руководств по рисованию для макетного слайда. Только для чтения [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Добавление новой вертикальной направляющей слева от центра слайда
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)