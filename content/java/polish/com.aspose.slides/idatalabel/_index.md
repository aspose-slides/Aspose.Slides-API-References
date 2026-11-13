---
title: IDataLabel
second_title: Aspose.Slides dla Java – Dokumentacja API
description: Reprezentuje etykiety serii.
type: docs
url: /pl/com.aspose.slides/idatalabel/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Reprezentuje etykiety serii.
## Metody

| Metoda | Opis |
| --- | --- |
| [isVisible()](#isVisible--) | False oznacza, że etykieta danych nie jest widoczna (a więc wszystkie flagi Show*- (ShowValue, ...) mają wartość false). |
| [hide()](#hide--) | Ukryj etykietę danych, ustawiając wszystkie flagi Show*- (ShowValue, ...) w stan false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Zwraca format etykiety danych. |
| [getValueFromCell()](#getValueFromCell--) | Pobiera lub ustawia komórkę danych skoroszytu. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Pobiera lub ustawia komórkę danych skoroszytu. |
| [getActualLabelText()](#getActualLabelText--) | Zwraca rzeczywisty tekst etykiety na podstawie ustawień DataLabelFormat lub wartości TextFrameForOverriding.Text. |
| [getLabelShapeType()](#getLabelShapeType--) | Pobiera lub ustawia typ kształtu etykiety danych. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Pobiera lub ustawia typ kształtu etykiety danych. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False oznacza, że etykieta danych nie jest widoczna (a więc wszystkie flagi Show*- (ShowValue, ...) są false). Tylko do odczytu boolean.

--------------------

Jeśli etykieta danych jest widoczna, możesz ją ukryć metodą Hide(). Jednak jeśli etykieta danych nie jest widoczna (IsVisible jest false), możesz ją uczynić widoczną, ustawiając flagi Show*- (ShowValue, ...) w stan true.

**Zwraca:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Ukryj etykietę danych, ustawiając wszystkie flagi Show*- (ShowValue, ...) w stan false. IsVisible będzie false po wykonaniu tej operacji.

--------------------

Jeśli etykieta danych nie jest widoczna (IsVisible jest false), możesz uczynić ją widoczną, ustawiając flagi Show*- (ShowValue, ...) w stan true.

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

Pobiera lub ustawia komórkę danych skoroszytu. Stosowane, jeśli właściwość IDataLabelFormat.ShowLabelValueFromCell ma wartość true.

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Pobiera lub ustawia komórkę danych skoroszytu. Stosowane, jeśli właściwość IDataLabelFormat.ShowLabelValueFromCell ma wartość true.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Zwraca rzeczywisty tekst etykiety na podstawie ustawień DataLabelFormat lub wartości TextFrameForOverriding.Text.

**Zwraca:**
java.lang.String - Rzeczywisty tekst etykiety String
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

Pobiera lub ustawia typ kształtu etykiety danych. Zwraca [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) jeśli nie zdefiniowano kształtu.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Ustaw typ kształtu pierwszej etykiety danych na Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

Pobiera lub ustawia typ kształtu etykiety danych. Zwraca [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) jeśli nie zdefiniowano kształtu.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Ustaw typ kształtu pierwszej etykiety danych na Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |   |