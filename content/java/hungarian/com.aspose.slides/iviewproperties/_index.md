---
title: IViewProperties
second_title: Aspose.Slides for Java API Reference
description: Presentation wide view properties.
type: docs
url: /hu/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Az egész bemutatóra vonatkozó nézeti tulajdonságok.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getLastView()](#getLastView--) | Megadja a nézetmódot, amelyet a bemutató dokumentum legutóbb mentésekor használtak. |
| [setLastView(int value)](#setLastView-int-) | Megadja a nézetmódot, amelyet a bemutató dokumentum legutóbb mentésekor használtak. |
| [getShowComments()](#getShowComments--) | Megadja, hogy a dia megjegyzései megjelenjenek-e. |
| [setShowComments(byte value)](#setShowComments-byte-) | Megadja, hogy a dia megjegyzései megjelenjenek-e. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Megadja a dianézet módhoz kapcsolódó közös nézeti tulajdonságokat. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Megadja a jegyzetnézet módhoz kapcsolódó közös nézeti tulajdonságokat. |
| [getNormalViewProperties()](#getNormalViewProperties--) | A normál nézet tulajdonságait ábrázolja. |
| [getGridSpacing()](#getGridSpacing--) | Visszaadja vagy beállítja a bemutató dokumentum alatti rács távolságát pontban. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Visszaadja vagy beállítja a bemutató dokumentum alatti rács távolságát pontban. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Megadja a nézetmódot, amelyet a bemutató dokumentum legutóbb mentésekor használtak. Olvasás/írás [ViewType](../../com.aspose.slides/viewtype).

**Visszatér:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Megadja a nézetmódot, amelyet a bemutató dokumentum legutóbb mentésekor használtak. Olvasás/írás [ViewType](../../com.aspose.slides/viewtype).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Megadja, hogy a dia megjegyzései megjelenjenek-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Megadja, hogy a dia megjegyzései megjelenjenek-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Megadja a dianézet módhoz kapcsolódó közös nézeti tulajdonságokat. Csak olvasható [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Visszatér:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Megadja a jegyzetnézet módhoz kapcsolódó közös nézeti tulajdonságokat. Csak olvasható [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Visszatér:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

A normál nézet tulajdonságait ábrázolja. A normál nézet három tartalmi régióból áll: a dia magából, egy oldalsó tartalmi régióból és egy alsó tartalmi régióból. Csak olvasható [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Visszatér:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Visszaadja vagy beállítja a bemutató dokumentum alatti rács távolságát pontban. Olvasás/írás float.

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

A rács távolságának pozitív számnak kell lennie. A tipikus értéktartomány 1 mm (2.8349607 pont) és 2 hüvelyk (144 pont) között.

**Visszatér:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Visszaadja vagy beállítja a bemutató dokumentum alatti rács távolságát pontban. Olvasás/írás float.

--------------------

> ```
> A következő példakód bemutatja, hogyan lehet módosítani a rács távolságát egy PowerPoint bemutatóban.
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

A rács távolságának pozitív számnak kell lennie. A tipikus értéktartomány 1 mm (2.8349607 pont) és 2 hüvelyk (144 pont) között.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |