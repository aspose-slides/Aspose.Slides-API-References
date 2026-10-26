---
title: INotesSlide
second_title: Справочник API Aspose.Slides для Java
description: Представляет слайд заметок в презентации.
type: docs
url: /ru/com.aspose.slides/inotesslide/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Представляет слайд заметок в презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter слайда заметок. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Возвращает объект TextFrame с текстом заметок, если он существует. |
| [getParentSlide()](#getParentSlide--) | Возвращает ParentSlide только для чтения [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```


Возвращает менеджер HeaderFooter слайда заметок. Только для чтения [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Возвращает:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```


Возвращает объект TextFrame с текстом заметок, если он существует. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возвращает:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```


Возвращает ParentSlide только для чтения [ISlide](../../com.aspose.slides/islide).

**Возвращает:**
[ISlide](../../com.aspose.slides/islide)