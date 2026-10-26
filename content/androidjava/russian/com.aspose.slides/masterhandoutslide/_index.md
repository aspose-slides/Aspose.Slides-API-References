---
title: MasterHandoutSlide
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет главный слайд для раздаточных материалов.
type: docs
url: /ru/com.aspose.slides/masterhandoutslide/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

Представляет главный слайд для раздаточных материалов.
## Методы

| Метод | Описание |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Указывает, должны ли формы на главном слайде отображаться на слайдах или нет. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Указывает, должны ли формы на главном слайде отображаться на слайдах или нет. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter главного раздаточного слайда. |
| [getThemeManager()](#getThemeManager--) | Возвращает менеджер темы. |
| [getDrawingGuides()](#getDrawingGuides--) | Возвращает коллекцию направляющих рисунка для главного раздаточного слайда. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Указывает, должны ли формы на главном слайде отображаться на слайдах или нет. Для самого главного слайда это свойство всегда возвращает false. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Указывает, должны ли формы на главном слайде отображаться на слайдах или нет. Для самого главного слайда это свойство всегда возвращает false. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

Возвращает менеджер HeaderFooter главного раздаточного слайда. Только для чтения [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Возвращаемое значение:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Возвращает менеджер темы. Только для чтения [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Возвращаемое значение:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Возвращает коллекцию направляющих рисунка для главного раздаточного слайда. Только для чтения [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Добавление новой горизонтальной направляющей над центром слайда
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)