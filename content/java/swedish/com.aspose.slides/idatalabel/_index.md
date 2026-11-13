---
title: IDataLabel
second_title: Aspose.Slides för Java API-referens
description: Representerar en serie etiketter.
type: docs
url: /sv/com.aspose.slides/idatalabel/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Representerar en serie etiketter.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isVisible()](#isVisible--) | Falskt betyder att datatetiketten inte är synlig (och att alla Show\*-flaggor (ShowValue, ...) är falska). |
| [hide()](#hide--) | Gör datatetiketten dold genom att sätta alla Show\*-flaggor (ShowValue, ...) till falskt läge. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Returnerar formatet för datatetiketten. |
| [getValueFromCell()](#getValueFromCell--) | Hämtar eller anger arbetsbokens datacell. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Hämtar eller anger arbetsbokens datacell. |
| [getActualLabelText()](#getActualLabelText--) | Returnerar den faktiska etiketttexten baserat på DataLabelFormat-inställningarna eller TextFrameForOverriding.Text-värdet. |
| [getLabelShapeType()](#getLabelShapeType--) | Hämtar eller anger formtypen för datatetiketten. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Hämtar eller anger formtypen för datatetiketten. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Falskt betyder att datatetiketten inte är synlig (och att alla Show\*-flaggor (ShowValue, ...) är falska). **Skrivskyddad** boolean.

--------------------

Om datatetiketten är synlig kan du dölja den med Hide()-metoden. Men om datatetiketten inte är synlig (IsVisible är falskt) kan du göra den synlig genom att sätta Show\*-flaggorna (ShowValue, ...) till sant läge.

**Returnerar:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Gör datatetiketten dold genom att sätta alla Show\*-flaggor (ShowValue, ...) till falskt läge. IsVisible kommer att vara falskt efter detta.

--------------------

Om datatetiketten inte är synlig (IsVisible är falskt) kan du göra den synlig genom att sätta Show\*-flaggorna (ShowValue, ...) till sant läge.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Returnerar formatet för datatetiketten. **Skrivskyddad** [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returnerar:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Hämtar eller anger arbetsbokens datacell. Tillämpas om egenskapen IDataLabelFormat.ShowLabelValueFromCell är sann.

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Hämtar eller anger arbetsbokens datacell. Tillämpas om egenskapen IDataLabelFormat.ShowLabelValueFromCell är sann.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Returnerar den faktiska etiketttexten baserat på DataLabelFormat-inställningarna eller TextFrameForOverriding.Text-värdet.

**Returnerar:**
java.lang.String - Faktisk etiketttext String
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

Hämtar eller anger formtypen för datatetiketten. Returnerar [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) om ingen form är definierad.

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Ange formtypen för den första datatetiketten till Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

Hämtar eller anger formtypen för datatetiketten. Returnerar [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) om ingen form är definierad.

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Ange formtypen för den första datatetiketten till Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |