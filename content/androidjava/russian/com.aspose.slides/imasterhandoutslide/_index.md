---
title: IMasterHandoutSlide
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет мастер-слайд для раздаточных листов.
type: docs
url: /ru/com.aspose.slides/imasterhandoutslide/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

Представляет мастер-слайд для раздаточных листов.
## Методы

| Метод | Описание |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter мастер-слайда раздаточного листа. |
| [getDrawingGuides()](#getDrawingGuides--) | Возвращает коллекцию направляющих рисования для мастер-слайда раздаточного листа. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


Возвращает менеджер HeaderFooter мастер-слайда раздаточного листа. Только для чтения [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Возвращает:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Возвращает коллекцию направляющих рисования для мастер-слайда раздаточного листа. Только для чтения [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Добавляем новую горизонтальную направляющую рисования над центром слайда
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращает:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)