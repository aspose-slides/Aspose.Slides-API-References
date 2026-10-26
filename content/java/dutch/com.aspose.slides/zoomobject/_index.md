---
title: ZoomObject
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een Zoom-object in een dia.
type: docs
url: /nl/com.aspose.slides/zoomobject/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Stelt een Zoom-object voor in een dia.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getImageType()](#getImageType--) | Haalt op of stelt het beeldtype van een zoomobject in. |
| [setImageType(int value)](#setImageType-int-) | Haalt op of stelt het beeldtype van een zoomobject in. |
| [getReturnToParent()](#getReturnToParent--) | Haalt op of stelt het navigatiegedrag in de diavoorstelling in. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Haalt op of stelt het navigatiegedrag in de diavoorstelling in. |
| [getShowBackground()](#getShowBackground--) | Haalt op of stelt een waarde in die aangeeft of de Zoom de achtergrond van de bestemmingsdia gebruikt. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Haalt op of stelt een waarde in die aangeeft of de Zoom de achtergrond van de bestemmingsdia gebruikt. |
| [getZoomImage()](#getZoomImage--) | Haalt op of stelt een afbeelding in voor een zoomobject. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Haalt op of stelt een afbeelding in voor een zoomobject. |
| [getTransitionDuration()](#getTransitionDuration--) | Haalt op of stelt de duur van de overgang tussen Zoom en dia in. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Haalt op of stelt de duur van de overgang tussen Zoom en dia in. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```

Haalt op of stelt het beeldtype van een zoomobject in. Lezen/schrijven [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standaardwaarde: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Geeft aan of het Zoom-object de dia-preview of een omslagafbeelding gebruikt.

**Retourwaarde:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

Haalt op of stelt het beeldtype van een zoomobject in. Lezen/schrijven [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standaardwaarde: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Geeft aan of het Zoom-object de dia-preview of een omslagafbeelding gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

Haalt op of stelt het navigatiegedrag in de diavoorstelling in. Lezen/schrijven boolean. Standaardwaarde: false

--------------------

> ```
> Voorbeeld:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Een waar-waarde van de eigenschap geeft aan dat de navigatie terug naar de ouder wordt gebruikt in de diavoorstelling.

**Retourwaarde:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

Haalt op of stelt het navigatiegedrag in de diavoorstelling in. Lezen/schrijven boolean. Standaardwaarde: false

--------------------

> ```
> Voorbeeld:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Een waar-waarde van de eigenschap geeft aan dat de navigatie terug naar de ouder wordt gebruikt in de diavoorstelling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

Haalt op of stelt een waarde in die aangeeft of de Zoom de achtergrond van de bestemmingsdia gebruikt. Lezen/schrijven boolean. Standaardwaarde: true

--------------------

> ```
> het voorbeeld toont het verwijderen van de achtergrond van een afbeelding van een Zoom-object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourwaarde:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```

Haalt op of stelt een waarde in die aangeeft of de Zoom de achtergrond van de bestemmingsdia gebruikt. Lezen/schrijven boolean. Standaardwaarde: true

--------------------

> ```
> het voorbeeld toont het verwijderen van de achtergrond van een afbeelding van een Zoom-object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```

Haalt op of stelt een afbeelding in voor een zoomobject. Lezen/schrijven [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> het voorbeeld toont het wijzigen van een afbeelding van een Zoom-object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourwaarde:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

Haalt op of stelt een afbeelding in voor een zoomobject. Lezen/schrijven [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> het voorbeeld toont het wijzigen van een afbeelding van een Zoom-object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```

Haalt op of stelt de duur van de overgang tussen Zoom en dia in. Lezen/schrijven float. Standaardwaarde: 1.0f

--------------------

> ```
> het voorbeeld toont het wijzigen van de duur van de overgang tussen Zoom en dia:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Indien niet gespecificeerd (TransitionDur = 0), wordt de overgang van de bestemmingsdia en de bijbehorende timing gebruikt.

**Retourwaarde:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

Haalt op of stelt de duur van de overgang tussen Zoom en dia in. Lezen/schrijven float. Standaardwaarde: 1.0f

--------------------

> ```
> het voorbeeld toont het wijzigen van de duur van de overgang tussen Zoom en dia:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Indien niet gespecificeerd (TransitionDur = 0), wordt de overgang van de bestemmingsdia en de bijbehorende timing gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |