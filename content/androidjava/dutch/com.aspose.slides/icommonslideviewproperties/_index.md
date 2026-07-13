---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Vertegenwoordigt algemene weergave-eigenschappen voor dia’s.
type: docs
url: /nl/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Vertegenwoordigt algemene weergave-eigenschappen voor dia’s.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getScale()](#getScale--) | Specificeert de weergave-schaalverhouding in percentages. |
| [setScale(int value)](#setScale-int-) | Specificeert de weergave-schaalverhouding in percentages. |
| [getVariableScale()](#getVariableScale--) | Specificeert dat de weergave-inhoud automatisch moet schalen om optimaal te passen bij de huidige venstergrootte. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Specificeert dat de weergave-inhoud automatisch moet schalen om optimaal te passen bij de huidige venstergrootte. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourneert de verzameling van de tekengidsen. |
### getScale() {#getScale--}
```
public abstract int getScale()
```

Specificeert de weergave-schaalverhouding in percentages. Lezen/schrijven int.

**Retourneert:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

Specificeert de weergave-schaalverhouding in percentages. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

Specificeert dat de weergave-inhoud automatisch moet schalen om optimaal te passen bij de huidige venstergrootte. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

Specificeert dat de weergave-inhoud automatisch moet schalen om optimaal te passen bij de huidige venstergrootte. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Retourneert de verzameling van de tekengidsen. Alleen-lezen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Adding the new vertical drawing guide to the right of the slide center
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // Adding the new horizontal drawing guide below the slide center
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)