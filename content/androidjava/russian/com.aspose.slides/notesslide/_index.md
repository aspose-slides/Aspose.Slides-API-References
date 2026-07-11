---
title: NotesSlide
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет слайд заметок в презентации.
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

Представляет слайд заметок в презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter слайда заметок. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Возвращает TextFrame с текстом заметок, если он есть. |
| [getThemeManager()](#getThemeManager--) | Возвращает переопределяющий менеджер темы. |
| [getParentSlide()](#getParentSlide--) | Возвращает родительский слайд. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Указывает, должны ли объекты на слайде-шаблоне отображаться на слайдах или нет. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Указывает, должны ли объекты на слайде-шаблоне отображаться на слайдах или нет. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Возвращает менеджер HeaderFooter слайда заметок. Только для чтения [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Возвращает:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

Возвращает TextFrame с текстом заметок, если он есть. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возвращает:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Возвращает переопределяющий менеджер темы. Только для чтения [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Возвращает:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

Возвращает родительский слайд. Только для чтения [ISlide](../../com.aspose.slides/islide).

**Возвращает:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Указывает, должны ли объекты на слайде-шаблоне отображаться на слайдах или нет. Чтение/запись boolean.

**Возвращает:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Указывает, должны ли объекты на слайде-шаблоне отображаться на слайдах или нет. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |