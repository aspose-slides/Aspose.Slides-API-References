---
title: IMasterSlide
second_title: Справочник API Aspose.Slides для Java
description: Представляет главный слайд в презентации.
type: docs
url: /ru/com.aspose.slides/imasterslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Представляет главный слайд в презентации.
## Methods

| Метод | Описание |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter главного слайда. |
| [getTitleStyle()](#getTitleStyle--) | Возвращает стиль текста заголовка. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Создаёт новый главный слайд на основе текущего, применяя к нему внешний шаблон, и применяет созданный главный слайд ко всем зависимым слайдам. |
| [getBodyStyle()](#getBodyStyle--) | Возвращает стиль основного текста. |
| [getOtherStyle()](#getOtherStyle--) | Возвращает стиль другого текста. |
| [getLayoutSlides()](#getLayoutSlides--) | Возвращает коллекцию дочерних слайдов-макетов для этого главного слайда. |
| [getPreserve()](#getPreserve--) | Определяет, будет ли соответствующий главный слайд удалён, когда удалены все слайды, следующие за этим главным слайдом. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Определяет, будет ли соответствующий главный слайд удалён, когда удалены все слайды, следующие за этим главным слайдом. |
| [hasDependingSlides()](#hasDependingSlides--) | Возвращает true, если существует хотя бы один слайд, зависящий от этого главного слайда. |
| [getDependingSlides()](#getDependingSlides--) | Возвращает массив со всеми слайдами, зависящими от этого главного слайда. |
| [getDrawingGuides()](#getDrawingGuides--) | Возвращает коллекцию направляющих рисунка для главного слайда. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```


Возвращает менеджер HeaderFooter главного слайда. Только для чтения [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Returns:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```


Возвращает стиль текста заголовка. Только для чтения [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```


Создаёт новый главный слайд на основе текущего, применяя к нему внешний шаблон, и применяет созданный главный слайд ко всем зависимым слайдам.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | java.lang.String | Путь к файлу внешнего шаблона (.thmx). |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - New themed MasterSlide.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```


Возвращает стиль основного текста. Только для чтения [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```


Возвращает стиль другого текста. Только для чтения [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```


Возвращает коллекцию дочерних слайдов-макетов для этого главного слайда. Только для чтения [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Вы можете получить доступ к альтернативному API для добавления/вставки/удаления/клонирования слайдов-макетов, используя свойство ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Returns:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```


Определяет, будет ли соответствующий главный слайд удалён, когда удалены все слайды, следующие за этим главным слайдом. Примечание: Aspose.Slides никогда сам не удалит неиспользуемый главный слайд; чтобы действительно удалить неиспользуемые главные слайды, вызовите [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Чтение/запись boolean.

**Returns:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```


Определяет, будет ли соответствующий главный слайд удалён, когда удалены все слайды, следующие за этим главным слайдом. Примечание: Aspose.Slides никогда сам не удалит неиспользуемый главный слайд; чтобы действительно удалить неиспользуемые главные слайды, вызовите [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Чтение/запись boolean.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Возвращает true, если существует хотя бы один слайд, зависящий от этого главного слайда. Только для чтения boolean.

**Returns:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Возвращает массив со всеми слайдами, зависящими от этого главного слайда.

**Returns:**
com.aspose.slides.ISlide[] - Массив [ISlide](../../com.aspose.slides/islide), который зависит от этого главного слайда
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Возвращает коллекцию направляющих рисунка для главного слайда. Только для чтения [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Добавление новой вертикальной направляющей справа от центра слайда
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)