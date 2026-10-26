---
title: IViewProperties
second_title: Aspose.Slides for Java API Reference
description: Presentation wide view properties.
type: docs
url: /nl/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Presentatie-brede weergave-eigenschappen.
## Methoden

| Method | Description |
| --- | --- |
| [getLastView()](#getLastView--) | Specificeert de weergavemodus die werd gebruikt toen het presentatiedocument voor het laatst werd opgeslagen. |
| [setLastView(int value)](#setLastView-int-) | Specificeert de weergavemodus die werd gebruikt toen het presentatiedocument voor het laatst werd opgeslagen. |
| [getShowComments()](#getShowComments--) | Specificeert of de dia-opmerkingen moeten worden weergegeven. |
| [setShowComments(byte value)](#setShowComments-byte-) | Specificeert of de dia-opmerkingen moeten worden weergegeven. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Specificeert gemeenschappelijke weergave-eigenschappen die verband houden met de dia-weergavemodus. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Specificeert gemeenschappelijke weergave-eigenschappen die verband houden met de notitie-weergavemodus. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Stelt normale weergave-eigenschappen voor. |
| [getGridSpacing()](#getGridSpacing--) | Retourneert of stelt de rasterafstand in die moet worden gebruikt voor het raster onderliggend aan het presentatiedocument, in punten. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Retourneert of stelt de rasterafstand in die moet worden gebruikt voor het raster onderliggend aan het presentatiedocument, in punten. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Specificeert de weergavemodus die werd gebruikt toen het presentatiedocument voor het laatst werd opgeslagen. Lezen/schrijven [ViewType](../../com.aspose.slides/viewtype).

**Returns:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Specificeert de weergavemodus die werd gebruikt toen het presentatiedocument voor het laatst werd opgeslagen. Lezen/schrijven [ViewType](../../com.aspose.slides/viewtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Specificeert of de dia-opmerkingen moeten worden weergegeven. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Specificeert of de dia-opmerkingen moeten worden weergegeven. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Specificeert gemeenschappelijke weergave-eigenschappen die verband houden met de dia-weergavemodus. Alleen-lezen [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returns:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Specificeert gemeenschappelijke weergave-eigenschappen die verband houden met de notitie-weergavemodus. Alleen-lezen [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returns:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Stelt normale weergave-eigenschappen voor. De normale weergave bestaat uit drie inhoudsgebieden: de dia zelf, een zij-inhoudsgebied en een onderste inhoudsgebied. Alleen-lezen [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Returns:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Retourneert of stelt de rasterafstand in die moet worden gebruikt voor het raster onderliggend aan het presentatiedocument, in punten. Lezen/schrijven float.

--------------------

> ```
> De volgende voorbeeldcode laat zien hoe u de rasterafstand in een PowerPoint-presentatie kunt aanpassen.
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

De rasterafstand moet een positief getal zijn. Het typische bereik is van 1 mm (2.8349607 punten) tot 2 inch (144 punten).

**Returns:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Retourneert of stelt de rasterafstand in die moet worden gebruikt voor het raster onderliggend aan het presentatiedocument, in punten. Lezen/schrijven float.

--------------------

> ```
> De volgende voorbeeldcode laat zien hoe u de rasterafstand in een PowerPoint-presentatie kunt aanpassen.
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

De rasterafstand moet een positief getal zijn. Het typische bereik is van 1 mm (2.8349607 punten) tot 2 inch (144 punten).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |