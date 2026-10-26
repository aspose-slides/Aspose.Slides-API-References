---
title: DataLabel
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een reeks labels voor.
type: docs
url: /nl/com.aspose.slides/datalabel/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Stelt een reeks labels voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Creëert een nieuw exemplaar van de DataLabel-klasse. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Retourneert het bovenliggende diagram. |
| [isVisible()](#isVisible--) | false betekent dat het label niet zichtbaar is (en dus alle Show\*-vlaggen (ShowValue, …) onwaar zijn). |
| [hide()](#hide--) | Verberg het label door alle Show\*-vlaggen (ShowValue, …) op onwaar te zetten. |
| [getActualLabelText()](#getActualLabelText--) | Retourneert de werkelijke labeltekst op basis van DataLabelFormat-instellingen of TextFrameForOverriding.Text-waarde. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialiseert TextFrameForOverriding met de tekst in parameter “text”. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Kan een rijk opgemaakte tekst bevatten. |
| [getTextFormat()](#getTextFormat--) | Retourneert tekstopmaak. |
| [getX()](#getX--) | Retourneert of stelt de x-coördinaat van een titel in als een fractie van de breedte van het diagram. |
| [setX(float value)](#setX-float-) | Retourneert of stelt de x-coördinaat van een titel in als een fractie van de breedte van het diagram. |
| [getY()](#getY--) | Retourneert of stelt de y-coördinaat van een titel in als een fractie van de hoogte van het diagram. |
| [setY(float value)](#setY-float-) | Retourneert of stelt de y-coördinaat van een titel in als een fractie van de hoogte van het diagram. |
| [getWidth()](#getWidth--) | Retourneert of stelt de breedte van een titel in als een fractie van de breedte van het diagram. |
| [setWidth(float value)](#setWidth-float-) | Retourneert of stelt de breedte van een titel in als een fractie van de breedte van het diagram. |
| [getHeight()](#getHeight--) | Retourneert of stelt de hoogte van een titel in als een fractie van de hoogte van het diagram. |
| [setHeight(float value)](#setHeight-float-) | Retourneert of stelt de hoogte van een titel in als een fractie van de hoogte van het diagram. |
| [getRight()](#getRight--) | Rechts. |
| [getBottom()](#getBottom--) | Onderkant. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Retourneert labelopmaak. |
| [getValueFromCell()](#getValueFromCell--) | Haalt of stelt workbook-datacel in. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Haalt of stelt workbook-datacel in. |
| [getActualX()](#getActualX--) | Specificeert de feitelijke x-locatie (links) van het diagram-element ten opzichte van de linkerbovenhoek van het diagram. |
| [getActualY()](#getActualY--) | Specificeert de feitelijke bovenkant van het diagram-element ten opzichte van de linkerbovenhoek van het diagram. |
| [getActualWidth()](#getActualWidth--) | Specificeert de feitelijke breedte van het diagram-element. |
| [getActualHeight()](#getActualHeight--) | Specificeert de feitelijke hoogte van het diagram-element. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een FillFormat. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Creëert een nieuw exemplaar van de DataLabel-klasse.

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

Retourneert het bovenliggende diagram. Alleen-lezen [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

false betekent dat het label niet zichtbaar is (en dus alle Show\*-vlaggen (ShowValue, …) onwaar zijn). Alleen-lezen boolean.

--------------------

Als het label zichtbaar is, kun je het verbergen met de hide()-methode. Maar als het label niet zichtbaar is (IsVisible is false), kun je het zichtbaar maken door de Show\*-vlaggen (ShowValue, …) op waar te zetten.

**Returns:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Verberg het label door alle Show\*-vlaggen (ShowValue, …) op onwaar te zetten. IsVisible zal daarna false zijn.

--------------------

Als het label niet zichtbaar is (IsVisible is false), kun je het zichtbaar maken door de Show\*-vlaggen (ShowValue, …) op waar te zetten.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Retourneert de feitelijke labeltekst op basis van DataLabelFormat-instellingen of TextFrameForOverriding.Text-waarde.

**Returns:**
java.lang.String - Het java.lang.String-object.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Initialiseert TextFrameForOverriding met de tekst in parameter “text”. Als TextFrameForOverriding al is geïnitialiseerd, wordt gewoon de tekst aangepast.

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

Kan een rijk opgemaakte tekst bevatten. Als deze eigenschap niet null is, dan overschrijft deze opgemaakte tekst de automatisch gegenereerde tekst van het label. Automatisch gegenereerde tekst van het label betekent tekst die wordt beheerd door ShowSeriesName, ShowValue, …-eigenschappen en wordt opgemaakt met de TextFormatManager.TextFormat-eigenschap. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

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

Retourneert of stelt de x-coördinaat van een titel in als een fractie van de breedte van het diagram. Lezen/Schrijven float.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Retourneert of stelt de x-coördinaat van een titel in als een fractie van de breedte van het diagram. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Retourneert of stelt de y-coördinaat van een titel in als een fractie van de hoogte van het diagram. Lezen/Schrijven float.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Retourneert of stelt de y-coördinaat van een titel in als een fractie van de hoogte van het diagram. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Retourneert of stelt de breedte van een titel in als een fractie van de breedte van het diagram. Lezen/Schrijven float.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Retourneert of stelt de breedte van een titel in als een fractie van de breedte van het diagram. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Retourneert of stelt de hoogte van een titel in als een fractie van de hoogte van het diagram. Lezen/Schrijven float.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Retourneert of stelt de hoogte van een titel in als een fractie van de hoogte van het diagram. Lezen/Schrijven float.

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

Retourneert labelopmaak. Alleen-lezen [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returns:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Haalt of stelt workbook-datacel in. Toegepast als IDataLabelFormat.ShowLabelValueFromCell-eigenschap true is.

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Haalt of stelt workbook-datacel in. Toegepast als IDataLabelFormat.ShowLabelValueFromCell-eigenschap true is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Specificeert de feitelijke x-locatie (links) van het diagram-element ten opzichte van de linkerbovenhoek van het diagram. Roep IChart.ValidateChartLayout() aan vóór het verkrijgen van de feitelijke waarden. Alleen-lezen float.

**Returns:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Specificeert de feitelijke bovenkant van het diagram-element ten opzichte van de linkerbovenhoek van het diagram. Roep IChart.ValidateChartLayout() aan vóór het verkrijgen van de feitelijke waarden. Alleen-lezen float.

**Returns:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Specificeert de feitelijke breedte van het diagram-element. Roep IChart.ValidateChartLayout() aan vóór het verkrijgen van de feitelijke waarden. Alleen-lezen float.

**Returns:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Specificeert de feitelijke hoogte van het diagram-element. Roep IChart.ValidateChartLayout() aan vóór het verkrijgen van de feitelijke waarden. Alleen-lezen float.

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