---
title: NormalViewProperties
second_title: Aspose.Slides dla Java – odniesienie API
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

Reprezentuje właściwości normalnego widoku. Normalny widok składa się z trzech obszarów zawartości: samego slajdu, bocznego obszaru zawartości oraz dolnego obszaru zawartości.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Utwórz obiekt prezentacji, który reprezentuje plik prezentacji
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
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Określa, czy aplikacja ma wyświetlać ikony podczas wyświetlania zarysu treści w którymkolwiek z obszarów zawartości trybu normalnego widoku. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Określa, czy aplikacja ma wyświetlać ikony podczas wyświetlania zarysu treści w którymkolwiek z obszarów zawartości trybu normalnego widoku. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Określa, czy pionowy dzielnik powinien przyczepić się do stanu zminimalizowanego, gdy boczny obszar jest wystarczająco mały. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Określa, czy pionowy dzielnik powinien przyczepić się do stanu zminimalizowanego, gdy boczny obszar jest wystarczająco mały. |
| [getVerticalBarState()](#getVerticalBarState--) | Określa stan, w którym powinien być wyświetlany pionowy pasek dzielnika. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Określa stan, w którym powinien być wyświetlany pionowy pasek dzielnika. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Określa stan, w którym powinien być wyświetlany poziomy pasek dzielnika. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Określa stan, w którym powinien być wyświetlany poziomy pasek dzielnika. |
| [getPreferSingleView()](#getPreferSingleView--) | Określa, czy użytkownik woli widzieć pojedynczy region zawartości na pełnym ekranie zamiast standardowego normalnego widoku z trzema regionami zawartości. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Określa, czy użytkownik woli widzieć pojedynczy region zawartości na pełnym ekranie zamiast standardowego normalnego widoku z trzema regionami zawartości. |
| [getRestoredLeft()](#getRestoredLeft--) | Ten element określa rozmiar bocznego regionu zawartości normalnego widoku, gdy region ma zmienny przywrócony rozmiar (niezminimalizowany ani niezmaksymalizowany). |
| [getRestoredTop()](#getRestoredTop--) | Ten element określa rozmiar górnego regionu slajdu w normalnym widoku, gdy region ma zmienny przywrócony rozmiar (niezminimalizowany ani niezmaksymalizowany). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Określa, czy aplikacja ma wyświetlać ikony podczas wyświetlania zarysu treści w którymkolwiek z obszarów zawartości trybu normalnego widoku. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Określa, czy aplikacja ma wyświetlać ikony podczas wyświetlania zarysu treści w którymkolwiek z obszarów zawartości trybu normalnego widoku. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Określa, czy pionowy dzielnik powinien przyczepić się do stanu zminimalizowanego, gdy boczny obszar jest wystarczająco mały. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Określa, czy pionowy dzielnik powinien przyczepić się do stanu zminimalizowanego, gdy boczny obszar jest wystarczająco mały. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Określa stan, w którym powinien być wyświetlany pionowy pasek dzielnika. Pionowy pasek dzielnika oddziela slajd od bocznego regionu zawartości.

**Zwraca:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Określa stan, w którym powinien być wyświetlany pionowy pasek dzielnika. Pionowy pasek dzielnika oddziela slajd od bocznego regionu zawartości.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Określa stan, w którym powinien być wyświetlany poziomy pasek dzielnika. Poziomy pasek dzielnika oddziela slajd od regionu zawartości pod slajdem.

**Zwraca:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Określa stan, w którym powinien być wyświetlany poziomy pasek dzielnika. Poziomy pasek dzielnika oddziela slajd od regionu zawartości pod slajdem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Określa, czy użytkownik woli widzieć pojedynczy region zawartości na pełnym ekranie zamiast standardowego normalnego widoku z trzema regionami zawartości. Jeśli włączone, aplikacja może wyświetlić jeden z regionów zawartości na całym oknie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Określa, czy użytkownik woli widzieć pojedynczy region zawartości na pełnym ekranie zamiast standardowego normalnego widoku z trzema regionami zawartości. Jeśli włączone, aplikacja może wyświetlić jeden z regionów zawartości na całym oknie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Ten element określa rozmiar bocznego regionu zawartości normalnego widoku, gdy region ma zmienny przywrócony rozmiar (niezminimalizowany ani niezmaksymalizowany). Tylko do odczytu [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Zwraca:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Ten element określa rozmiar górnego regionu slajdu w normalnym widoku, gdy region ma zmienny przywrócony rozmiar (niezminimalizowany ani niezmaksymalizowany). Tylko do odczytu [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Zwraca:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)