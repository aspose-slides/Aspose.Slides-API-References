---
title: ILayoutSlide
second_title: Справочник API Aspose.Slides для Java
description: Представляет слайд макета.
type: docs
url: /ru/com.aspose.slides/ilayoutslide/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Представляет слайд макета.
## Методы

| Метод | Описание |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter слайда макета. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Возвращает менеджер заполнителей слайда макета. |
| [getMasterSlide()](#getMasterSlide--) | Возвращает или задает главный слайд для макета. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Возвращает или задает главный слайд для макета. |
| [getLayoutType()](#getLayoutType--) | Возвращает тип макета данного слайда макета. |
| [hasDependingSlides()](#hasDependingSlides--) | Возвращает true, если существует хотя бы один слайд, зависящий от этого слайда макета. |
| [getDependingSlides()](#getDependingSlides--) | Возвращает массив всех слайдов, зависящих от этого слайда макета. |
| [remove()](#remove--) | Удаляет макет из презентации. |
| [getDrawingGuides()](#getDrawingGuides--) | Возвращает коллекцию направляющих черчения для слайда макета. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Возвращает менеджер HeaderFooter слайда макета. Только для чтения [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Возвращаемое значение:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

Возвращает менеджер заполнителей слайда макета. Только для чтения [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Возвращаемое значение:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

Возвращает или задает главный слайд для макета. Чтение/запись [IMasterSlide](../../com.aspose.slides/imasterslide).

**Возвращаемое значение:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

Возвращает или задает главный слайд для макета. Чтение/запись [IMasterSlide](../../com.aspose.slides/imasterslide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

Возвращает тип макета данного слайда макета. Только для чтения [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Возвращаемое значение:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Возвращает true, если существует хотя бы один слайд, зависящий от этого слайда макета. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Возвращает массив всех слайдов, зависящих от этого слайда макета.

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Массив всех слайдов, зависящих от этого слайда макета
### remove() {#remove--}
```
public abstract void remove()
```

Удаляет макет из презентации.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Возвращает коллекцию направляющих черчения для слайда макета. Только для чтения [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Добавление нового вертикального направляющего черчения слева от центра слайда
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)