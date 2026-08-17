---
title: IMasterNotesSlide
second_title: Справка API Aspose.Slides для Java
description: Представляет основной слайд для заметок.
type: docs
url: /ru/com.aspose.slides/imasternotesslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

Представляет основной слайд для заметок.
## Methods

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter мастера слайдов заметок. |
| [getNotesStyle()](#getNotesStyle--) | Возвращает стиль текста заметок. |
| [getDrawingGuides()](#getDrawingGuides--) | Возвращает коллекцию направляющих рисования для мастера слайдов заметок. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


Возвращает менеджер HeaderFooter мастера слайдов заметок. Только для чтения [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**Returns:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```


Возвращает стиль текста заметок. Только для чтения [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Возвращает коллекцию направляющих рисования для мастера слайдов заметок. Только для чтения [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Добавление новой горизонтальной направляющей рисования ниже центра слайда
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)