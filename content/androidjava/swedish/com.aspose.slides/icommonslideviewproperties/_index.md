---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar gemensamma egenskaper för bildvisning.
type: docs
url: /sv/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Representerar gemensamma egenskaper för bildvisning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getScale()](#getScale--) | Anger vyens skalningsförhållande i procent. |
| [setScale(int value)](#setScale-int-) | Anger vyens skalningsförhållande i procent. |
| [getVariableScale()](#getVariableScale--) | Anger att innehållet i vyn automatiskt ska skalas för att passa bäst i det aktuella fönsterstorleken. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Anger att innehållet i vyn automatiskt ska skalas för att passa bäst i det aktuella fönsterstorleken. |
| [getDrawingGuides()](#getDrawingGuides--) | Returnerar samlingen av ritningsguider. |
### getScale() {#getScale--}
```
public abstract int getScale()
```


Anger vyens skalningsförhållande i procent. Läs/skriv int.

**Returnerar:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


Anger vyens skalningsförhållande i procent. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```


Anger att innehållet i vyn automatiskt ska skalas för att passa bäst i det aktuella fönsterstorleken. Läs/skriv boolean.

**Returnerar:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```


Anger att innehållet i vyn automatiskt ska skalas för att passa bäst i det aktuella fönsterstorleken. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Returnerar samlingen av ritningsguider. Endast läsning [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Lägger till den nya vertikala ritningsguiden till höger om bildens centrum
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
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