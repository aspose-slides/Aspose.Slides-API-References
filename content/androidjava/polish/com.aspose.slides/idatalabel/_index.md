---
title: IDataLabel
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje etykiety serii.
type: docs
url: /pl/com.aspose.slides/idatalabel/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Reprezentuje etykiety serii.
## Metody

| Metoda | Opis |
| --- | --- |
| [isVisible()](#isVisible--) | False oznacza, że etykieta danych nie jest widoczna (i wszystkie flagi Show*-flags (ShowValue, ...) są false). |
| [hide()](#hide--) | Ukryj etykietę danych, ustawiając wszystkie flagi Show*-flags (ShowValue, ...) w stan false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Zwraca format etykiety danych. |
| [getValueFromCell()](#getValueFromCell--) | Pobiera lub ustawia komórkę danych skoroszytu. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Pobiera lub ustawia komórkę danych skoroszytu. |
| [getActualLabelText()](#getActualLabelText--) | Zwraca rzeczywisty tekst etykiety na podstawie ustawień DataLabelFormat lub wartości TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False oznacza, że etykieta danych nie jest widoczna (i wszystkie flagi Show*-flags (ShowValue, ...) są false). Tylko do odczytu boolean.

--------------------

Jeśli etykieta danych jest widoczna, możesz ją ukryć metodą Hide(). Jednak jeśli etykieta danych nie jest widoczna (IsVisible jest false), możesz ją uczynić widoczną, ustawiając flagi Show*-flags (ShowValue, ...) w stan true.

**Zwraca:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Ukryj etykietę danych, ustawiając wszystkie flagi Show*-flags (ShowValue, ...) w stan false. IsVisible będzie po tym false.

--------------------

Jeśli etykieta danych nie jest widoczna (IsVisible jest false), możesz ją uczynić widoczną, ustawiając flagi Show*-flags (ShowValue, ...) w stan true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Zwraca format etykiety danych. Tylko do odczytu [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Zwraca:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Pobiera lub ustawia komórkę danych skoroszytu. Stosowane, jeśli własność IDataLabelFormat.ShowLabelValueFromCell jest równa true.

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Pobiera lub ustawia komórkę danych skoroszytu. Stosowane, jeśli własność IDataLabelFormat.ShowLabelValueFromCell jest równa true.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Zwraca rzeczywisty tekst etykiety na podstawie ustawień DataLabelFormat lub wartości TextFrameForOverriding.Text.

**Zwraca:**
java.lang.String - Rzeczywisty tekst etykiety String