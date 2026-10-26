---
title: CommonSlideViewProperties
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt gemeenschappelijke diaweergave-eigenschappen voor.
type: docs
url: /nl/com.aspose.slides/commonslideviewproperties/
---
**Overerving:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Stelt gemeenschappelijke diaweergave-eigenschappen voor.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Maak een Presentation-object dat een presentatiebestand vertegenwoordigt
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Instellen van weergave-eigenschappen van de presentatie
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Zoomwaarde in percentages voor diaweergave
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Zoomwaarde in percentages voor notitieweergave
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getScale()](#getScale--) | Specificeert de weergaveschaalverhouding in percentages. |
| [setScale(int value)](#setScale-int-) | Specificeert de weergaveschaalverhouding in percentages. |
| [getVariableScale()](#getVariableScale--) | Specificeert dat de inhoud van de weergave automatisch moet schalen om het huidige venstergrootte optimaal te passen. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Specificeert dat de inhoud van de weergave automatisch moet schalen om het huidige venstergrootte optimaal te passen. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourneert de collectie van de tekengidsen. |
### getScale() {#getScale--}
```
public final int getScale()
```


Specificeert de weergaveschaalverhouding in percentages. Lezen/Schrijven int.

**Retour:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Specificeert de weergaveschaalverhouding in percentages. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```


Specificeert dat de inhoud van de weergave automatisch moet schalen om het huidige venstergrootte optimaal te passen. Lezen/Schrijven boolean.

**Retour:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```


Specificeert dat de inhoud van de weergave automatisch moet schalen om het huidige venstergrootte optimaal te passen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
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
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Voegt de nieuwe verticale tekengids toe rechts van het midden van de dia
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Voegt de nieuwe horizontale tekengids toe onder het midden van de dia
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retour:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)