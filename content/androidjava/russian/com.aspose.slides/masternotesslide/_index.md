---
title: MasterNotesSlide
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет главный слайд для заметок.
type: docs
url: /ru/com.aspose.slides/masternotesslide/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

Представляет главный слайд заметок.
## Методы

| Метод | Описание |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter главного слайда заметок. |
| [getThemeManager()](#getThemeManager--) | Возвращает менеджер темы. |
| [getNotesStyle()](#getNotesStyle--) | Возвращает стиль текста заметок. |
| [getDrawingGuides()](#getDrawingGuides--) | Возвращает коллекцию руководящих линий для главного слайда заметок. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет. Для самого главного слайда это свойство всегда возвращает false. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет. Для самого главного слайда это свойство всегда возвращает false. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Возвращает менеджер HeaderFooter главного слайда заметок. Только для чтения [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Возвращаемое значение:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Возвращает менеджер темы. Только для чтения [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Возвращаемое значение:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

Возвращает стиль текста заметок. Только для чтения [ITextStyle](../../com.aspose.slides/itextstyle).

**Возвращаемое значение:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Возвращает коллекцию руководящих линий для главного слайда заметок. Только для чтения [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Добавление новой горизонтальной линии черчения ниже центра слайда
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)