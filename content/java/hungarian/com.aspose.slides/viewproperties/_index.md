---
title: ViewProperties
second_title: Aspose.Slides Java API hivatkozás
description: A teljes prezentációra vonatkozó nézeti tulajdonságok.
type: docs
url: /hu/com.aspose.slides/viewproperties/
---
**Öröklés:**  
java.lang.Object

**Minden implementált interfész:**  
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject  
```
public class ViewProperties implements IViewProperties, IDOMObject
```

A teljes prezentációra vonatkozó nézeti tulajdonságok.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getLastView()](#getLastView--) | Megadja a nézet módját, amelyet a prezentációs dokumentum legutóbb mentésekor használtak. |
| [setLastView(int value)](#setLastView-int-) | Megadja a nézet módját, amelyet a prezentációs dokumentum legutóbb mentésekor használtak. |
| [getShowComments()](#getShowComments--) | Megadja, hogy a diakönyvzeteket meg kell-e jeleníteni. |
| [setShowComments(byte value)](#setShowComments-byte-) | Megadja, hogy a diakönyvzeteket meg kell-e jeleníteni. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Ábrázolja a normál nézet tulajdonságait. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Megadja a dianézet módhoz kapcsolódó közös nézeti tulajdonságokat. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Megadja a jegyzet nézet módhoz kapcsolódó közös nézeti tulajdonságokat. |
| [getGridSpacing()](#getGridSpacing--) | Visszatér vagy beállítja a rács távolságát, amelyet a prezentációs dokumentum alatti rácshoz pontokban kell használni. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Visszatér vagy beállítja a rács távolságát, amelyet a prezentációs dokumentum alatti rácshoz pontokban kell használni. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getLastView() {#getLastView--}
```
public final int getLastView()
```

Megadja a nézet módját, amelyet a prezentációs dokumentum legutóbb mentésekor használtak. Olvasás/írás [ViewType](../../com.aspose.slides/viewtype).

**Visszatér:**  
int

### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

Megadja a nézet módját, amelyet a prezentációs dokumentum legutóbb mentésekor használtak. Olvasás/írás [ViewType](../../com.aspose.slides/viewtype).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

Megadja, hogy a diakönyvzeteket meg kell-e jeleníteni. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte

### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

Megadja, hogy a diakönyvzeteket meg kell-e jeleníteni. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

Ábrázolja a normál nézet tulajdonságait. A normál nézet három tartalmi régióból áll: a dia, egy oldalsó tartalmi régió és egy alsó tartalmi régió. Csak olvasás [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Visszatér:**  
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)

### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

Megadja a dianézet módhoz kapcsolódó közös nézeti tulajdonságokat. Csak olvasás [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Visszatér:**  
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

Megadja a jegyzet nézet módhoz kapcsolódó közös nézeti tulajdonságokat. Csak olvasás [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Visszatér:**  
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

Visszatér vagy beállítja a rács távolságát, amelyet a prezentációs dokumentum alatti rácshoz pontokban kell használni. Olvasás/írás float.

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

A rácstávolság értékének pozitív számnak kell lennie. A tipikus értéktartomány 1 mm (2,8349607 pont) és 2 hüvelyk (144 pont) között.

**Visszatér:**  
float

### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

Visszatér vagy beállítja a rács távolságát, amelyet a prezentációs dokumentum alatti rácshoz pontokban kell használni. Olvasás/írás float.

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

A rácstávolság értékének pozitív számnak kell lennie. A tipikus értéktartomány 1 mm (2,8349607 pont) és 2 hüvelyk (144 pont) között.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszatér a Parent_Immediate objektummal. Csak olvasás IDOMObject.

**Visszatér:**  
com.aspose.slides.IDOMObject