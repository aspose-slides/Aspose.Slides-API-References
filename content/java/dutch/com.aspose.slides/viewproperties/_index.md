---
title: ViewProperties
second_title: Aspose.Slides voor Java API-referentie
description: Presentatie-brede weergave-eigenschappen.
type: docs
url: /nl/com.aspose.slides/viewproperties/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Presentatie-brede weergave-eigenschappen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLastView()](#getLastView--) | Specificeert de weergavemodus die werd gebruikt toen het presentatiedocument voor het laatst werd opgeslagen. |
| [setLastView(int value)](#setLastView-int-) | Specificeert de weergavemodus die werd gebruikt toen het presentatiedocument voor het laatst werd opgeslagen. |
| [getShowComments()](#getShowComments--) | Specificeert of de dia-opmerkingen moeten worden getoond. |
| [setShowComments(byte value)](#setShowComments-byte-) | Specificeert of de dia-opmerkingen moeten worden getoond. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Stelt normale weergave-eigenschappen voor. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Specificeert gemeenschappelijke weergave-eigenschappen geassocieerd met de dia-weergavemodus. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Specificeert gemeenschappelijke weergave-eigenschappen geassocieerd met de notitie-weergavemodus. |
| [getGridSpacing()](#getGridSpacing--) | Geeft de rasterafstand terug of stelt deze in die moet worden gebruikt voor het raster onderliggend aan het presentatiedocument, in punten. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Geeft de rasterafstand terug of stelt deze in die moet worden gebruikt voor het raster onderliggend aan het presentatiedocument, in punten. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getLastView() {#getLastView--}
```
public final int getLastView()
```

Specificeert de weergavemodus die werd gebruikt toen het presentatiedocument voor het laatst werd opgeslagen. Lezen/Schrijven [ViewType](../../com.aspose.slides/viewtype).

**Retour:**
int

### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

Specificeert de weergavemodus die werd gebruikt toen het presentatiedocument voor het laatst werd opgeslagen. Lezen/Schrijven [ViewType](../../com.aspose.slides/viewtype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

Specificeert of de dia-opmerkingen moeten worden getoond. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte

### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

Specificeert of de dia-opmerkingen moeten worden getoond. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

Stelt normale weergave-eigenschappen voor. De normale weergave bestaat uit drie inhoudsgebieden: de dia zelf, een zij-inhoudsgebied en een onder-inhoudsgebied. Alleen-lezen [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Retour:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)

### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

Specificeert gemeenschappelijke weergave-eigenschappen geassocieerd met de dia-weergavemodus. Alleen-lezen [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Retour:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

Specificeert gemeenschappelijke weergave-eigenschappen geassocieerd met de notitie-weergavemodus. Alleen-lezen [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Retour:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

Geeft de rasterafstand terug of stelt deze in die moet worden gebruikt voor het raster onderliggend aan het presentatiedocument, in punten. Lezen/Schrijven float.

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

De rasterafstand moet een positief getal zijn. Het typische waardebereik is van 1 mm (2,8349607 punten) tot 2 inch (144 punten).

**Retour:**
float

### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

Geeft de rasterafstand terug of stelt deze in die moet worden gebruikt voor het raster onderliggend aan het presentatiedocument, in punten. Lezen/Schrijven float.

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

De rasterafstand moet een positief getal zijn. Het typische waardebereik is van 1 mm (2,8349607 punten) tot 2 inch (144 punten).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert een Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject