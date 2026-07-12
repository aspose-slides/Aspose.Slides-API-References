---
title: ViewProperties
second_title: Aspose.Slides for Android Java API Referencia
description: A prezentációra vonatkozó nézeti tulajdonságok.
type: docs
url: /hu/com.aspose.slides/viewproperties/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

A prezentáció általános nézeti tulajdonságai.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [getLastView()](#getLastView--) | Megadja a nézetmódot, amelyet a prezentáció dokumentum legutóbbi mentésekor használtak. |
| [setLastView(int value)](#setLastView-int-) | Megadja a nézetmódot, amelyet a prezentáció dokumentum legutóbbi mentésekor használtak. |
| [getShowComments()](#getShowComments--) | Megadja, hogy a diák megjegyzései megjelenjenek-e. |
| [setShowComments(byte value)](#setShowComments-byte-) | Megadja, hogy a diák megjegyzései megjelenjenek-e. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Normál nézet tulajdonságait képviseli. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Megadja a dia nézetmóddal kapcsolatos közös nézeti tulajdonságokat. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Megadja a jegyzet nézetmóddal kapcsolatos közös nézeti tulajdonságokat. |
| [getGridSpacing()](#getGridSpacing--) | Visszaadja vagy beállítja a prezentáció dokumentum alatti rács rácstávolságát pontban. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Visszaadja vagy beállítja a prezentáció dokumentum alatti rács rácstávolságát pontban. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```


Megadja a nézetmódot, amelyet a prezentáció dokumentum legutóbbi mentésekor használtak. Olvasás/írás [ViewType](../../com.aspose.slides/viewtype).

**Visszatér:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```


Megadja a nézetmódot, amelyet a prezentáció dokumentum legutóbbi mentésekor használtak. Olvasás/írás [ViewType](../../com.aspose.slides/viewtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```


Megadja, hogy a diák megjegyzései megjelenjenek-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```


Megadja, hogy a diák megjegyzései megjelenjenek-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```


Normál nézet tulajdonságait képviseli. A normál nézet három tartalmi területből áll: magából a diákról, egy oldalsó tartalmi területről és egy alsó tartalmi területről. Csak olvasás [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Visszatér:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```


Megadja a dia nézetmóddal kapcsolatos közös nézeti tulajdonságokat. Csak olvasás [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Visszatér:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```


Megadja a jegyzet nézetmóddal kapcsolatos közös nézeti tulajdonságokat. Csak olvasás [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Visszatér:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```


Visszaadja vagy beállítja a prezentáció dokumentum alatti rács rácstávolságát pontban. Olvasás/írás float.

--------------------

> ```
> Az alábbi példakód bemutatja, hogyan változtatható meg a rácstávolság egy PowerPoint prezentációban.
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

A rácstávolság értékének pozitív számnak kell lennie. A tipikus értéktartomány 1 mm (2.8349607 pont) és 2 hüvelyk (144 pont) között.

**Visszatér:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```


Visszaadja vagy beállítja a prezentáció dokumentum alatti rács rácstávolságát pontban. Olvasás/írás float.

--------------------

> ```
> Az alábbi példakód bemutatja, hogyan változtatható meg a rácstávolság egy PowerPoint prezentációban.
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

A rácstávolság értékének pozitív számnak kell lennie. A tipikus értéktartomány 1 mm (2.8349607 pont) és 2 hüvelyk (144 pont) között.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszaadja a Parent_Immediate objektumot. Csak olvasás IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject