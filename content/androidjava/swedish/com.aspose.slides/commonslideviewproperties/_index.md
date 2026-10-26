---
title: CommonSlideViewProperties
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar vanliga slide view-egenskaper.
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

Representerar vanliga egenskaper för slide view.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Skapa ett Presentation-objekt som representerar en presentationsfil
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Ställer in vyegenskaper för presentationen
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Zoomvärde i procent för bildvyn
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Zoomvärde i procent för anteckningsvyn
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getScale()](#getScale--) | Specificerar visningsskalningsförhållandet i procent. |
| [setScale(int value)](#setScale-int-) | Specificerar visningsskalningsförhållandet i procent. |
| [getVariableScale()](#getVariableScale--) | Specificerar att innehållet i vyn automatiskt skalas för att passa bäst i det aktuella fönstrets storlek. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Specificerar att innehållet i vyn automatiskt skalas för att passa bäst i det aktuella fönstrets storlek. |
| [getDrawingGuides()](#getDrawingGuides--) | Returnerar samlingen av ritningsguiderna. |
### getScale() {#getScale--}
```
public final int getScale()
```

Specificerar visningsskalningsförhållandet i procent. Läs/skriv int.

**Returnerar:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

Specificerar visningsskalningsförhållandet i procent. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

Specificerar att innehållet i vyn automatiskt skalas för att passa bäst i det aktuella fönstrets storlek. Läs/skriv boolean.

**Returnerar:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

Specificerar att innehållet i vyn automatiskt skalas för att passa bäst i det aktuella fönstrets storlek. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Returnerar samlingen av ritningsguiderna. Skrivskyddad [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Lägger till den nya vertikala ritningsguiden till höger om bildens mitt
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Lägger till den nya horisontella ritningsguiden under bildens mitt
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)