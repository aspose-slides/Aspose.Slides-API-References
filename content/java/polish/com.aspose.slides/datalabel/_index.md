---
title: DataLabel
second_title: Aspose.Slides dla Java - odniesienie API
description: Reprezentuje etykiety serii.
type: docs
url: /pl/com.aspose.slides/datalabel/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Reprezentuje etykiety serii.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Utworzy nową instancję klasy DataLabel. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Zwraca wykres nadrzędny. |
| [isVisible()](#isVisible--) | False oznacza, że etykieta danych nie jest widoczna (i tak więc wszystkie flagi Show\*- (ShowValue, ...) są false). |
| [hide()](#hide--) | Ukryj etykietę danych, ustawiając wszystkie flagi Show\*- (ShowValue, ...) na stan false. |
| [getActualLabelText()](#getActualLabelText--) | Zwraca rzeczywisty tekst etykiety na podstawie ustawień DataLabelFormat lub wartości TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicjalizuje TextFrameForOverriding przy użyciu tekstu w parametrze "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Może zawierać tekst sformatowany bogato. |
| [getTextFormat()](#getTextFormat--) | Zwraca format tekstu. |
| [getX()](#getX--) | Zwraca lub ustawia współrzędną x tytułu jako ułamek szerokości wykresu. |
| [setX(float value)](#setX-float-) | Zwraca lub ustawia współrzędną x tytułu jako ułamek szerokości wykresu. |
| [getY()](#getY--) | Zwraca lub ustawia współrzędną y tytułu jako ułamek wysokości wykresu. |
| [setY(float value)](#setY-float-) | Zwraca lub ustawia współrzędną y tytułu jako ułamek wysokości wykresu. |
| [getWidth()](#getWidth--) | Zwraca lub ustawia szerokość tytułu jako ułamek szerokości wykresu. |
| [setWidth(float value)](#setWidth-float-) | Zwraca lub ustawia szerokość tytułu jako ułamek szerokości wykresu. |
| [getHeight()](#getHeight--) | Zwraca lub ustawia wysokość tytułu jako ułamek wysokości wykresu. |
| [setHeight(float value)](#setHeight-float-) | Zwraca lub ustawia wysokość tytułu jako ułamek wysokości wykresu. |
| [getRight()](#getRight--) | Prawo. |
| [getBottom()](#getBottom--) | Dół. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Zwraca format etykiety danych. |
| [getValueFromCell()](#getValueFromCell--) | Pobiera lub ustawia komórkę danych skoroszytu. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Pobiera lub ustawia komórkę danych skoroszytu. |
| [getActualX()](#getActualX--) | Określa rzeczywistą pozycję x (lewo) elementu wykresu względem lewego górnego rogu wykresu. |
| [getActualY()](#getActualY--) | Określa rzeczywistą górę elementu wykresu względem lewego górnego rogu wykresu. |
| [getActualWidth()](#getActualWidth--) | Określa rzeczywistą szerokość elementu wykresu. |
| [getActualHeight()](#getActualHeight--) | Określa rzeczywistą wysokość elementu wykresu. |
| [getSlide()](#getSlide--) | Zwraca slajd nadrzędny FillFormat. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację nadrzędną FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Utworzy nową instancję klasy DataLabel.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Nadrzędny ChartDataPoint. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Zwraca wykres nadrzędny. Tylko do odczytu [IChart](../../com.aspose.slides/ichart).

**Zwraca:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False oznacza, że etykieta danych nie jest widoczna (i wszystkie flagi Show\*- (ShowValue, ...) są false). Tylko do odczytu boolean.

--------------------

Jeśli etykieta danych jest widoczna, możesz ją ukryć metodą Hide(). Jeśli etykieta danych nie jest widoczna (IsVisible jest false), możesz ją zrobić widoczną, ustawiając flagi Show\*- (ShowValue, ...) na stan true.

**Zwraca:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Ukrywa etykietę danych, ustawiając wszystkie flagi Show\*- (ShowValue, ...) na stan false. Po tym IsVisible będzie false.

--------------------

Jeśli etykieta danych nie jest widoczna (IsVisible jest false), możesz ją zrobić widoczną, ustawiając flagi Show\*- (ShowValue, ...) na stan true.
### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Zwraca rzeczywisty tekst etykiety na podstawie ustawień DataLabelFormat lub wartości TextFrameForOverriding.Text.

**Zwraca:**
java.lang.String - Obiekt java.lang.String.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inicjalizuje TextFrameForOverriding przy użyciu tekstu w parametrze "text". Jeśli TextFrameForOverriding jest już zainicjowany, po prostu zmienia jego tekst.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst dla nowego TextFrameForOverriding. |

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Może zawierać bogato sformatowany tekst. Jeśli ta właściwość nie jest nullem, wartość tego sformatowanego tekstu zastępuje automatycznie generowany tekst etykiety danych. Automatycznie generowany tekst etykiety danych oznacza tekst zarządzany przez właściwości ShowSeriesName, ShowValue, ... i formatowany przy użyciu właściwości TextFormatManager.TextFormat. Tylko do odczytu [ITextFrame](../../com.aspose.slides/itextframe).

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Zwraca format tekstu. Tylko do odczytu [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Zwraca:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Zwraca lub ustawia współrzędną x tytułu jako ułamek szerokości wykresu. Odczyt/zapis float.

**Zwraca:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Zwraca lub ustawia współrzędną x tytułu jako ułamek szerokości wykresu. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Zwraca lub ustawia współrzędną y tytułu jako ułamek wysokości wykresu. Odczyt/zapis float.

**Zwraca:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Zwraca lub ustawia współrzędną y tytułu jako ułamek wysokości wykresu. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Zwraca lub ustawia szerokość tytułu jako ułamek szerokości wykresu. Odczyt/zapis float.

**Zwraca:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Zwraca lub ustawia szerokość tytułu jako ułamek szerokości wykresu. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Zwraca lub ustawia wysokość tytułu jako ułamek wysokości wykresu. Odczyt/zapis float.

**Zwraca:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Zwraca lub ustawia wysokość tytułu jako ułamek wysokości wykresu. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

Prawo. Tylko do odczytu float.

**Zwraca:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Dół. Tylko do odczytu float.

**Zwraca:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Zwraca format etykiety danych. Tylko do odczytu [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Zwraca:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Pobiera lub ustawia komórkę danych skoroszytu. Zastosowane, jeśli właściwość IDataLabelFormat.ShowLabelValueFromCell jest równa true.

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Pobiera lub ustawia komórkę danych skoroszytu. Zastosowane, jeśli właściwość IDataLabelFormat.ShowLabelValueFromCell jest równa true.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Określa rzeczywistą pozycję x (lewo) elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed uzyskaniem rzeczywistych wartości. Tylko do odczytu float.

**Zwraca:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Określa rzeczywistą górę elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed uzyskaniem rzeczywistych wartości. Tylko do odczytu float.

**Zwraca:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Określa rzeczywistą szerokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed uzyskaniem rzeczywistych wartości. Tylko do odczytu float.

**Zwraca:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Określa rzeczywistą wysokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed uzyskaniem rzeczywistych wartości. Tylko do odczytu float.

**Zwraca:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Zwraca slajd nadrzędny FillFormat. Tylko do odczytu [BaseSlide](../../com.aspose.slides/baseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca prezentację nadrzędną FillFormat. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)