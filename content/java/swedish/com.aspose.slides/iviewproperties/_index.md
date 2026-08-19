---
title: IViewProperties
second_title: Aspose.Slides for Java API Reference
description: Visningsinställningar för hela presentationen.
type: docs
url: /sv/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Visningsinställningar för hela presentationen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLastView()](#getLastView--) | Anger visningsläget som användes när presentationsdokumentet senast sparades. |
| [setLastView(int value)](#setLastView-int-) | Anger visningsläget som användes när presentationsdokumentet senast sparades. |
| [getShowComments()](#getShowComments--) | Anger om bildkommentarerna ska visas. |
| [setShowComments(byte value)](#setShowComments-byte-) | Anger om bildkommentarerna ska visas. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Anger gemensamma visningsinställningar som är associerade med bildvisningsläget. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Anger gemensamma visningsinställningar som är associerade med anteckningsvisningsläget. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Representerar normala visningsinställningar. |
| [getGridSpacing()](#getGridSpacing--) | Returnerar eller anger rutnätsavståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Returnerar eller anger rutnätsavståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Anger visningsläget som användes när presentationsdokumentet senast sparades. Läs/skriv [ViewType](../../com.aspose.slides/viewtype).

**Returnerar:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Anger visningsläget som användes när presentationsdokumentet senast sparades. Läs/skriv [ViewType](../../com.aspose.slides/viewtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Anger om bildkommentarerna ska visas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Anger om bildkommentarerna ska visas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Anger gemensamma visningsinställningar som är associerade med bildvisningsläget. Endast läsning [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returnerar:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Anger gemensamma visningsinställningar som är associerade med anteckningsvisningsläget. Endast läsning [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returnerar:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Representerar normala visningsinställningar. Det normala visningsläget består av tre innehållsområden: själva bilden, ett sidoinnehållsområde och ett botteninnehållsområde. Endast läsning [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Returnerar:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Returnerar eller anger rutnätsavståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. Läs/skriv float.

--------------------

> ```
> Följande exempel visar hur man ändrar rasteravståndet i en PowerPoint-presentation.
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

Rutnätsavståndsvärdet måste vara ett positivt tal. Det typiska värdeintervallet är från 1 mm (2.8349607 punkter) till 2 inches (144 punkter).

**Returnerar:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Returnerar eller anger rutnätsavståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. Läs/skriv float.

--------------------

> ```
> Följande exempel visar hur man ändrar rasteravståndet i en PowerPoint-presentation.
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

Rutnätsavståndsvärdet måste vara ett positivt tal. Det typiska värdeintervallet är från 1 mm (2.8349607 punkter) till 2 inches (144 punkter).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |