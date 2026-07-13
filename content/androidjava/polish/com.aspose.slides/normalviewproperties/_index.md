---
title: NormalViewProperties
second_title: Aspose.Slides dla Androida – odniesienie do Java API
description: Reprezentuje właściwości normalnego widoku.
type: docs
url: /pl/com.aspose.slides/normalviewproperties/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

Reprezentuje właściwości normalnego widoku. Normalny widok składa się z trzech obszarów treści: samego slajdu, bocznego obszaru treści oraz dolnego obszaru treści.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Instancjonuj obiekt prezentacji reprezentujący plik prezentacji
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

## Metody

| Metoda | Opis |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Określa, czy aplikacja powinna wyświetlać ikony przy wyświetlaniu treści konspektu w którymkolwiek z obszarów treści trybu normalnego widoku. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Określa, czy aplikacja powinna wyświetlać ikony przy wyświetlaniu treści konspektu w którymkolwiek z obszarów treści trybu normalnego widoku. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Określa, czy pionowy podziałka powinna przełączać się do stanu zminimalizowanego, gdy boczny obszar jest wystarczająco mały. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Określa, czy pionowy podziałka powinna przełączać się do stanu zminimalizowanego, gdy boczny obszar jest wystarczająco mały. |
| [getVerticalBarState()](#getVerticalBarState--) | Określa stan, w jakim powinna być wyświetlana pionowa belka podziałki. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Określa stan, w jakim powinna być wyświetlana pionowa belka podziałki. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Określa stan, w jakim powinna być wyświetlana pozioma belka podziałki. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Określa stan, w jakim powinna być wyświetlana pozioma belka podziałki. |
| [getPreferSingleView()](#getPreferSingleView--) | Określa, czy użytkownik preferuje widok pełnoekranowy z jednym obszarem treści zamiast standardowego normalnego widoku z trzema obszarami treści. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Określa, czy użytkownik preferuje widok pełnoekranowy z jednym obszarem treści zamiast standardowego normalnego widoku z trzema obszarami treści. |
| [getRestoredLeft()](#getRestoredLeft--) | Ten element określa rozmiar bocznego obszaru treści normalnego widoku, gdy obszar ma zmienny przywrócony rozmiar (niezminimalizowany ani zmaksymalizowany). |
| [getRestoredTop()](#getRestoredTop--) | Ten element określa rozmiar górnego obszaru slajdu normalnego widoku, gdy obszar ma zmienny przywrócony rozmiar (niezminimalizowany ani zmaksymalizowany). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Określa, czy aplikacja powinna wyświetlać ikony przy wyświetlaniu treści konspektu w którymkolwiek z obszarów treści trybu normalnego widoku. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Określa, czy aplikacja powinna wyświetlać ikony przy wyświetlaniu treści konspektu w którymkolwiek z obszarów treści trybu normalnego widoku. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Określa, czy pionowy podziałka powinna przełączać się do stanu zminimalizowanego, gdy boczny obszar jest wystarczająco mały. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Określa, czy pionowy podziałka powinna przełączać się do stanu zminimalizowanego, gdy boczny obszar jest wystarczająco mały. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Określa stan, w jakim powinna być wyświetlana pionowa belka podziałki. Pionowa belka podziałki oddziela slajd od bocznego obszaru treści.

**Zwraca:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Określa stan, w jakim powinna być wyświetlana pionowa belka podziałki. Pionowa belka podziałki oddziela slajd od bocznego obszaru treści.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Określa stan, w jakim powinna być wyświetlana pozioma belka podziałki. Pozioma belka podziałki oddziela slajd od obszaru treści pod slajdem.

**Zwraca:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Określa stan, w jakim powinna być wyświetlana pozioma belka podziałki. Pozioma belka podziałki oddziela slajd od obszaru treści pod slajdem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Określa, czy użytkownik preferuje widok pełnoekranowy z jednym obszarem treści zamiast standardowego normalnego widoku z trzema obszarami treści. Jeśli włączone, aplikacja może wyświetlić jeden z obszarów treści w całym oknie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Określa, czy użytkownik preferuje widok pełnoekranowy z jednym obszarem treści zamiast standardowego normalnego widoku z trzema obszarami treści. Jeśli włączone, aplikacja może wyświetlić jeden z obszarów treści w całym oknie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Ten element określa rozmiar bocznego obszaru treści normalnego widoku, gdy obszar ma zmienny przywrócony rozmiar (niezminimalizowany ani zmaksymalizowany). Tylko do odczytu [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Zwraca:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Ten element określa rozmiar górnego obszaru slajdu normalnego widoku, gdy obszar ma zmienny przywrócony rozmiar (niezminimalizowany ani zmaksymalizowany). Tylko do odczytu [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Zwraca:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)