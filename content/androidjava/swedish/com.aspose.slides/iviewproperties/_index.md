---
title: IViewProperties
second_title: Aspose.Slides för Android via Java API Referens
description: Vyegenskaper för hela presentationen.
type: docs
url: /sv/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Vyegenskaper för hela presentationen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLastView()](#getLastView--) | Anger vyläget som användes när presentationsdokumentet senast sparades. |
| [setLastView(int value)](#setLastView-int-) | Anger vyläget som användes när presentationsdokumentet senast sparades. |
| [getShowComments()](#getShowComments--) | Anger om bildkommentarer ska visas. |
| [setShowComments(byte value)](#setShowComments-byte-) | Anger om bildkommentarer ska visas. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Anger gemensamma vyegenskaper som är associerade med bildvyläget. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Anger gemensamma vyegenskaper som är associerade med anteckningsvyläget. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Representerar normala vyegenskaper. |
| [getGridSpacing()](#getGridSpacing--) | Returnerar eller anger rasteravståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Returnerar eller anger rasteravståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```


Anger vyläget som användes när presentationsdokumentet senast sparades. Läs/skriv [ViewType](../../com.aspose.slides/viewtype).

**Returnerar:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```


Anger vyläget som användes när presentationsdokumentet senast sparades. Läs/skriv [ViewType](../../com.aspose.slides/viewtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```


Anger om bildkommentarer ska visas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```


Anger om bildkommentarer ska visas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```


Anger gemensamma vyegenskaper som är associerade med bildvyläget. Skrivskyddad [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returnerar:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```


Anger gemensamma vyegenskaper som är associerade med anteckningsvyläget. Skrivskyddad [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returnerar:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```


Representerar normala vyegenskaper. Den normala vyn består av tre innehållsområden: själva bilden, ett sidoinnehållsområde och ett botteninnehållsområde. Skrivskyddad [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Returnerar:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
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

Rasteravståndsvärdet måste vara ett positivt tal. Det typiska värdeintervallet är från 1 mm (2,8349607 punkter) till 2 tum (144 punkter).

**Returnerar:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```


Returnerar eller anger rasteravståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. Läs/skriv float.

--------------------

> ```
> Följande exempelprogram visar hur man ändrar rasteravståndet i en PowerPoint-presentation.
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

Rasteravståndsvärdet måste vara ett positivt tal. Det typiska värdeintervallet är från 1 mm (2,8349607 punkter) till 2 tum (144 punkter).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |