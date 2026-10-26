---
title: DataLabel
second_title: Aspose.Slides för Java API-referens
description: Representerar serieetiketter.
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

Representerar serieetiketter.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Skapar en ny instans av DataLabel-klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Returnerar det överordnade diagrammet. |
| [isVisible()](#isVisible--) | Falskt betyder att dataetiketten inte är synlig (och så är alla Show*-flaggor (ShowValue, ...) falska). |
| [hide()](#hide--) | Gör dataetiketten dold genom att sätta alla Show*-flaggor (ShowValue, ...) till falskt läge. |
| [getActualLabelText()](#getActualLabelText--) | Returnerar den faktiska etiketttexten baserat på DataLabelFormat-inställningarna eller TextFrameForOverriding.Text-värdet. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initierar TextFrameForOverriding med texten i parametern "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Kan innehålla en rik formaterad text. |
| [getTextFormat()](#getTextFormat--) | Returnerar textformat. |
| [getX()](#getX--) | Returnerar eller anger x-koordinaten för en titel som en bråkdel av diagrammets bredd. |
| [setX(float value)](#setX-float-) | Returnerar eller anger x-koordinaten för en titel som en bråkdel av diagrammets bredd. |
| [getY()](#getY--) | Returnerar eller anger y-koordinaten för en titel som en bråkdel av diagrammets höjd. |
| [setY(float value)](#setY-float-) | Returnerar eller anger y-koordinaten för en titel som en bråkdel av diagrammets höjd. |
| [getWidth()](#getWidth--) | Returnerar eller anger bredden på en titel som en bråkdel av diagrammets bredd. |
| [setWidth(float value)](#setWidth-float-) | Returnerar eller anger bredden på en titel som en bråkdel av diagrammets bredd. |
| [getHeight()](#getHeight--) | Returnerar eller anger höjden på en titel som en bråkdel av diagrammets höjd. |
| [setHeight(float value)](#setHeight-float-) | Returnerar eller anger höjden på en titel som en bråkdel av diagrammets höjd. |
| [getRight()](#getRight--) | Höger. |
| [getBottom()](#getBottom--) | Nederkant. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Returnerar dataetikettformat. |
| [getValueFromCell()](#getValueFromCell--) | Hämtar eller anger arbetsboksdatacell. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Hämtar eller anger arbetsboksdatacell. |
| [getActualX()](#getActualX--) | Anger den faktiska x-positionen (vänster) för diagrammets element relativt diagrammets övre vänstra hörn. |
| [getActualY()](#getActualY--) | Anger den faktiska toppen av diagrammets element relativt diagrammets övre vänstra hörn. |
| [getActualWidth()](#getActualWidth--) | Anger den faktiska bredden på diagrammets element. |
| [getActualHeight()](#getActualHeight--) | Anger den faktiska höjden på diagrammets element. |
| [getSlide()](#getSlide--) | Returnerar den överordnade bilden för ett FillFormat. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen för ett FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Skapar en ny instans av DataLabel-klassen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Överordnad ChartDataPoint. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objektet. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Returnerar det överordnade diagrammet. Skrivskyddad [IChart](../../com.aspose.slides/ichart).

**Returnerar:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Falskt betyder att dataetiketten inte är synlig (och så är alla Show*-flaggor (ShowValue, ...) falska). Skrivskyddad  boolean .

--------------------

Om dataetiketten är synlig kan du göra den dold med Hide()-metoden. Men om dataetiketten inte är synlig (IsVisible är falskt) kan du göra dataetiketten synlig genom att sätta Show*-flaggor (ShowValue, ...) till sant läge.

**Returnerar:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Gör dataetiketten dold genom att sätta alla Show*-flaggor (ShowValue, ...) till falskt läge. IsVisible kommer att vara falskt efter detta.

--------------------

Om dataetiketten inte är synlig (IsVisible är falskt) kan du göra den synlig genom att sätta Show*-flaggor (ShowValue, ...) till sant läge.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Returnerar den faktiska etiketttexten baserat på DataLabelFormat-inställningarna eller TextFrameForOverriding.Text-värdet.

**Returnerar:**
java.lang.String - java.lang.String-objektet.
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

Kan innehålla en rik formaterad text. Om denna egenskap inte är null så åsidosätter detta formaterade textvärde den automatiskt genererade texten för dataetiketten. Automatiskt genererad text för dataetiketten betyder text som hanteras av ShowSeriesName, ShowValue, ... egenskaperna och som är formaterad med TextFormatManager.TextFormat-egenskapen. Skrivskyddad [ITextFrame](../../com.aspose.slides/itextframe).

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

Returnerar eller anger x-koordinaten för en titel som en bråkdel av diagrammets bredd. Läs/skriv  float .

**Returnerar:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Returnerar eller anger x-koordinaten för en titel som en bråkdel av diagrammets bredd. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Returnerar eller anger y-koordinaten för en titel som en bråkdel av diagrammets höjd. Läs/skriv  float .

**Returnerar:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Returnerar eller anger y-koordinaten för en titel som en bråkdel av diagrammets höjd. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Returnerar eller anger bredden på en titel som en bråkdel av diagrammets bredd. Läs/skriv  float .

**Returnerar:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Returnerar eller anger bredden på en titel som en bråkdel av diagrammets bredd. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Returnerar eller anger höjden på en titel som en bråkdel av diagrammets höjd. Läs/skriv  float .

**Returnerar:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Returnerar eller anger höjden på en titel som en bråkdel av diagrammets höjd. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

Höger. Skrivskyddad  float .

**Returnerar:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Nederkant. Skrivskyddad  float .

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

Hämtar eller anger arbetsboksdatacell. Tillämpas om IDataLabelFormat.ShowLabelValueFromCell-egenskapen är true.

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Hämtar eller anger arbetsboksdatacell. Tillämpas om IDataLabelFormat.ShowLabelValueFromCell-egenskapen är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Anger den faktiska x-positionen (vänster) för diagrammets element relativt diagrammets övre vänstra hörn. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. Läs  float .

**Returnerar:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Anger den faktiska toppen av diagrammets element relativt diagrammets övre vänstra hörn. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. Läs  float .

**Returnerar:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Anger den faktiska bredden på diagrammets element. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. Läs  float .

**Returnerar:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Anger den faktiska höjden på diagrammets element. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. Läs  float .

**Returnerar:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar den överordnade bilden för ett FillFormat. Skrivskyddad [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar den överordnade presentationen för ett FillFormat. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)