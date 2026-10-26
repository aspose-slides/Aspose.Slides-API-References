---
title: ViewProperties
second_title: Aspose.Slides voor Android via Java API-referentie
description: Presentatiebrede weergave-eigenschappen.
type: docs
url: /nl/com.aspose.slides/viewproperties/
---
**Erfelijkheid:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Presentatiebrede weergave-eigenschappen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLastView()](#getLastView--) | Specificeert de weergavemodus die is gebruikt toen het presentatiedocument voor het laatst werd opgeslagen. |
| [setLastView(int value)](#setLastView-int-) | Specificeert de weergavemodus die is gebruikt toen het presentatiedocument voor het laatst werd opgeslagen. |
| [getShowComments()](#getShowComments--) | Specificeert of de slide-opmerkingen moeten worden weergegeven. |
| [setShowComments(byte value)](#setShowComments-byte-) | Specificeert of de slide-opmerkingen moeten worden weergegeven. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Stelt normale weergave-eigenschappen voor. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Specificeert algemene weergave-eigenschappen die verbonden zijn aan de slide-weergavemodus. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Specificeert algemene weergave-eigenschappen die verbonden zijn aan de notities-weergavemodus. |
| [getGridSpacing()](#getGridSpacing--) | Retourneert of stelt de rasterafstand in die moet worden gebruikt voor het raster onder het presentatiedocument, in punten. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Retourneert of stelt de rasterafstand in die moet worden gebruikt voor het raster onder het presentatiedocument, in punten. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```


Specificeert de weergavemodus die is gebruikt toen het presentatiedocument voor het laatst werd opgeslagen. Lezen/Schrijven [ViewType](../../com.aspose.slides/viewtype).

**Retourwaarde:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```


Specificeert de weergavemodus die is gebruikt toen het presentatiedocument voor het laatst werd opgeslagen. Lezen/Schrijven [ViewType](../../com.aspose.slides/viewtype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```


Specificeert of de slide-opmerkingen moeten worden weergegeven. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourwaarde:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```


Specificeert of de slide-opmerkingen moeten worden weergegeven. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```


Stelt normale weergave-eigenschappen voor. De normale weergave bestaat uit drie inhoudsgebieden: de slide zelf, een zijinhoudsgebied en een onderste inhoudsgebied. Alleen-lezen [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Retourwaarde:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```


Specificeert algemene weergave-eigenschappen die verbonden zijn aan de slide-weergavemodus. Alleen-lezen [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Retourwaarde:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```


Specificeert algemene weergave-eigenschappen die verbonden zijn aan de notities-weergavemodus. Alleen-lezen [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Retourwaarde:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```


Retourneert of stelt de rasterafstand in die moet worden gebruikt voor het raster onder het presentatiedocument, in punten. Lezen/Schrijven float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

De rasterafstand moet een positief getal zijn. Het typische waardebereik ligt tussen 1 mm (2.8349607 punten) en 2 inch (144 punten).

**Retourwaarde:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```


Retourneert of stelt de rasterafstand in die moet worden gebruikt voor het raster onder het presentatiedocument, in punten. Lezen/Schrijven float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

De rasterafstand moet een positief getal zijn. Het typische waardebereik ligt tussen 1 mm (2.8349607 punten) en 2 inch (144 punten).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retourwaarde:**
com.aspose.slides.IDOMObject