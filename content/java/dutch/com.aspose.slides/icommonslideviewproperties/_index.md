---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Java API Reference
description: Stelt algemene diaweergave-eigenschappen voor.
type: docs
url: /nl/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Stelt algemene diaweergave-eigenschappen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getScale()](#getScale--) | Specificeert de weergave-schaalverhouding in procenten. |
| [setScale(int value)](#setScale-int-) | Specificeert de weergave-schaalverhouding in procenten. |
| [getVariableScale()](#getVariableScale--) | Specificeert dat de weergave-inhoud automatisch moet schalen om het huidige venster optimaal te passen. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Specificeert dat de weergave-inhoud automatisch moet schalen om het huidige venster optimaal te passen. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourneert de collectie van de tekengidsen. |

### getScale() {#getScale--}
```
public abstract int getScale()
```

Specificeert de weergave-schaalverhouding in procenten. Lezen/schrijven int.

**Retourneert:**
int

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

Specificeert de weergave-schaalverhouding in procenten. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

Specificeert dat de weergave-inhoud automatisch moet schalen om het huidige venster optimaal te passen. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

Specificeert dat de weergave-inhoud automatisch moet schalen om het huidige venster optimaal te passen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
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
>      // Voegt de nieuwe verticale tekengids toe aan de rechterkant van het midden van de dia
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // Voegt de nieuwe horizontale tekengids toe onder het midden van de dia
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)