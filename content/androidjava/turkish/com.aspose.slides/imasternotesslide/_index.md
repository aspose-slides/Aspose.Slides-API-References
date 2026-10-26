---
title: IMasterNotesSlide
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Notlar için ana slaytı temsil eder.
type: docs
url: /tr/com.aspose.slides/imasternotesslide/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

Notlar için ana slaytı temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Master notlar slaytının HeaderFooter yöneticisini döndürür. |
| [getNotesStyle()](#getNotesStyle--) | Not metninin stilini döndürür. |
| [getDrawingGuides()](#getDrawingGuides--) | Master notlar slaytı için çizim kılavuzlarının bir koleksiyonunu döndürür. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


Master notlar slaytının HeaderFooter yöneticisini döndürür. Yalnızca okuma [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**Döndürür:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```


Not metninin stilini döndürür. Yalnızca okuma [ITextStyle](../../com.aspose.slides/itextstyle).

**Döndürür:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Master notlar slaytı için çizim kılavuzlarının bir koleksiyonunu döndürür. Yalnızca okuma [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Yeni yatay çizim kılavuzunu slayt merkezinin altında ekleme
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)