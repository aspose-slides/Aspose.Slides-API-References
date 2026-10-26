---
title: ZoomObject
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een Zoom-object in een dia voor.
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

Stelt een Zoom-object in een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getImageType()](#getImageType--) | Haalt op of stelt het type afbeelding van een zoom-object in. |
| [setImageType(int value)](#setImageType-int-) | Haalt op of stelt het type afbeelding van een zoom-object in. |
| [getReturnToParent()](#getReturnToParent--) | Haalt op of stelt het navigatiegedrag in de diavoorstelling in. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Haalt op of stelt het navigatiegedrag in de diavoorstelling in. |
| [getShowBackground()](#getShowBackground--) | Haalt op of stelt de waarde in die aangeeft of de Zoom de achtergrond van de doel-dia zal gebruiken. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Haalt op of stelt de waarde in die aangeeft of de Zoom de achtergrond van de doel-dia zal gebruiken. |
| [getZoomImage()](#getZoomImage--) | Haalt op of stelt de afbeelding voor zoom-object in. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Haalt op of stelt de afbeelding voor zoom-object in. |
| [getTransitionDuration()](#getTransitionDuration--) | Haalt op of stelt de duur van de overgang tussen Zoom en dia in. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Haalt op of stelt de duur van de overgang tussen Zoom en dia in. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```

Haalt op of stelt het type afbeelding van een zoom-object in. Lezen/schrijven [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standaardwaarde: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
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

**Retourwaarde:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

Haalt op of stelt het type afbeelding van een zoom-object in. Lezen/schrijven [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standaardwaarde: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
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

Een true-waarde van de eigenschap specificeert terugkeren naar bovenliggend navigatiegedrag in de diavoorstelling.

**Retourwaarde:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

Haalt op of stelt het navigatiegedrag in de diavoorstelling in. Lezen/schrijven boolean. Standaardwaarde: false

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

Een true-waarde van de eigenschap specificeert terugkeren naar bovenliggend navigatiegedrag in de diavoorstelling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

Haalt op of stelt de waarde in die aangeeft of de Zoom de achtergrond van de doel-dia zal gebruiken. Lezen/schrijven boolean. Standaardwaarde: true

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

Haalt op of stelt de waarde in die aangeeft of de Zoom de achtergrond van de doel-dia zal gebruiken. Lezen/schrijven boolean. Standaardwaarde: true

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

Haalt op of stelt de afbeelding voor een zoom-object in. Lezen/schrijven [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> het voorbeeld toont het wijzigen van een afbeelding van een Zoom-object:
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


**Retourwaarde:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

Haalt op of stelt de afbeelding voor een zoom-object in. Lezen/schrijven [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> het voorbeeld toont het wijzigen van een afbeelding van een Zoom-object:
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

Als niet gespecificeerd (TransitionDur = 0), wordt de overgang van de doel-dia en de bijbehorende timing gebruikt.

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

Als niet gespecificeerd (TransitionDur = 0), wordt de overgang van de doel-dia en de bijbehorende timing gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |