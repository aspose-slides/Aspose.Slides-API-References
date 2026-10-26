---
title: SectionZoomFrame
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt ein Section Zoom object in einer Folie dar.
type: docs
url: /de/com.aspose.slides/sectionzoomframe/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

Stellt ein Section Zoom object in einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Liest oder setzt das Abschnittsobjekt, auf das das Section Zoom object verlinkt ist. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Liest oder setzt das Abschnittsobjekt, auf das das Section Zoom object verlinkt ist. |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```


Liest oder setzt das Abschnittsobjekt, auf das das Section Zoom object verlinkt ist. Lesen/Schreiben [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Next example demonstrates changing target section and creates new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```


Liest oder setzt das Abschnittsobjekt, auf das das Section Zoom object verlinkt ist. Lesen/Schreiben [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Das nächste Beispiel demonstriert das Ändern des Zielabschnitts und erstellt ein neues Bild für das Section Zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |