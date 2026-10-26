---
title: INormalViewProperties
second_title: Aspose.Slides for Java API referencia
description: A normál nézet tulajdonságait reprezentálja.
type: docs
url: /hu/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

A normál nézet tulajdonságait reprezentálja. A normál nézet három tartalmi régióból áll: a diából, egy oldalsó tartalmi régióból és egy alsó tartalmi régióból.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Megadja, hogy az alkalmazás megjelenítsen-e ikonokat, ha a normál nézet mód bármely tartalmi régiójában vázlat tartalmat jelenít meg. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Megadja, hogy az alkalmazás megjelenítsen-e ikonokat, ha a normál nézet mód bármely tartalmi régiójában vázlat tartalmat jelenít meg. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Megadja, hogy a függőleges osztó a bal oldali régió elég kicsi legyen esetén minimalizált állapotba ugráljon-e. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Megadja, hogy a függőleges osztó a bal oldali régió elég kicsi legyen esetén minimalizált állapotba ugráljon-e. |
| [getVerticalBarState()](#getVerticalBarState--) | Megadja, hogy a függőleges osztó sáv milyen állapotban legyen megjelenítve. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Megadja, hogy a függőleges osztó sáv milyen állapotban legyen megjelenítve. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Megadja, hogy a vízszintes osztó sáv milyen állapotban legyen megjelenítve. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Megadja, hogy a vízszintes osztó sáv milyen állapotban legyen megjelenítve. |
| [getPreferSingleView()](#getPreferSingleView--) | Megadja, hogy a felhasználó a három tartalmi régióval rendelkező szabványos normál nézet helyett teljes ablakos egyetlen tartalom régiót szeretne-e. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Megadja, hogy a felhasználó a három tartalmi régióval rendelkező szabványos normál nézet helyett teljes ablakos egyetlen tartalom régiót szeretne-e. |
| [getRestoredLeft()](#getRestoredLeft--) | Ez az elem a normál nézet oldalsó tartalmi régiójának méretezését határozza meg, amikor a régió változó helyreállított mérettel rendelkezik (sem minimalizált, sem maximalizált). |
| [getRestoredTop()](#getRestoredTop--) | Ez az elem a normál nézet felső diarétegének méretezését határozza meg, amikor a régió változó helyreállított mérettel rendelkezik (sem minimalizált, sem maximalizált). |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Megadja, hogy az alkalmazás megjelenítsen-e ikonokat, ha a normál nézet mód bármely tartalmi régiójában vázlat tartalmat jelenít meg. Olvasás/írás boolean.

**Visszatér:**  
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Megadja, hogy az alkalmazás megjelenítsen-e ikonokat, ha a normál nézet mód bármely tartalmi régiójában vázlat tartalmat jelenít meg. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Megadja, hogy a függőleges osztó a bal oldali régió elég kicsi legyen esetén minimalizált állapotba ugráljon-e. Olvasás/írás boolean.

**Visszatér:**  
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Megadja, hogy a függőleges osztó a bal oldali régió elég kicsi legyen esetén minimalizált állapotba ugráljon-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Megadja, hogy a függőleges osztó sáv milyen állapotban legyen megjelenítve. A függőleges osztó sáv elválasztja a diát az oldalsó tartalmi régiótól.

**Visszatér:**  
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Megadja, hogy a függőleges osztó sáv milyen állapotban legyen megjelenítve. A függőleges osztó sáv elválasztja a diát az oldalsó tartalmi régiótól.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Megadja, hogy a vízszintes osztó sáv milyen állapotban legyen megjelenítve. A vízszintes osztó sáv elválasztja a diát a diától alatti tartalmi régiótól.

**Visszatér:**  
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Megadja, hogy a vízszintes osztó sáv milyen állapotban legyen megjelenítve. A vízszintes osztó sáv elválasztja a diát a diától alatti tartalmi régiótól.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Megadja, hogy a felhasználó a három tartalmi régióval rendelkező szabványos normál nézet helyett teljes ablakos egyetlen tartalom régiót szeretne-e. Ha engedélyezve van, az alkalmazás egy tartalmi régiót a teljes ablakban jeleníthet meg. Olvasás/írás boolean.

**Visszatér:**  
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Megadja, hogy a felhasználó a három tartalmi régióval rendelkező szabványos normál nézet helyett teljes ablakos egyetlen tartalom régiót szeretne-e. Ha engedélyezve van, az alkalmazás egy tartalmi régiót a teljes ablakban jeleníthet meg. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Ez az elem a normál nézet oldalsó tartalmi régiójának méretezését határozza meg, amikor a régió változó helyreállított mérettel rendelkezik (sem minimalizált, sem maximalizált). Csak olvasható [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Visszatér:**  
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Ez az elem a normál nézet felső diarétegének méretezését határozza meg, amikor a régió változó helyreállított mérettel rendelkezik (sem minimalizált, sem maximalizált). Csak olvasható [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Visszatér:**  
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)