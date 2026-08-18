---
title: IMasterNotesSlide
second_title: Aspose.Slides for Java API Referansı
description: Notlar için ana slaytı temsil eder.
type: docs
url: /tr/com.aspose.slides/imasternotesslide/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

Notlar için ana slaytı temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Ana not slaydının HeaderFooter yöneticisini döndürür. |
| [getNotesStyle()](#getNotesStyle--) | Bir not metninin stilini döndürür. |
| [getDrawingGuides()](#getDrawingGuides--) | Ana not slaydının çizim kılavuzları koleksiyonunu döndürür. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Ana not slaydının HeaderFooter yöneticisini döndürür. Salt okunur [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**Döndürür:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```

Bir not metninin stilini döndürür. Salt okunur [ITextStyle](../../com.aspose.slides/itextstyle).

**Döndürür:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Ana not slaydının çizim kılavuzları koleksiyonunu döndürür. Salt okunur [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Slayt merkezinin altında yeni yatay çizim kılavuzunu ekleme
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)