---
title: NormalViewProperties
second_title: Aspose.Slides a Java API referencia
description: Normál nézet tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/normalviewproperties/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

A normál nézet tulajdonságait képviseli. A normál nézet három tartalmi régióból áll: magából a diából, egy oldalsó tartalmi régióból és egy alsó tartalmi régióból.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Példányosít egy prezentációobjektumot, amely egy prezentációs fájlt képvisel
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Megadja, hogy az alkalmazás ikonokat jelenítsen-e, ha a vázlat tartalmát bármelyik tartalmi régióban a normál nézet módban jeleníti meg. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Megadja, hogy az alkalmazás ikonokat jelenítsen-e, ha a vázlat tartalmát bármelyik tartalmi régióban a normál nézet módban jeleníti meg. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Megadja, hogy a függőleges elválasztó elcsúszhat-e minimális állapotba, ha az oldalsó régió elég kicsi. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Megadja, hogy a függőleges elválasztó elcsúszhat-e minimális állapotba, ha az oldalsó régió elég kicsi. |
| [getVerticalBarState()](#getVerticalBarState--) | Megadja, hogy milyen állapotban jelenjen meg a függőleges elválasztó sáv. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Megadja, hogy milyen állapotban jelenjen meg a függőleges elválasztó sáv. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Megadja, hogy milyen állapotban jelenjen meg a vízszintes elválasztó sáv. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Megadja, hogy milyen állapotban jelenjen meg a vízszintes elválasztó sáv. |
| [getPreferSingleView()](#getPreferSingleView--) | Megadja, hogy a felhasználó a teljes ablakos egyetlen tartalmi régiót részesíti-e előnyben a három tartalmi régióval rendelkező szabványos normál nézettel szemben. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Megadja, hogy a felhasználó a teljes ablakos egyetlen tartalmi régiót részesíti-e előnyben a három tartalmi régióval rendelkező szabványos normál nézettel szemben. |
| [getRestoredLeft()](#getRestoredLeft--) | Ez az elem a normál nézet oldalsó tartalmi régiójának méretezését határozza meg, amikor a régió változó visszaállított méretű (sem minimalizált, sem maximalizált). |
| [getRestoredTop()](#getRestoredTop--) | Ez az elem a normál nézet felső diarégiójának méretezését határozza meg, amikor a régió változó visszaállított méretű (sem minimalizált, sem maximalizált). |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Megadja, hogy az alkalmazás ikonokat jelenítsen-e, ha a vázlat tartalmát bármelyik tartalmi régióban a normál nézet módban jeleníti meg. Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Megadja, hogy az alkalmazás ikonokat jelenítsen-e, ha a vázlat tartalmát bármelyik tartalmi régióban a normál nézet módban jeleníti meg. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Megadja, hogy a függőleges elválasztó elcsúszhat-e minimális állapotba, ha az oldalsó régió elég kicsi. Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Megadja, hogy a függőleges elválasztó elcsúszhat-e minimális állapotba, ha az oldalsó régió elég kicsi. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Megadja, hogy milyen állapotban jelenjen meg a függőleges elválasztó sáv. A függőleges elválasztó sáv elválasztja a diát az oldalsó tartalmi régiótól.

**Visszatérési érték:**
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Megadja, hogy milyen állapotban jelenjen meg a függőleges elválasztó sáv. A függőleges elválasztó sáv elválasztja a diát az oldalsó tartalmi régiótól.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Megadja, hogy milyen állapotban jelenjen meg a vízszintes elválasztó sáv. A vízszintes elválasztó sáv elválasztja a diát az alatta lévő tartalmi régiótól.

**Visszatérési érték:**
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Megadja, hogy milyen állapotban jelenjen meg a vízszintes elválasztó sáv. A vízszintes elválasztó sáv elválasztja a diát az alatta lévő tartalmi régiótól.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Megadja, hogy a felhasználó a teljes ablakos egyetlen tartalmi régiót részesíti-e előnyben a három tartalmi régióval rendelkező szabványos normál nézettel szemben. Ha engedélyezve van, az alkalmazás egy tartalmi régiót jeleníthet meg az egész ablakban. Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Megadja, hogy a felhasználó a teljes ablakos egyetlen tartalmi régiót részesíti-e előnyben a három tartalmi régióval rendelkező szabványos normál nézettel szemben. Ha engedélyezve van, az alkalmazás egy tartalmi régiót jeleníthet meg az egész ablakban. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Ez az elem a normál nézet oldalsó tartalmi régiójának méretezését határozza meg, amikor a régió változó visszaállított méretű (sem minimalizált, sem maximalizált). Csak olvasás [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Visszatérési érték:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Ez az elem a normál nézet felső diarégiójának méretezését határozza meg, amikor a régió változó visszaállított méretű (sem minimalizált, sem maximalizált). Csak olvasás [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Visszatérési érték:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)