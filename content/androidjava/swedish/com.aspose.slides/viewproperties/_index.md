---
title: ViewProperties
second_title: Aspose.Slides för Android via Java API-referens
description: Allmänna vyegenskaper för presentationen.
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

Allmänna vyegenskaper för presentationen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLastView()](#getLastView--) | Anger visningsläget som användes när presentationsdokumentet senast sparades. |
| [setLastView(int value)](#setLastView-int-) | Anger visningsläget som användes när presentationsdokumentet senast sparades. |
| [getShowComments()](#getShowComments--) | Anger om bildkommentarerna ska visas. |
| [setShowComments(byte value)](#setShowComments-byte-) | Anger om bildkommentarerna ska visas. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Representerar normala vyegenskaper. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Anger gemensamma vyegenskaper som är associerade med bildvyläget. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Anger gemensamma vyegenskaper som är associerade med notvyläget. |
| [getGridSpacing()](#getGridSpacing--) | Returnerar eller anger rasteravståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Returnerar eller anger rasteravståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```


Anger visningsläget som användes när presentationsdokumentet senast sparades. Läs/skriv [ViewType](../../com.aspose.slides/viewtype).

**Returnerar:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```


Anger visningsläget som användes när presentationsdokumentet senast sparades. Läs/skriv [ViewType](../../com.aspose.slides/viewtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```


Anger om bildkommentarerna ska visas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```


Anger om bildkommentarerna ska visas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```


Representerar normala vyegenskaper. Den normala vyn består av tre innehållsregioner: själva bilden, en sidoinnehållsregion och en botteninnehållsregion. Skrivskyddad [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Returnerar:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```


Anger gemensamma vyegenskaper som är associerade med bildvyläget. Skrivskyddad [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returnerar:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```


Anger gemensamma vyegenskaper som är associerade med notvyläget. Skrivskyddad [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returnerar:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```


Returnerar eller anger rasteravståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. Läs/skriv float.

**Returnerar:**
float
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


Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject