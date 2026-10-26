---
title: ViewProperties
second_title: Aspose.Slides för Java API-referens
description: Presentationens övergripande vyegenskaper.
type: docs
url: /sv/com.aspose.slides/viewproperties/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Presentationens övergripande vyegenskaper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLastView()](#getLastView--) | Anger vyläget som användes när presentationsdokumentet senast sparades. |
| [setLastView(int value)](#setLastView-int-) | Anger vyläget som användes när presentationsdokumentet senast sparades. |
| [getShowComments()](#getShowComments--) | Anger om bildkommentarer ska visas. |
| [setShowComments(byte value)](#setShowComments-byte-) | Anger om bildkommentarer ska visas. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Representerar normalvyegenskaper. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Anger gemensamma vyegenskaper som är kopplade till bildvyläget. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Anger gemensamma vyegenskaper som är kopplade till notevyläget. |
| [getGridSpacing()](#getGridSpacing--) | Returnerar eller anger rasteravståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Returnerar eller anger rasteravståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```


Anger vyläget som användes när presentationsdokumentet senast sparades. Läs/skriv [ViewType](../../com.aspose.slides/viewtype).

**Returnerar:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```


Anger vyläget som användes när presentationsdokumentet senast sparades. Läs/skriv [ViewType](../../com.aspose.slides/viewtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```


Anger om bildkommentarer ska visas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```


Anger om bildkommentarer ska visas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```


Representerar normalvyegenskaper. Normalvyn består av tre innehållsregioner: själva bilden, en sidoinnehållsregion och en nedersta innehållsregion. Endast läs [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Returnerar:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```


Anger gemensamma vyegenskaper som är kopplade till bildvyläget. Endast läs [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returnerar:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```


Anger gemensamma vyegenskaper som är kopplade till notevyläget. Endast läs [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returnerar:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```


Returnerar eller anger rasteravståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. Läs/skriv float.

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

Rasteravståndsvärdet måste vara ett positivt tal. Det typiska värdeintervallet är från 1 mm (2.8349607 punkter) till 2 tum (144 punkter).

**Returnerar:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```


Returnerar eller anger rasteravståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. Läs/skriv float.

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

Rasteravståndsvärdet måste vara ett positivt tal. Det typiska värdeintervallet är från 1 mm (2.8349607 punkter) till 2 tum (144 punkter).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returnerar Parent_Immediate-objekt. Endast läs IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject