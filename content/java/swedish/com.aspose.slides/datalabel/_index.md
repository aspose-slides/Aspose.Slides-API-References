---
title: DataLabel
second_title: Aspose.Slides för Java API-referens
description: Representerar en serieetiketter.
type: docs
url: /sv/com.aspose.slides/datalabel/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Representerar en serieetiketter.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Skapar en ny instans av DataLabel-klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Returnerar föräldrakartan. |
| [isVisible()](#isVisible--) | False betyder att dataetiketten inte är synlig (och därför är alla Show*-flaggor (ShowValue, ...) falska). |
| [hide()](#hide--) | Gör dataetiketten dold genom att sätta alla Show*-flaggor (ShowValue, ...) till falskt läge. |
| [getActualLabelText()](#getActualLabelText--) | Returnerar den faktiska etiketttexten baserat på DataLabelFormat-inställningar eller TextFrameForOverriding.Text-värde. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initierar TextFrameForOverriding med texten i parametern "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Kan innehålla rik formaterad text. |
| [getTextFormat()](#getTextFormat--) | Returnerar textformat. |
| [getX()](#getX--) | Returnerar eller sätter x-koordinaten för en titel som en fraktion av diagrammets bredd. |
| [setX(float value)](#setX-float-) | Returnerar eller sätter x-koordinaten för en titel som en fraktion av diagrammets bredd. |
| [getY()](#getY--) | Returnerar eller sätter y-koordinaten för en titel som en fraktion av diagrammets höjd. |
| [setY(float value)](#setY-float-) | Returnerar eller sätter y-koordinaten för en titel som en fraktion av diagrammets höjd. |
| [getWidth()](#getWidth--) | Returnerar eller sätter bredden på en titel som en fraktion av diagrammets bredd. |
| [setWidth(float value)](#setWidth-float-) | Returnerar eller sätter bredden på en titel som en fraktion av diagrammets bredd. |
| [getHeight()](#getHeight--) | Returnerar eller sätter höjden på en titel som en fraktion av diagrammets höjd. |
| [setHeight(float value)](#setHeight-float-) | Returnerar eller sätter höjden på en titel som en fraktion av diagrammets höjd. |
| [getRight()](#getRight--) | Höger. |
| [getBottom()](#getBottom--) | Botten. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Returnerar dataetikettformat. |
| [getValueFromCell()](#getValueFromCell--) | Hämtar eller sätter arbetsboksdatacell. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Hämtar eller sätter arbetsboksdatacell. |
| [getLabelShapeType()](#getLabelShapeType--) | Hämtar eller sätter formtypen för dataetiketten. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Hämtar eller sätter formtypen för dataetiketten. |
| [getActualX()](#getActualX--) | Anger den faktiska x-positionen (vänster) för diagrammets element relativt diagrammets övre vänstra hörn. |
| [getActualY()](#getActualY--) | Anger den faktiska överkanten för diagrammets element relativt diagrammets övre vänstra hörn. |
| [getActualWidth()](#getActualWidth--) | Anger den faktiska bredden för diagrammets element. |
| [getActualHeight()](#getActualHeight--) | Anger den faktiska höjden för diagrammets element. |
| [getSlide()](#getSlide--) | Returnerar den överordnade bilden för en FillFormat. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen för en FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Skapar en ny instans av DataLabel-klassen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Föräldra-ChartDataPoint. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Returnerar föräldrakartan. Skrivskyddad [IChart](../../com.aspose.slides/ichart).

**Returnerar:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False betyder att dataetiketten inte är synlig (och därför är alla Show*-flaggor (ShowValue, ...) falska). Skrivskyddad boolean.

--------------------

Om dataetiketten är synlig kan du dölja den med Hide()-metoden. Men om dataetiketten inte är synlig (IsVisible är false) kan du göra den synlig genom att sätta Show*-flaggor (ShowValue, ...) till sant läge.

**Returnerar:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Gör dataetiketten dold genom att sätta alla Show*-flaggor (ShowValue, ...) till falskt läge. IsVisible blir false efter detta.

--------------------

Om dataetiketten inte är synlig (IsVisible är false) kan du göra den synlig genom att sätta Show*-flaggor (ShowValue, ...) till sant läge.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Returnerar den faktiska etiketttexten baserat på DataLabelFormat-inställningar eller TextFrameForOverriding.Text-värde.

**Returnerar:**
java.lang.String - The java.lang.String object.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Initierar TextFrameForOverriding med texten i parametern "text". Om TextFrameForOverriding redan är initierad ändras bara dess text.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text för en ny TextFrameForOverriding. |

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Kan innehålla rik formaterad text. Om denna egenskap inte är null så åsidosätter detta formaterade textvärde den automatiskt genererade texten för dataetiketten. Automatgenererad text för dataetiketten betyder text som hanteras av ShowSeriesName, ShowValue, ...-egenskaperna och som formateras med TextFormatManager.TextFormat-egenskapen. Skrivskyddad [ITextFrame](../../com.aspose.slides/itextframe).

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Returnerar textformat. Skrivskyddad [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returnerar:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Returnerar eller sätter x-koordinaten för en titel som en fraktion av diagrammets bredd. Läs/skriv float.

**Returnerar:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Returnerar eller sätter x-koordinaten för en titel som en fraktion av diagrammets bredd. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Returnerar eller sätter y-koordinaten för en titel som en fraktion av diagrammets höjd. Läs/skriv float.

**Returnerar:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Returnerar eller sätter y-koordinaten för en titel som en fraktion av diagrammets höjd. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Returnerar eller sätter bredden på en titel som en fraktion av diagrammets bredd. Läs/skriv float.

**Returnerar:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Returnerar eller sätter bredden på en titel som en fraktion av diagrammets bredd. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Returnerar eller sätter höjden på en titel som en fraktion av diagrammets höjd. Läs/skriv float.

**Returnerar:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Returnerar eller sätter höjden på en titel som en fraktion av diagrammets höjd. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

Höger. Läs/skriv float.

**Returnerar:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Botten. Läs/skriv float.

**Returnerar:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Returnerar dataetikettformat. Skrivskyddad [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returnerar:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Hämtar eller sätter arbetsboksdatacell. Tillämpas om IDataLabelFormat.ShowLabelValueFromCell-egenskapen är sann.

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Hämtar eller sätter arbetsboksdatacell. Tillämpas om IDataLabelFormat.ShowLabelValueFromCell-egenskapen är sann.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```

Hämtar eller sätter formtypen för dataetiketten. Returnerar [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) om ingen form är definierad.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Ställ in formtypen för den första dataetiketten till Ellipse.
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
public final void setLabelShapeType(int value)
```

Hämtar eller sätter formtypen för dataetiketten. Returnerar [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) om ingen form är definierad.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Ställ in formtypen för den första dataetiketten till Ellipse.
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
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Anger den faktiska x-positionen (vänster) för diagrammets element relativt diagrammets övre vänstra hörn. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. Läs float.

**Returnerar:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Anger den faktiska överkanten för diagrammets element relativt diagrammets övre vänstra hörn. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. Läs float.

**Returnerar:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Anger den faktiska bredden för diagrammets element. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. Läs float.

**Returnerar:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Anger den faktiska höjden för diagrammets element. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. Läs float.

**Returnerar:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar den överordnade bilden för en FillFormat. Skrivskyddad [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar den överordnade presentationen för en FillFormat. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)