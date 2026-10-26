---
title: IViewProperties
second_title: Aspose.Slides for Android via Java API referencia
description: Az egész prezentációra vonatkozó nézeti tulajdonságok.
type: docs
url: /hu/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Az egész prezentációra vonatkozó nézeti tulajdonságok.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getLastView()](#getLastView--) | Megadja a nézetmódot, amelyet a prezentációdokumentum legutóbb mentésekor használtak. |
| [setLastView(int value)](#setLastView-int-) | Megadja a nézetmódot, amelyet a prezentációdokumentum legutóbb mentésekor használtak. |
| [getShowComments()](#getShowComments--) | Megadja, hogy a dia megjegyzései megjelenjenek-e. |
| [setShowComments(byte value)](#setShowComments-byte-) | Megadja, hogy a dia megjegyzései megjelenjenek-e. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Megadja a dianézet módhoz kapcsolódó közös nézeti tulajdonságokat. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Megadja a jegyzetnézet módhoz kapcsolódó közös nézeti tulajdonságokat. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Képviseli a normál nézeti tulajdonságokat. |
| [getGridSpacing()](#getGridSpacing--) | Visszaadja vagy beállítja a prezentációdokumentum alatti rács sorközeit pontban. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Visszaadja vagy beállítja a prezentációdokumentum alatti rács sorközeit pontban. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Megadja a nézetmódot, amelyet a prezentációdokumentum legutóbb mentésekor használtak. Olvasás/írás [ViewType](../../com.aspose.slides/viewtype).

**Visszatérési érték:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Megadja a nézetmódot, amelyet a prezentációdokumentum legutóbb mentésekor használtak. Olvasás/írás [ViewType](../../com.aspose.slides/viewtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Megadja, hogy a dia megjegyzései megjelenjenek-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Megadja, hogy a dia megjegyzései megjelenjenek-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Megadja a dianézet módhoz kapcsolódó közös nézeti tulajdonságokat. Csak olvasás [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Visszatérési érték:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Megadja a jegyzetnézet módhoz kapcsolódó közös nézeti tulajdonságokat. Csak olvasás [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Visszatérési érték:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Képviseli a normál nézeti tulajdonságokat. A normál nézet három tartalmi területből áll: maga a dia, egy oldalsó tartalmi terület és egy alsó tartalmi terület. Csak olvasás [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Visszatérési érték:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Visszaadja vagy beállítja a prezentációdokumentum alatti rács sorközeit pontban. Olvasás/írás float.

**Visszatérési érték:**
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

A rács sorköz értékének pozitív számnak kell lennie. A tipikus értéktartomány 1 mm (2.8349607 pont) és 2 hüvelyk (144 pont) között.

**Visszatérési érték:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Visszaadja vagy beállítja a prezentációdokumentum alatti rács sorközeit pontban. Olvasás/írás float.

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

A rács sorköz értékének pozitív számnak kell lennie. A tipikus értéktartomány 1 mm (2.8349607 pont) és 2 hüvelyk (144 pont) között.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |