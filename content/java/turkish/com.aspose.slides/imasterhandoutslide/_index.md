---
title: IMasterHandoutSlide
second_title: Aspose.Slides for Java API Referansı
description: El ilanları için ana slaydı temsil eder.
type: docs
url: /tr/com.aspose.slides/imasterhandoutslide/
---
**Tüm Gerçekleştirilen Arayüzler:**  
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)  
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

El ilanları için ana slaydı temsil eder.  
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Ana el ilanı slaydının HeaderFooter yöneticisini döndürür. |
| [getDrawingGuides()](#getDrawingGuides--) | Ana el ilanı slaydı için çizim kılavuzlarının bir koleksiyonunu döndürür. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

Ana el ilanı slaydının HeaderFooter yöneticisini döndürür. Salt okunur [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Döndürür:**  
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Ana el ilanı slaydı için çizim kılavuzlarının bir koleksiyonunu döndürür. Salt okunur [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Yeni yatay çizim kılavuzunu slayt merkezinin üzerine ekleme
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)