---
title: INotesSlide
second_title: Aspose.Slides для Android через Java API Reference
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
| [getNotesTextFrame()](#getNotesTextFrame--) | Возвращает TextFrame с текстом заметок, если он есть. |
| [getParentSlide()](#getParentSlide--) | Возвращает ParentSlide только для чтения [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Возвращает менеджер HeaderFooter слайда заметок. Только для чтения [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Возвращаемое значение:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

Возвращает TextFrame с текстом заметок, если он есть. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возвращаемое значение:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

Возвращает ParentSlide только для чтения [ISlide](../../com.aspose.slides/islide).

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide)