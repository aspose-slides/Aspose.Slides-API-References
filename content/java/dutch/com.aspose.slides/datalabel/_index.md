---
title: DataLabel
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een reekslabels voor.
type: docs
url: /nl/com.aspose.slides/datalabel/
---
**Erfelijkheid:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Stelt een reekslabels voor.
## Constructeurs

| Constructor | Beschrijving |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Maakt een nieuw exemplaar van de DataLabel-klasse aan. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Geeft de bovenliggende grafiek terug. |
| [isVisible()](#isVisible--) | False betekent dat het gegevenslabel niet zichtbaar is (en daarom zijn alle Show*-vlaggen (ShowValue, ...) onwaar). |
| [hide()](#hide--) | Verberg het gegevenslabel door alle Show*-vlaggen (ShowValue, ...) op false te zetten. |
| [getActualLabelText()](#getActualLabelText--) | Geeft de werkelijke labeltekst terug op basis van de DataLabelFormat-instellingen of de TextFrameForOverriding.Text-waarde. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialiseert TextFrameForOverriding met de tekst in de parameter "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Kan een rijk opgemaakt tekst bevatten. |
| [getTextFormat()](#getTextFormat--) | Geeft het tekstformaat terug. |
| [getX()](#getX--) | Geeft de x-coördinaat van een titel terug of stelt deze in als een fractie van de breedte van de grafiek. |
| [setX(float value)](#setX-float-) | Geeft de x-coördinaat van een titel terug of stelt deze in als een fractie van de breedte van de grafiek. |
| [getY()](#getY--) | Geeft de y-coördinaat van een titel terug of stelt deze in als een fractie van de hoogte van de grafiek. |
| [setY(float value)](#setY-float-) | Geeft de y-coördinaat van een titel terug of stelt deze in als een fractie van de hoogte van de grafiek. |
| [getWidth()](#getWidth--) | Geeft de breedte van een titel terug of stelt deze in als een fractie van de breedte van de grafiek. |
| [setWidth(float value)](#setWidth-float-) | Geeft de breedte van een titel terug of stelt deze in als een fractie van de breedte van de grafiek. |
| [getHeight()](#getHeight--) | Geeft de hoogte van een titel terug of stelt deze in als een fractie van de hoogte van de grafiek. |
| [setHeight(float value)](#setHeight-float-) | Geeft de hoogte van een titel terug of stelt deze in als een fractie van de hoogte van de grafiek. |
| [getRight()](#getRight--) | Rechts. |
| [getBottom()](#getBottom--) | Onderkant. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Geeft het gegevenslabelformaat terug. |
| [getValueFromCell()](#getValueFromCell--) | Haalt op of stelt een werkboekgegevenscel in. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Haalt op of stelt een werkboekgegevenscel in. |
| [getLabelShapeType()](#getLabelShapeType--) | Haalt het vormtype van het gegevenslabel op of stelt het in. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Haalt het vormtype van het gegevenslabel op of stelt het in. |
| [getActualX()](#getActualX--) | Specificeert de werkelijke x-positie (links) van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek. |
| [getActualY()](#getActualY--) | Specificeert de werkelijke bovenkant van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek. |
| [getActualWidth()](#getActualWidth--) | Specificeert de werkelijke breedte van het grafiekelement. |
| [getActualHeight()](#getActualHeight--) | Specificeert de werkelijke hoogte van het grafiekelement. |
| [getSlide()](#getSlide--) | Geeft de bovenliggende dia van een FillFormat terug. |
| [getPresentation()](#getPresentation--) | Geeft de bovenliggende presentatie van een FillFormat terug. |

### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Maakt een nieuw exemplaar van de DataLabel-klasse aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Bovenliggende ChartDataPoint. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Geeft het Parent_Immediate-object terug. Alleen-lezen IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Geeft de bovenliggende grafiek terug. Alleen-lezen [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False betekent dat het gegevenslabel niet zichtbaar is (en daarom alle Show*-vlaggen (ShowValue, ...) onwaar zijn). Alleen-lezen boolean.

---

Als het gegevenslabel zichtbaar is, kun je het verbergen met de Hide()-methode. Maar als het gegevenslabel niet zichtbaar is (IsVisible is false), kun je het gegevenslabel zichtbaar maken door de Show*-vlaggen (ShowValue, ...) op true te zetten.

**Returns:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Verberg het gegevenslabel door alle Show*-vlaggen (ShowValue, ...) op false te zetten. IsVisible zal daarna false zijn.

---

Als het gegevenslabel niet zichtbaar is (IsVisible is false), kun je het gegevenslabel zichtbaar maken door de Show*-vlaggen (ShowValue, ...) op true te zetten.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Geeft de werkelijke labeltekst terug op basis van de DataLabelFormat-instellingen of de TextFrameForOverriding.Text-waarde.

**Returns:**
java.lang.String - The java.lang.String object.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Initialiseert TextFrameForOverriding met de tekst in de parameter "text". Als TextFrameForOverriding al is geïnitialiseerd, verandert de tekst gewoon.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst voor een nieuwe TextFrameForOverriding. |

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Kan een rijk opgemaakte tekst bevatten. Als deze eigenschap niet null is, dan overschrijft deze opgemaakte tekstwaarde de automatisch gegenereerde tekst van het gegevenslabel. Automatisch gegenereerde tekst van het gegevenslabel betekent tekst die wordt beheerd door de eigenschappen ShowSeriesName, ShowValue, ... en wordt opgemaakt met de TextFormatManager.TextFormat-eigenschap. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Geeft tekstformaat terug. Alleen-lezen [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returns:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Geeft de x-coördinaat van een titel terug of stelt deze in als een fractie van de breedte van de grafiek. Lezen/schrijven float.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Geeft de x-coördinaat van een titel terug of stelt deze in als een fractie van de breedte van de grafiek. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Geeft de y-coördinaat van een titel terug of stelt deze in als een fractie van de hoogte van de grafiek. Lezen/schrijven float.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Geeft de y-coördinaat van een titel terug of stelt deze in als een fractie van de hoogte van de grafiek. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Geeft de breedte van een titel terug of stelt deze in als een fractie van de breedte van de grafiek. Lezen/schrijven float.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Geeft de breedte van een titel terug of stelt deze in als een fractie van de breedte van de grafiek. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Geeft de hoogte van een titel terug of stelt deze in als een fractie van de hoogte van de grafiek. Lezen/schrijven float.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Geeft de hoogte van een titel terug of stelt deze in als een fractie van de hoogte van de grafiek. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

Rechts. Alleen-lezen float.

**Returns:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Onderkant. Alleen-lezen float.

**Returns:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Geeft het gegevenslabelformaat terug. Alleen-lezen [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returns:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Haalt de werkboekgegevenscel op of stelt die in. Toegepast indien IDataLabelFormat.ShowLabelValueFromCell-eigenschap true is.

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Haalt de werkboekgegevenscel op of stelt die in. Toegepast indien IDataLabelFormat.ShowLabelValueFromCell-eigenschap true is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```

Haalt het vormtype van het gegevenslabel op of stelt het in. Retourneert [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) als er geen vorm is gedefinieerd.

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


**Returns:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public final void setLabelShapeType(int value)
```

Stelt het vormtype van het gegevenslabel in. Retourneert [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) als er geen vorm is gedefinieerd.

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
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Specificeert de werkelijke x-locatie (links) van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek. Roep methode IChart.ValidateChartLayout() aan voordat u de werkelijke waarden krijgt. Lezen float.

**Returns:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Specificeert de werkelijke bovenkant van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek. Roep methode IChart.ValidateChartLayout() aan voordat u de werkelijke waarden krijgt. Lezen float.

**Returns:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Specificeert de werkelijke breedte van het grafiekelement. Roep methode IChart.ValidateChartLayout() aan voordat u de werkelijke waarden krijgt. Lezen float.

**Returns:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Specificeert de werkelijke hoogte van het grafiekelement. Roep methode IChart.ValidateChartLayout() aan voordat u de werkelijke waarden krijgt. Lezen float.

**Returns:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Geeft de bovenliggende dia van een FillFormat terug. Alleen-lezen [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Geeft de bovenliggende presentatie van een FillFormat terug. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)