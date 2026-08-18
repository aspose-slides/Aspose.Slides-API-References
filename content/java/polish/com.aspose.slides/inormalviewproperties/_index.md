---
title: INormalViewProperties
second_title: Aspose.Slides for Java API Reference
description: Represents normal view properties.
type: docs
url: /pl/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Reprezentuje właściwości normalnego widoku. Normalny widok składa się z trzech regionów zawartości: samego slajdu, bocznego regionu zawartości oraz dolnego regionu zawartości.
## Metody

| Metoda | Opis |
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

Określa, czy aplikacja powinna wyświetlać ikony przy wyświetlaniu treści konspektu w dowolnym z regionów zawartości trybu normalnego widoku. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Określa, czy aplikacja powinna wyświetlać ikony przy wyświetlaniu treści konspektu w dowolnym z regionów zawartości trybu normalnego widoku. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Określa, czy pionowy podziałnik ma przyciągać się do stanu zminimalizowanego, gdy boczny region jest wystarczająco mały. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Określa, czy pionowy podziałnik ma przyciągać się do stanu zminimalizowanego, gdy boczny region jest wystarczająco mały. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Określa stan, w jakim ma być wyświetlany pionowy pasek podziału. Pionowy pasek podziału oddziela slajd od bocznego regionu zawartości.

**Zwraca:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Określa stan, w jakim ma być wyświetlany pionowy pasek podziału. Pionowy pasek podziału oddziela slajd od bocznego regionu zawartości.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Określa stan, w jakim ma być wyświetlany poziomy pasek podziału. Poziomy pasek podziału oddziela slajd od regionu zawartości pod slajdem.

**Zwraca:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Określa stan, w jakim ma być wyświetlany poziomy pasek podziału. Poziomy pasek podziału oddziela slajd od regionu zawartości pod slajdem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Określa, czy użytkownik woli zobaczyć pojedynczy region zawartości na pełnym oknie zamiast standardowego normalnego widoku z trzema regionami zawartości. Jeśli włączone, aplikacja może wybrać wyświetlenie jednego z regionów zawartości w całym oknie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Określa, czy użytkownik woli zobaczyć pojedynczy region zawartości na pełnym oknie zamiast standardowego normalnego widoku z trzema regionami zawartości. Jeśli włączone, aplikacja może wybrać wyświetlenie jednego z regionów zawartości w całym oknie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Ten element określa rozmiar bocznego regionu zawartości w normalnym widoku, gdy region ma zmienny przywrócony rozmiar (niezminimalizowany ani niezmaksymalizowany). Tylko do odczytu [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Zwraca:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Ten element określa rozmiar górnego regionu slajdu w normalnym widoku, gdy region ma zmienny przywrócony rozmiar (niezminimalizowany ani niezmaksymalizowany). Tylko do odczytu [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Zwraca:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)