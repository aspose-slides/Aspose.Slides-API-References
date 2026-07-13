---
title: IMasterHandoutSlide
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta la diapositiva master per i fogli volanti.
type: docs
url: /it/com.aspose.slides/imasterhandoutslide/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

Rappresenta la diapositiva master per i fogli volanti.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Restituisce il gestore HeaderFooter della diapositiva master del foglio volante. |
| [getDrawingGuides()](#getDrawingGuides--) | Restituisce una raccolta di guide di disegno per la diapositiva master del foglio volante. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


Restituisce il gestore HeaderFooter della diapositiva master del foglio volante. Solo lettura [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Restituisce:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Restituisce una raccolta di guide di disegno per la diapositiva master del foglio volante. Solo lettura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Aggiunta della nuova guida di disegno orizzontale sopra il centro della diapositiva
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)