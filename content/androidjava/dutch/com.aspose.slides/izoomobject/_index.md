---
title: IZoomObject
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een Zoom-object in een dia.
type: docs
url: /nl/com.aspose.slides/izoomobject/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Vertegenwoordigt een Zoom-object in een dia.
## Methoden

| Method | Description |
| --- | --- |
| [getImageType()](#getImageType--) | Haalt of stelt het afbeeldingstype van een zoom-object in. |
| [setImageType(int value)](#setImageType-int-) | Haalt of stelt het afbeeldingstype van een zoom-object in. |
| [getReturnToParent()](#getReturnToParent--) | Haalt of stelt het navigatiegedrag in de diavoorstelling in. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Haalt of stelt het navigatiegedrag in de diavoorstelling in. |
| [getShowBackground()](#getShowBackground--) | Haalt of stelt de waarde die aangeeft of de Zoom de achtergrond van de doel-dia gebruikt in. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Haalt of stelt de waarde die aangeeft of de Zoom de achtergrond van de doel-dia gebruikt in. |
| [getZoomImage()](#getZoomImage--) | Haalt of stelt de afbeelding voor een zoom-object in. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Haalt of stelt de afbeelding voor een zoom-object in. |
| [getTransitionDuration()](#getTransitionDuration--) | Haalt of stelt de duur van de overgang tussen Zoom en dia in. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Haalt of stelt de duur van de overgang tussen Zoom en dia in. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```


Haalt of stelt het afbeeldingstype van een zoom-object in. Lezen/schrijven [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standaardwaarde: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Specificeert of het Zoom-object de dia-preview of een omslagafbeelding gebruikt.

**Retour:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```


Haalt of stelt het afbeeldingstype van een zoom-object in. Lezen/schrijven [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standaardwaarde: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Specificeert of het Zoom-object de dia-preview of een omslagafbeelding gebruikt.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```


Haalt of stelt het navigatiegedrag in de diavoorstelling in. Lezen/schrijven boolean. Standaardwaarde: false

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

Waarheidswaarde van de eigenschap geeft het terugkeren naar de bovenliggende navigatiegedrag in de diavoorstelling aan.

**Retour:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```


Haalt of stelt het navigatiegedrag in de diavoorstelling in. Lezen/schrijven boolean. Standaardwaarde: false

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

Waarheidswaarde van de eigenschap geeft het terugkeren naar de bovenliggende navigatiegedrag in de diavoorstelling aan.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```


Haalt of stelt de waarde die aangeeft of de Zoom de achtergrond van de doel-dia gebruikt in. Lezen/schrijven boolean. Standaardwaarde: true

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


**Retour:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```


Haalt of stelt de waarde die aangeeft of de Zoom de achtergrond van de doel-dia gebruikt in. Lezen/schrijven boolean. Standaardwaarde: true

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```


Haalt of stelt de afbeelding voor een zoom-object in. Lezen/schrijven [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```


Haalt of stelt de afbeelding voor een zoom-object in. Lezen/schrijven [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```


Haalt of stelt de duur van de overgang tussen Zoom en dia in. Lezen/schrijven float. Standaardwaarde: 1.0f

--------------------

> ```
> Het voorbeeld toont het wijzigen van de duur van de overgang tussen Zoom en dia:
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

Als niet gespecificeerd (TransitionDur = 0), wordt de overgang van de doel-dia gebruikt samen met de tijdstippen die bij die overgang horen.

**Retour:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```


Haalt of stelt de duur van de overgang tussen Zoom en dia in. Lezen/schrijven float. Standaardwaarde: 1.0f

--------------------

> ```
> Het voorbeeld toont het wijzigen van de duur van de overgang tussen Zoom en dia:
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

Als niet gespecificeerd (TransitionDur = 0), wordt de overgang van de doel-dia gebruikt samen met de tijdstippen die bij die overgang horen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |