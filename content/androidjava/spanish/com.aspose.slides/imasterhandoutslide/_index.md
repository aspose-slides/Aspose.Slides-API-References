---
title: IMasterHandoutSlide
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa la diapositiva maestra para folletos.
type: docs
url: /es/com.aspose.slides/imasterhandoutslide/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

Representa la diapositiva maestra para folletos.
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Devuelve el administrador HeaderFooter de la diapositiva maestra de folletos. |
| [getDrawingGuides()](#getDrawingGuides--) | Devuelve una colección de guías de dibujo para la diapositiva maestra de folletos. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


Devuelve el administrador HeaderFooter de la diapositiva maestra de folletos. Solo lectura [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Devuelve:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Devuelve una colección de guías de dibujo para la diapositiva maestra de folletos. Solo lectura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Agregando la nueva guía de dibujo horizontal por encima del centro de la diapositiva
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)