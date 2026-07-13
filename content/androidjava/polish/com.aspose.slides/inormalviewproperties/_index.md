---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents normal view properties.
type: docs
url: /pl/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Reprezentuje właściwości normalnego widoku. Normalny widok składa się z trzech obszarów zawartości: samego slajdu, bocznego obszaru zawartości oraz dolnego obszaru zawartości.
## Metody

| Metoda | Opis |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Określa, czy aplikacja powinna wyświetlać ikony przy wyświetlaniu zawartości zarysu w dowolnym z obszarów zawartości trybu normalnego widoku. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Określa, czy aplikacja powinna wyświetlać ikony przy wyświetlaniu zawartości zarysu w dowolnym z obszarów zawartości trybu normalnego widoku. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Określa, czy pionowy podziałnik powinien przełączać się do stanu zminimalizowanego, gdy boczny obszar jest wystarczająco mały. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Określa, czy pionowy podziałnik powinien przełączać się do stanu zminimalizowanego, gdy boczny obszar jest wystarczająco mały. |
| [getVerticalBarState()](#getVerticalBarState--) | Określa stan, w jakim powinien być wyświetlany pionowy pasek podziałnika. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Określa stan, w jakim powinien być wyświetlany pionowy pasek podziałnika. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Określa stan, w jakim powinien być wyświetlany poziomy pasek podziałnika. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Określa stan, w jakim powinien być wyświetlany poziomy pasek podziałnika. |
| [getPreferSingleView()](#getPreferSingleView--) | Określa, czy użytkownik preferuje wyświetlanie jednego obszaru zawartości w pełnym oknie zamiast standardowego normalnego widoku z trzema obszarami zawartości. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Określa, czy użytkownik preferuje wyświetlanie jednego obszaru zawartości w pełnym oknie zamiast standardowego normalnego widoku z trzema obszarami zawartości. |
| [getRestoredLeft()](#getRestoredLeft--) | Ten element określa rozmiar bocznego obszaru zawartości normalnego widoku, gdy obszar ma zmienny przywrócony rozmiar (niezminimalizowany ani nie zmaksymalizowany). |
| [getRestoredTop()](#getRestoredTop--) | Ten element określa rozmiar górnego obszaru slajdu normalnego widoku, gdy obszar ma zmienny przywrócony rozmiar (niezminimalizowany ani nie zmaksymalizowany). |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Określa, czy aplikacja powinna wyświetlać ikony przy wyświetlaniu zawartości zarysu w dowolnym z obszarów zawartości trybu normalnego widoku. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Określa, czy aplikacja powinna wyświetlać ikony przy wyświetlaniu zawartości zarysu w dowolnym z obszarów zawartości trybu normalnego widoku. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Określa, czy pionowy podziałnik powinien przełączać się do stanu zminimalizowanego, gdy boczny obszar jest wystarczająco mały. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Określa, czy pionowy podziałnik powinien przełączać się do stanu zminimalizowanego, gdy boczny obszar jest wystarczająco mały. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Określa stan, w jakim powinien być wyświetlany pionowy pasek podziałnika. Pionowy pasek podziałnika oddziela slajd od bocznego obszaru zawartości.

**Zwraca:**
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Określa stan, w jakim powinien być wyświetlany pionowy pasek podziałnika. Pionowy pasek podziałnika oddziela slajd od bocznego obszaru zawartości.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Określa stan, w jakim powinien być wyświetlany poziomy pasek podziałnika. Poziomy pasek podziałnika oddziela slajd od obszaru zawartości znajdującego się pod slajdem.

**Zwraca:**
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Określa stan, w jakim powinien być wyświetlany poziomy pasek podziałnika. Poziomy pasek podziałnika oddziela slajd od obszaru zawartości znajdującego się pod slajdem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Określa, czy użytkownik preferuje wyświetlanie jednego obszaru zawartości w pełnym oknie zamiast standardowego normalnego widoku z trzema obszarami zawartości. Jeśli włączona, aplikacja może wybrać wyświetlenie jednego z obszarów w całym oknie. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Określa, czy użytkownik preferuje wyświetlanie jednego obszaru zawartości w pełnym oknie zamiast standardowego normalnego widoku z trzema obszarami zawartości. Jeśli włączona, aplikacja może wybrać wyświetlenie jednego z obszarów w całym oknie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Ten element określa rozmiar bocznego obszaru zawartości normalnego widoku, gdy obszar ma zmienny przywrócony rozmiar (niezminimalizowany ani nie zmaksymalizowany). Tylko do odczytu [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Zwraca:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Ten element określa rozmiar górnego obszaru slajdu normalnego widoku, gdy obszar ma zmienny przywrócony rozmiar (niezminimalizowany ani nie zmaksymalizowany). Tylko do odczytu [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Zwraca:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)