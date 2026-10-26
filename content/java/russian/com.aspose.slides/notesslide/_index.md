---
title: NotesSlide
second_title: Справочник API Aspose.Slides for Java
description: Представляет слайд с заметками в презентации.
type: docs
url: /ru/com.aspose.slides/notesslide/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Все реализованные интерфейсы:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Представляет заметочный слайд в презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter заметочного слайда. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Возвращает TextFrame с текстом заметок, если он существует. |
| [getThemeManager()](#getThemeManager--) | Возвращает менеджер переопределяющей темы. |
| [getParentSlide()](#getParentSlide--) | Возвращает родительский слайд. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Указывает, следует ли показывать фигуры на мастер-слайде на слайдах или нет. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Указывает, следует ли показывать фигуры на мастер-слайде на слайдах или нет. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Возвращает менеджер HeaderFooter заметочного слайда. Только для чтения [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Возвращаемое значение:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

Возвращает TextFrame с текстом заметок, если он существует. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возвращаемое значение:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Возвращает менеджер переопределяющей темы. Только для чтения [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Возвращаемое значение:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

Возвращает родительский слайд. Только для чтения [ISlide](../../com.aspose.slides/islide).

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Указывает, следует ли показывать фигуры на мастер-слайде на слайдах или нет. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Указывает, следует ли показывать фигуры на мастер-слайде на слайдах или нет. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |