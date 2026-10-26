---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents normal view properties.
type: docs
url: /hu/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

A normál nézet tulajdonságait reprezentálja. A normál nézet három tartalmi területből áll: maga a dia, egy oldalsó tartalmi terület, és egy alsó tartalmi terület.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Specifies whether the application should show icons if displaying outline content in any of the content regions of normal view mode. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Specifies whether the application should show icons if displaying outline content in any of the content regions of normal view mode. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Specifies whether the vertical splitter should snap to a minimized state when the side region is sufficiently small. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Specifies whether the vertical splitter should snap to a minimized state when the side region is sufficiently small. |
| [getVerticalBarState()](#getVerticalBarState--) | Specifies the state that the vertical splitter bar should be shown in. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Specifies the state that the vertical splitter bar should be shown in. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Specifies the state that the horizontal splitter bar should be shown in. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Specifies the state that the horizontal splitter bar should be shown in. |
| [getPreferSingleView()](#getPreferSingleView--) | Specifies whether the user prefers to see a full-window single-content region over the standard normal view with three content regions. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Specifies whether the user prefers to see a full-window single-content region over the standard normal view with three content regions. |
| [getRestoredLeft()](#getRestoredLeft--) | This element specifies the sizing of the side content region of the normal view, when the region is of a variable restored size(neither minimized nor maximized). |
| [getRestoredTop()](#getRestoredTop--) | This element specifies the sizing of the top slide region of the normal view, when the region is of a variable restored size(neither minimized nor maximized). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```


Megadja, hogy az alkalmazás megjelenítse-e az ikonokat, ha vázlat tartalmat jelenít meg a normál nézet bármely tartalmi régiójában. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```


Megadja, hogy az alkalmazás megjelenítse-e az ikonokat, ha vázlat tartalmat jelenít meg a normál nézet bármely tartalmi régiójában. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```


Megadja, hogy a függőleges osztó sáv minimalizált állapotba pattantsa-e, ha az oldalsó régió elég kicsi. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```


Megadja, hogy a függőleges osztó sáv minimalizált állapotba pattantsa-e, ha az oldalsó régió elég kicsi. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```


Megadja, hogy a függőleges osztó sáv milyen állapotban legyen megjelenítve. A függőleges osztó sáv elválasztja a diát az oldalsó tartalmi régiótól.

**Visszatérési érték:**
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


Megadja, hogy a vízszintes osztó sáv milyen állapotban legyen megjelenítve. A vízszintes osztó sáv elválasztja a diát a dia alatti tartalmi régiótól.

**Visszatérési érték:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```


Megadja, hogy a vízszintes osztó sáv milyen állapotban legyen megjelenítve. A vízszintes osztó sáv elválasztja a diát a dia alatti tartalmi régiótól.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```


Megadja, hogy a felhasználó a három tartalmi régióval rendelkező szabványos normál nézet helyett teljes ablakos egyetlen tartalmi régiót szeretne-e látni. Engedélyezve a alkalmazás egy tartalmi régiót teljes ablakban jeleníthet meg. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```


Megadja, hogy a felhasználó a három tartalmi régióval rendelkező szabványos normál nézet helyett teljes ablakos egyetlen tartalmi régiót szeretne-e látni. Engedélyezve a alkalmazás egy tartalmi régiót teljes ablakban jeleníthet meg. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```


Ez az elem meghatározza a normál nézet oldalsó tartalmi régiójának méretét, amikor a régió változó visszaállított méretű (sem minimalizált, sem maximalizált). Csak olvasható [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Visszatérési érték:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```


Ez az elem meghatározza a normál nézet felső diaterületének méretét, amikor a régió változó visszaállított méretű (sem minimalizált, sem maximalizált). Csak olvasható [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Visszatérési érték:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)