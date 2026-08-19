---
title: IZoomObject
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een Zoom-object in een dia voor.
type: docs
url: /nl/com.aspose.slides/izoomobject/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Stelt een Zoom-object in een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getImageType()](#getImageType--) | Haal het afbeeldingstype van een zoomobject op of stel het in. |
| [setImageType(int value)](#setImageType-int-) | Haal het afbeeldingstype van een zoomobject op of stel het in. |
| [getReturnToParent()](#getReturnToParent--) | Haal het navigatiegedrag in de diavoorstelling op of stel het in. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Haal het navigatiegedrag in de diavoorstelling op of stel het in. |
| [getShowBackground()](#getShowBackground--) | Haal de waarde op die aangeeft of de Zoom de achtergrond van de bestemmingsdia zal gebruiken of stel deze in. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Haal de waarde op die aangeeft of de Zoom de achtergrond van de bestemmingsdia zal gebruiken of stel deze in. |
| [getZoomImage()](#getZoomImage--) | Haal de afbeelding voor het zoomobject op of stel deze in. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Haal de afbeelding voor het zoomobject op of stel deze in. |
| [getTransitionDuration()](#getTransitionDuration--) | Haal de duur van de overgang tussen Zoom en dia op of stel deze in. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Haal de duur van de overgang tussen Zoom en dia op of stel deze in. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```


Haal het afbeeldingstype van een zoomobject op of stel het in. Lezen/Schrijven [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standaardwaarde: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

Specificeert of het Zoom-object de dia-preview of een omslagafbeelding gebruikt.

**Retourwaarde:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```


Haal het afbeeldingstype van een zoomobject op of stel het in. Lezen/Schrijven [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standaardwaarde: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

Specificeert of het Zoom-object de dia-preview of een omslagafbeelding gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```


Haal het navigatiegedrag in de diavoorstelling op of stel het in. Lezen/Schrijven boolean. Standaardwaarde: false

--------------------

> ```
> Example:
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

Een waar-waarde van de eigenschap specificeert het terugkeren-naar-bovenliggend navigatiegedrag in de diavoorstelling.

**Retourwaarde:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```


Haal het navigatiegedrag in de diavoorstelling op of stel het in. Lezen/Schrijven boolean. Standaardwaarde: false

--------------------

> ```
> Example:
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

Een waar-waarde van de eigenschap specificeert het terugkeren-naar-bovenliggend navigatiegedrag in de diavoorstelling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```


Haal de waarde op die aangeeft of de Zoom de achtergrond van de bestemmingsdia zal gebruiken of stel deze in. Lezen/Schrijven boolean. Standaardwaarde: true

--------------------

> ```
> Het voorbeeld toont het verwijderen van de achtergrond van een afbeelding van een Zoom-object:
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
public abstract void setShowBackground(boolean value)
```


Haal de waarde op die aangeeft of de Zoom de achtergrond van de bestemmingsdia zal gebruiken of stel deze in. Lezen/Schrijven boolean. Standaardwaarde: true

--------------------

> ```
> The example demonstrates removing the background of an image of a Zoom object:
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
public abstract IPPImage getZoomImage()
```


Haal de afbeelding voor het zoomobject op of stel deze in. Lezen/Schrijven [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Het voorbeeld toont het wijzigen van een afbeelding van een Zoom-object:
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
public abstract void setZoomImage(IPPImage value)
```


Haal de afbeelding voor het zoomobject op of stel deze in. Lezen/Schrijven [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Het voorbeeld toont het wijzigen van een afbeelding van een Zoom-object:
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
public abstract float getTransitionDuration()
```


Haal de duur van de overgang tussen Zoom en dia op of stel deze in. Lezen/Schrijven float. Standaardwaarde: 1.0f

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

Indien niet gespecificeerd (TransitionDur = 0), wordt de transitie van de bestemmingsdia gebruikt en de bijbehorende timing.

**Retourwaarde:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```


Haal de duur van de overgang tussen Zoom en dia op of stel deze in. Lezen/Schrijven float. Standaardwaarde: 1.0f

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

Indien niet gespecificeerd (TransitionDur = 0), wordt de transitie van de bestemmingsdia gebruikt en de bijbehorende timing.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |