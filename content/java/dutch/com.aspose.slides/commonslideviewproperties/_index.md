---
title: CommonSlideViewProperties
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt gemeenschappelijke diaweergave-eigenschappen.
type: docs
url: /nl/com.aspose.slides/commonslideviewproperties/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Vertegenwoordigt gemeenschappelijke diaweergave-eigenschappen.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Instantieer een Presentation-object dat een presentatiebestand vertegenwoordigt
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Instellen van weergave-eigenschappen van de presentatie
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Zoomwaarde in procenten voor de diaweergave
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Zoomwaarde in procenten voor notitieweergave
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Methoden

| Methode | Omschrijving |
| --- | --- |
| [getScale()](#getScale--) | Specificeert de weergaveschaalverhouding in percentages. |
| [setScale(int value)](#setScale-int-) | Specificeert de weergaveschaalverhouding in percentages. |
| [getVariableScale()](#getVariableScale--) | Geeft aan dat de weergave-inhoud automatisch moet schalen om het huidige venster het best te passen. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Geeft aan dat de weergave-inhoud automatisch moet schalen om het huidige venster het best te passen. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourneert de collectie van de tekengidsen. |
### getScale() {#getScale--}
```
public final int getScale()
```

Specificeert de weergaveschaalverhouding in percentages. Lezen/Schrijven int.

**Retourneert:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

Specificeert de weergaveschaalverhouding in percentages. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

Geeft aan dat de weergave-inhoud automatisch moet schalen om het huidige venster het best te passen. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

Geeft aan dat de weergave-inhoud automatisch moet schalen om het huidige venster het best te passen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Retourneert de collectie van de tekengidsen. Alleen-lezen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Voeg de nieuwe verticale tekengids toe rechts van het midden van de dia
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Voeg de nieuwe horizontale tekengids toe onder het midden van de dia
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)