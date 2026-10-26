---
title: CommonSlideViewProperties
second_title: Aspose.Slides för Java API-referens
description: Representerar vanliga bildvisningsegenskaper.
type: docs
url: /sv/com.aspose.slides/commonslideviewproperties/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Representerar vanliga bildvisningsegenskaper.

--------------------

> ```
> Följande exempel visar hur du sätter zoomvärdet för en PowerPoint-presentationens bild.
>  
>  // Instansiera ett Presentation-objekt som representerar en presentationsfil
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Inställning av visningsegenskaper för presentationen
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Zoomvärde i procent för bildvyn
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Zoomvärde i procent för notervyn
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getScale()](#getScale--) | Anger vy-zoomförhållandet i procent. |
| [setScale(int value)](#setScale-int-) | Anger vy-zoomförhållandet i procent. |
| [getVariableScale()](#getVariableScale--) | Anger att vyinnehållet automatiskt ska skalas för att bäst passa aktuell fönsterstorlek. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Anger att vyinnehållet automatiskt ska skalas för att bäst passa aktuell fönsterstorlek. |
| [getDrawingGuides()](#getDrawingGuides--) | Returnerar samlingen av ritningsguider. |
### getScale() {#getScale--}
```
public final int getScale()
```


Anger vy-zoomförhållandet i procent. Läs/skriv int.

**Returnerar:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Anger vy-zoomförhållandet i procent. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```


Anger att vyinnehållet automatiskt ska skalas för att bäst passa aktuell fönsterstorlek. Läs/skriv boolean.

**Returnerar:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```


Anger att vyinnehållet automatiskt ska skalas för att bäst passa aktuell fönsterstorlek. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Returnerar samlingen av ritningsguider. Endast läsning [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Lägger till den nya vertikala ritningsguiden till höger om bildens centrum
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Lägger till den nya horisontella ritningsguiden under bildens centrum
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)