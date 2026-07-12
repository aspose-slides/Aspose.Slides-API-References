---
title: CommonSlideViewProperties
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt gemeinsame Folienansichtseigenschaften dar.
type: docs
url: /de/com.aspose.slides/commonslideviewproperties/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Stellt gemeinsame Folienansichtseigenschaften dar.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Instanziiert ein Presentation-Objekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Einstellen der Ansichtseigenschaften der Präsentation
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Zoomwert in Prozent für die Folienansicht
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Zoomwert in Prozent für die Notizansicht
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getScale()](#getScale--) | Gibt das Ansichts-Skalierungsverhältnis in Prozent an. |
| [setScale(int value)](#setScale-int-) | Gibt das Ansichts-Skalierungsverhältnis in Prozent an. |
| [getVariableScale()](#getVariableScale--) | Gibt an, dass der Ansichtsinhalt automatisch skaliert werden soll, um optimal in die aktuelle Fenstergröße zu passen. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Gibt an, dass der Ansichtsinhalt automatisch skaliert werden soll, um optimal in die aktuelle Fenstergröße zu passen. |
| [getDrawingGuides()](#getDrawingGuides--) | Gibt die Sammlung der Zeichenhilfen zurück. |
### getScale() {#getScale--}
```
public final int getScale()
```


Gibt das Ansichts-Skalierungsverhältnis in Prozent an. Lesen/Schreiben int.

**Rückgabe:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Gibt das Ansichts-Skalierungsverhältnis in Prozent an. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```


Gibt an, dass der Ansichtsinhalt automatisch skaliert werden soll, um optimal in die aktuelle Fenstergröße zu passen. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```


Gibt an, dass der Ansichtsinhalt automatisch skaliert werden soll, um optimal in die aktuelle Fenstergröße zu passen. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Gibt die Sammlung der Zeichenhilfen zurück. Nur-lesen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Hinzufügen der neuen vertikalen Zeichenlinie rechts von der Folienmitte
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Hinzufügen der neuen horizontalen Zeichenlinie unterhalb der Folienmitte
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)