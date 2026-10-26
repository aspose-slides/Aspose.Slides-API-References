---
title: MasterSlide
second_title: Справочник API Aspose.Slides для Java
description: Представляет основной слайд в презентации.
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

Представляет основной слайд в презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter основного слайда. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Создает новый основной слайд на основе текущего, применяя к нему внешний шаблон, и применяет созданный основной слайд ко всем зависимым слайдам. |
| [getTitleStyle()](#getTitleStyle--) | Возвращает стиль заголовочного текста. |
| [getBodyStyle()](#getBodyStyle--) | Возвращает стиль основного текста. |
| [getOtherStyle()](#getOtherStyle--) | Возвращает стиль другого текста. |
| [getLayoutSlides()](#getLayoutSlides--) | Возвращает коллекцию дочерних слайдов макета для этого основного слайда. |
| [getPreserve()](#getPreserve--) | Определяет, будет ли соответствующий мастер удалён, когда все слайды, следующие за этим мастером, удалены. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Определяет, будет ли соответствующий мастер удалён, когда все слайды, следующие за этим мастером, удалены. |
| [getDependingSlides()](#getDependingSlides--) | Возвращает массив всех слайдов, зависящих от этого основного слайда. |
| [hasDependingSlides()](#hasDependingSlides--) | Возвращает true, если существует хотя бы один слайд, зависящий от этого основного слайда. |
| [getThemeManager()](#getThemeManager--) | Возвращает менеджер темы. |
| [getName()](#getName--) | Возвращает или задает имя основного слайда. |
| [setName(String value)](#setName-java.lang.String-) | Возвращает или задает имя основного слайда. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Указывает, следует ли отображать фигуры на основном слайде на слайдах или нет. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Указывает, следует ли отображать фигуры на основном слайде на слайдах или нет. |
| [getDrawingGuides()](#getDrawingGuides--) | Возвращает коллекцию направляющих рисунка для основного слайда. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Возвращает менеджер HeaderFooter основного слайда. Только для чтения [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Возвращает:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Создает новый основной слайд на основе текущего, применяя к нему внешний шаблон, и применяет созданный основной слайд ко всем зависимым слайдам.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | java.lang.String | Путь к файлу внешней темы (.thmx). |

**Возвращает:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Новый тематический MasterSlide.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Возвращает стиль заголовочного текста. Только для чтения [ITextStyle](../../com.aspose.slides/itextstyle).

**Возвращает:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Возвращает стиль основного текста. Только для чтения [ITextStyle](../../com.aspose.slides/itextstyle).

**Возвращает:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Возвращает стиль другого текста. Только для чтения [ITextStyle](../../com.aspose.slides/itextstyle).

**Возвращает:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Возвращает коллекцию дочерних слайдов макета для этого основного слайда. Только для чтения [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Вы можете получить доступ к альтернативному API для добавления/вставки/удаления/клонирования слайдов макета, используя свойство ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Возвращает:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Определяет, будет ли соответствующий мастер удалён, когда все слайды, следующие за этим мастером, удалены. Примечание: Aspose.Slides никогда не удалит неиспользуемый мастер сам по себе; для фактического удаления неиспользуемых мастеров вызовите [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Чтение/запись  boolean .

**Возвращает:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Определяет, будет ли соответствующий мастер удалён, когда все слайды, следующие за этим мастером, удалены. Примечание: Aspose.Slides никогда не удалит неиспользуемый мастер сам по себе; для фактического удаления неиспользуемых мастеров вызовите [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Чтение/запись  boolean .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Возвращает массив всех слайдов, зависящих от этого основного слайда.

**Возвращает:**
com.aspose.slides.ISlide[] - Массив [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Возвращает true, если существует хотя бы один слайд, зависящий от этого основного слайда. Только для чтения  boolean .

**Возвращает:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Возвращает менеджер темы. Только для чтения [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Возвращает:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```

Возвращает или задает имя основного слайда. Чтение/запись String.

**Возвращает:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Возвращает или задает имя основного слайда. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Указывает, следует ли отображать фигуры на основном слайде на слайдах или нет. Для самого основного слайда это свойство всегда возвращает  false . Чтение/запись  boolean .

**Возвращает:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Указывает, следует ли отображать фигуры на основном слайде на слайдах или нет. Для самого основного слайда это свойство всегда возвращает  false . Чтение/запись  boolean .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Возвращает коллекцию направляющих рисунка для основного слайда. Только для чтения [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Добавление новой вертикальной направляющей рисунка справа от центра слайда
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)