---
title: IDataLabel
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een reeks labels voor.
type: docs
url: /nl/com.aspose.slides/idatalabel/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Stelt een reeks labels voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isVisible()](#isVisible--) | False betekent dat het gegevenslabel niet zichtbaar is (en dus alle Show*-flags (ShowValue, ...) false zijn). |
| [hide()](#hide--) | Verberg het gegevenslabel door alle Show*-flags (ShowValue, ...) op de false-status te zetten. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Geeft het formaat van het gegevenslabel terug. |
| [getValueFromCell()](#getValueFromCell--) | Haalt of stelt de werkmapgegevenscel in. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Haalt of stelt de werkmapgegevenscel in. |
| [getActualLabelText()](#getActualLabelText--) | Geeft de werkelijke labeltekst terug op basis van de DataLabelFormat-instellingen of de TextFrameForOverriding.Text-waarde. |
| [getLabelShapeType()](#getLabelShapeType--) | Haalt of stelt het vormtype van het gegevenslabel in. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Haalt of stelt het vormtype van het gegevenslabel in. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False betekent dat het gegevenslabel niet zichtbaar is (en dus alle Show*-flags (ShowValue, ...) false zijn). Alleen-lezen boolean.

--------------------

Als het gegevenslabel zichtbaar is, kun je het verbergen met de Hide()-methode. Maar als het gegevenslabel niet zichtbaar is (IsVisible is false), kun je het gegevenslabel zichtbaar maken door de Show*-flags (ShowValue, ...) op true te zetten.

**Retour:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Verberg het gegevenslabel door alle Show*-flags (ShowValue, ...) op false te zetten. IsVisible zal daarna false zijn.

--------------------

Als het gegevenslabel niet zichtbaar is (IsVisible is false), kun je het gegevenslabel zichtbaar maken door de Show*-flags (ShowValue, ...) op true te zetten.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Geeft het formaat van het gegevenslabel terug. Alleen-lezen [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Retour:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Haalt of stelt de werkmapgegevenscel in. Toegepast als de eigenschap IDataLabelFormat.ShowLabelValueFromCell true is.

**Retour:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Haalt of stelt de werkmapgegevenscel in. Toegepast als de eigenschap IDataLabelFormat.ShowLabelValueFromCell true is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Geeft de werkelijke labeltekst terug op basis van de DataLabelFormat-instellingen of de TextFrameForOverriding.Text-waarde.

**Retour:**
java.lang.String - Werkelijke labeltekst String
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

Haalt of stelt het vormtype van het gegevenslabel in. Retourneert [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) als er geen vorm is gedefinieerd.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Stel het vormtype van het eerste gegevenslabel in op Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retour:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

Haalt of stelt het vormtype van het gegevenslabel in. Retourneert [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) als er geen vorm is gedefinieerd.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Stel het vormtype van het eerste gegevenslabel in op Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |