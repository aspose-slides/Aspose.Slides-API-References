---
title: MasterSlide
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет главный слайд в презентации.
type: docs
url: /ru/com.aspose.slides/masterslide/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Представляет главный слайд в презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter главного слайда. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Создаёт новый главный слайд на основе текущего, применяя к нему внешнюю тему, и применяет созданный главный слайд ко всем зависимым слайдам. |
| [getTitleStyle()](#getTitleStyle--) | Возвращает стиль текста заголовка. |
| [getBodyStyle()](#getBodyStyle--) | Возвращает стиль основного текста. |
| [getOtherStyle()](#getOtherStyle--) | Возвращает стиль другого текста. |
| [getLayoutSlides()](#getLayoutSlides--) | Возвращает коллекцию дочерних макетных слайдов для этого главного слайда. |
| [getPreserve()](#getPreserve--) | Определяет, будет ли соответствующий главный слайд удалён, когда все слайды, следующие за этим главным, будут удалены. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Определяет, будет ли соответствующий главный слайд удалён, когда все слайды, следующие за этим главным, будут удалены. |
| [getDependingSlides()](#getDependingSlides--) | Возвращает массив всех слайдов, зависящих от этого главного слайда. |
| [hasDependingSlides()](#hasDependingSlides--) | Возвращает true, если существует хотя бы один слайд, зависящий от этого главного слайда. |
| [getThemeManager()](#getThemeManager--) | Возвращает менеджер темы. |
| [getName()](#getName--) | Возвращает или задаёт имя главного слайда. |
| [setName(String value)](#setName-java.lang.String-) | Возвращает или задаёт имя главного слайда. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет. |
| [getDrawingGuides()](#getDrawingGuides--) | Возвращает коллекцию направляющих для главного слайда. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Возвращает менеджер HeaderFooter главного слайда. Только для чтения [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Возвращаемое значение:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Создаёт новый главный слайд на основе текущего, применяя к нему внешнюю тему, и применяет созданный главный слайд ко всем зависимым слайдам.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | java.lang.String | Путь к файлу внешней темы (.thmx). |

**Возвращаемое значение:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Новый тематический MasterSlide.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Возвращает стиль текста заголовка. Только для чтения [ITextStyle](../../com.aspose.slides/itextstyle).

**Возвращаемое значение:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Возвращает стиль основного текста. Только для чтения [ITextStyle](../../com.aspose.slides/itextstyle).

**Возвращаемое значение:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Возвращает стиль другого текста. Только для чтения [ITextStyle](../../com.aspose.slides/itextstyle).

**Возвращаемое значение:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Возвращает коллекцию дочерних макетных слайдов для этого главного слайда. Только для чтения [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Вы можете получить доступ к альтернативному API для добавления/вставки/удаления/клонирования макетных слайдов, используя свойство ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Возвращаемое значение:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Определяет, будет ли соответствующий главный слайд удалён, когда все слайды, следующие за этим главным, будут удалены. Примечание: Aspose.Slides никогда не удалит неиспользуемый главный слайд самостоятельно, чтобы фактически удалить неиспользуемые главные слайды, вызовите [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Чтение/запись  boolean .

**Возвращаемое значение:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Определяет, будет ли соответствующий главный слайд удалён, когда все слайды, следующие за этим главным, будут удалены. Примечание: Aspose.Slides никогда не удалит неиспользуемый главный слайд самостоятельно, чтобы фактически удалить неиспользуемые главные слайды, вызовите [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Чтение/запись  boolean .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Возвращает массив всех слайдов, зависящих от этого главного слайда.

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Возвращает true, если существует хотя бы один слайд, зависящий от этого главного слайда. Только для чтения  boolean .

**Возвращаемое значение:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Возвращает менеджер темы. Только для чтения [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Возвращаемое значение:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```

Возвращает или задаёт имя главного слайда. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Возвращает или задаёт имя главного слайда. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет. Для самого главного слайда это свойство всегда возвращает  false . Чтение/запись  boolean .

**Возвращаемое значение:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет. Для самого главного слайда это свойство всегда возвращает  false . Чтение/запись  boolean .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Возвращает коллекцию направляющих для главного слайда. Только для чтения [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
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


**Возвращаемое значение:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)