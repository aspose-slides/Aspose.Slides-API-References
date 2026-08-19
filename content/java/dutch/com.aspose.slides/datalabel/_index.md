---
title: DataLabel
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een reekslabels voor.
type: docs
url: /nl/com.aspose.slides/datalabel/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Stelt een reekslabels voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Maakt een nieuw exemplaar van de DataLabel-klasse aan. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Retourneert de bovenliggende grafiek. |
| [isVisible()](#isVisible--) | False betekent dat gegevenslabel niet zichtbaar is (en dus alle Show\*-flags (ShowValue, ...) onwaar zijn). |
| [hide()](#hide--) | Verberg het gegevenslabel door alle Show\*-flags (ShowValue, ...) op onwaar te zetten. |
| [getActualLabelText()](#getActualLabelText--) | Retourneert de daadwerkelijke labeltekst op basis van DataLabelFormat-instellingen of de waarde van TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialiseert TextFrameForOverriding met de tekst in parameter "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Kan een rijk opgemaakte tekst bevatten. |
| [getTextFormat()](#getTextFormat--) | Retourneert tekstopmaak. |
| [getX()](#getX--) | Retourneert of stelt de x-coördinaat van een titel in als een fractie van de breedte van de grafiek. |
| [setX(float value)](#setX-float-) | Retourneert of stelt de x-coördinaat van een titel in als een fractie van de breedte van de grafiek. |
| [getY()](#getY--) | Retourneert of stelt de y-coördinaat van een titel in als een fractie van de hoogte van de grafiek. |
| [setY(float value)](#setY-float-) | Retourneert of stelt de y-coördinaat van een titel in als een fractie van de hoogte van de grafiek. |
| [getWidth()](#getWidth--) | Retourneert of stelt de breedte van een titel in als een fractie van de breedte van de grafiek. |
| [setWidth(float value)](#setWidth-float-) | Retourneert of stelt de breedte van een titel in als een fractie van de breedte van de grafiek. |
| [getHeight()](#getHeight--) | Retourneert of stelt de hoogte van een titel in als een fractie van de hoogte van de grafiek. |
| [setHeight(float value)](#setHeight-float-) | Retourneert of stelt de hoogte van een titel in als een fractie van de hoogte van de grafiek. |
| [getRight()](#getRight--) | Rechts. |
| [getBottom()](#getBottom--) | Onder. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Retourneert gegevenslabelopmaak. |
| [getValueFromCell()](#getValueFromCell--) | Haalt op of stelt werkboekdatacel in. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Haalt op of stelt werkboekdatacel in. |
| [getActualX()](#getActualX--) | Specificeert de werkelijke x-locatie (links) van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek. |
| [getActualY()](#getActualY--) | Specificeert de werkelijke bovenkant van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek. |
| [getActualWidth()](#getActualWidth--) | Specificeert de werkelijke breedte van het grafiekelement. |
| [getActualHeight()](#getActualHeight--) | Specificeert de werkelijke hoogte van het grafiekelement. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een FillFormat. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een FillFormat. |
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

Retourneert Parent_Immediate-object. Alleen-lezen IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Retourneert de bovenliggende grafiek. Alleen-lezen [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False betekent dat het gegevenslabel niet zichtbaar is (en dus alle Show*-flags (ShowValue, ...) onwaar zijn). Alleen-lezen boolean.

--------------------

Als het gegevenslabel zichtbaar is, kun je het verbergen met de Hide()-methode. Maar als het gegevenslabel niet zichtbaar is (IsVisible is false), kun je het zichtbaar maken door de Show*-flags (ShowValue, ...) op true te zetten.

**Returns:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Verberg het gegevenslabel door alle Show*-flags (ShowValue, ...) op false te zetten. IsVisible zal daarna false zijn.

--------------------

Als het gegevenslabel niet zichtbaar is (IsVisible is false), kun je het zichtbaar maken door de Show*-flags (ShowValue, ...) op true te zetten.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Retourneert de daadwerkelijke labeltekst op basis van DataLabelFormat-instellingen of de waarde van TextFrameForOverriding.Text.

**Returns:**
java.lang.String - The java.lang.String object.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Initialiseert TextFrameForOverriding met de tekst in parameter "text". Als TextFrameForOverriding al geïnitialiseerd is, verandert alleen de tekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst voor een nieuw TextFrameForOverriding. |

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Kan een rijk opgemaakte tekst bevatten. Als deze eigenschap niet null is, dan overschrijft deze opgemaakte tekst de automatisch gegenereerde tekst van het gegevenslabel. Automatisch gegenereerde tekst van het gegevenslabel betekent tekst die wordt beheerd door de ShowSeriesName, ShowValue, ...-eigenschappen en wordt opgemaakt met de TextFormatManager.TextFormat-eigenschap. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Retourneert tekstopmaak. Alleen-lezen [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returns:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Retourneert of stelt de x-coördinaat van een titel in als een fractie van de breedte van de grafiek. Lezen/schrijven float .

**Returns:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Retourneert of stelt de x-coördinaat van een titel in als een fractie van de breedte van de grafiek. Lezen/schrijven float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Retourneert of stelt de y-coördinaat van een titel in als een fractie van de hoogte van de grafiek. Lezen/schrijven float .

**Returns:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Retourneert of stelt de y-coördinaat van een titel in als een fractie van de hoogte van de grafiek. Lezen/schrijven float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Retourneert of stelt de breedte van een titel in als een fractie van de breedte van de grafiek. Lezen/schrijven float .

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Retourneert of stelt de breedte van een titel in als een fractie van de breedte van de grafiek. Lezen/schrijven float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Retourneert of stelt de hoogte van een titel in als een fractie van de hoogte van de grafiek. Lezen/schrijven float .

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Retourneert of stelt de hoogte van een titel in als een fractie van de hoogte van de grafiek. Lezen/schrijven float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

Rechts. Alleen-lezen float .

**Returns:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Onder. Alleen-lezen float .

**Returns:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Retourneert gegevenslabelopmaak. Alleen-lezen [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returns:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Haalt op of stelt werkboekdatacel in. Toegepast als IDataLabelFormat.ShowLabelValueFromCell-eigenschap true is.

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Haalt op of stelt werkboekdatacel in. Toegepast als IDataLabelFormat.ShowLabelValueFromCell-eigenschap true is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Specificeert de werkelijke x-locatie (links) van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek. Roep methode IChart.ValidateChartLayout() aan vóór het verkrijgen van werkelijke waarden. Alleen float .

**Returns:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Specificeert de werkelijke bovenkant van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek. Roep methode IChart.ValidateChartLayout() aan vóór het verkrijgen van werkelijke waarden. Alleen float .

**Returns:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Specificeert de werkelijke breedte van het grafiekelement. Roep methode IChart.ValidateChartLayout() aan vóór het verkrijgen van werkelijke waarden. Alleen float .

**Returns:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Specificeert de werkelijke hoogte van het grafiekelement. Roep methode IChart.ValidateChartLayout() aan vóór het verkrijgen van werkelijke waarden. Alleen float .

**Returns:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de bovenliggende dia van een FillFormat. Alleen-lezen [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie van een FillFormat. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)