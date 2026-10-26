---
title: IViewProperties
second_title: Aspose.Slides voor Android via Java API-referentie
description: Presentatiebrede weergave-eigenschappen.
type: docs
url: /nl/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Presentatiebrede weergave-eigenschappen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLastView()](#getLastView--) | Specificeert de weergavemodus die werd gebruikt toen het presentatiedocument voor het laatst werd opgeslagen. |
| [setLastView(int value)](#setLastView-int-) | Specificeert de weergavemodus die werd gebruikt toen het presentatiedocument voor het laatst werd opgeslagen. |
| [getShowComments()](#getShowComments--) | Specificeert of de dia-opmerkingen getoond moeten worden. |
| [setShowComments(byte value)](#setShowComments-byte-) | Specificeert of de dia-opmerkingen getoond moeten worden. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Specificeert gemeenschappelijke weergave-eigenschappen die gekoppeld zijn aan de dia-weergavemodus. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Specificeert gemeenschappelijke weergave-eigenschappen die gekoppeld zijn aan de notitie-weergavemodus. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Stelt normale weergave-eigenschappen voor. |
| [getGridSpacing()](#getGridSpacing--) | Geeft de rasterafstand terug of stelt deze in die moet worden gebruikt voor het raster dat ten grondslag ligt aan het presentatiedocument, in punten. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Geeft de rasterafstand terug of stelt deze in die moet worden gebruikt voor het raster dat ten grondslag ligt aan het presentatiedocument, in punten. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Specificeert de weergavemodus die werd gebruikt toen het presentatiedocument voor het laatst werd opgeslagen. Lezen/schrijven [ViewType](../../com.aspose.slides/viewtype).

**Retour:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Specificeert de weergavemodus die werd gebruikt toen het presentatiedocument voor het laatst werd opgeslagen. Lezen/schrijven [ViewType](../../com.aspose.slides/viewtype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Specificeert of de dia-opmerkingen getoond moeten worden. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Specificeert of de dia-opmerkingen getoond moeten worden. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Specificeert gemeenschappelijke weergave-eigenschappen die gekoppeld zijn aan de dia-weergavemodus. Alleen-lezen [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Retour:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Specificeert gemeenschappelijke weergave-eigenschappen die gekoppeld zijn aan de notitie-weergavemodus. Alleen-lezen [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Retour:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Stelt normale weergave-eigenschappen voor. De normale weergave bestaat uit drie inhoudsgebieden: de dia zelf, een zijinhoudsgebied en een onderste inhoudsgebied. Alleen-lezen [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Retour:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Geeft de rasterafstand terug of stelt deze in die moet worden gebruikt voor het raster dat ten grondslag ligt aan het presentatiedocument, in punten. Lezen/schrijven float.

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

De waarde van de rasterafstand moet een positief getal zijn. Het typische bereik ligt tussen 1 mm (2.8349607 punten) en 2 inch (144 punten).

**Retour:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Geeft de rasterafstand terug of stelt deze in die moet worden gebruikt voor het raster dat ten grondslag ligt aan het presentatiedocument, in punten. Lezen/schrijven float.

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

De waarde van de rasterafstand moet een positief getal zijn. Het typische bereik ligt tussen 1 mm (2.8349607 punten) en 2 inch (144 punten).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |