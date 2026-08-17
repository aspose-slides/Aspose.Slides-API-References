---
title: DataLabel
second_title: Aspose.Slides für Java API Referenz
description: Stellt Serienbeschriftungen dar.
type: docs
url: /de/com.aspose.slides/datalabel/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Stellt Serienbeschriftungen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Erstellt eine neue Instanz der DataLabel-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Gibt das übergeordnete Diagramm zurück. |
| [isVisible()](#isVisible--) | False bedeutet, dass die Datenbeschriftung nicht sichtbar ist (und somit alle Show\*-Flags (ShowValue, ...) false sind). |
| [hide()](#hide--) | Macht die Datenbeschriftung unsichtbar, indem alle Show\*-Flags (ShowValue, ...) auf den falschen Zustand gesetzt werden. |
| [getActualLabelText()](#getActualLabelText--) | Gibt den tatsächlichen Beschriftungstext basierend auf den DataLabelFormat-Einstellungen oder dem Textwert von TextFrameForOverriding.Text zurück. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialisiert TextFrameForOverriding mit dem Text im Parameter "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Kann einen reich formatierten Text enthalten. |
| [getTextFormat()](#getTextFormat--) | Gibt das Textformat zurück. |
| [getX()](#getX--) | Gibt die x-Koordinate eines Titels zurück oder setzt sie als Bruchteil der Breite des Diagramms. |
| [setX(float value)](#setX-float-) | Gibt die x-Koordinate eines Titels zurück oder setzt sie als Bruchteil der Breite des Diagramms. |
| [getY()](#getY--) | Gibt die y-Koordinate eines Titels zurück oder setzt sie als Bruchteil der Höhe des Diagramms. |
| [setY(float value)](#setY-float-) | Gibt die y-Koordinate eines Titels zurück oder setzt sie als Bruchteil der Höhe des Diagramms. |
| [getWidth()](#getWidth--) | Gibt die Breite eines Titels zurück oder setzt sie als Bruchteil der Breite des Diagramms. |
| [setWidth(float value)](#setWidth-float-) | Gibt die Breite eines Titels zurück oder setzt sie als Bruchteil der Breite des Diagramms. |
| [getHeight()](#getHeight--) | Gibt die Höhe eines Titels zurück oder setzt sie als Bruchteil der Höhe des Diagramms. |
| [setHeight(float value)](#setHeight-float-) | Gibt die Höhe eines Titels zurück oder setzt sie als Bruchteil der Höhe des Diagramms. |
| [getRight()](#getRight--) | Rechts. |
| [getBottom()](#getBottom--) | Unten. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Gibt das Datenbeschriftungsformat zurück. |
| [getValueFromCell()](#getValueFromCell--) | Ruft die Arbeitsblatt-Datenzelle ab oder legt sie fest. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Ruft die Arbeitsblatt-Datenzelle ab oder legt sie fest. |
| [getActualX()](#getActualX--) | Gibt den tatsächlichen x-Standort (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. |
| [getActualY()](#getActualY--) | Gibt den tatsächlichen oberen Standort des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. |
| [getActualWidth()](#getActualWidth--) | Gibt die tatsächliche Breite des Diagrammelements an. |
| [getActualHeight()](#getActualHeight--) | Gibt die tatsächliche Höhe des Diagrammelements an. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines FillFormat zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines FillFormat zurück. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Erstellt eine neue Instanz der DataLabel-Klasse.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Übergeordneter ChartDataPoint. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Gibt das übergeordnete Diagramm zurück. Nur lesbar [IChart](../../com.aspose.slides/ichart).

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False bedeutet, dass die Datenbeschriftung nicht sichtbar ist (und somit alle Show\*-Flags (ShowValue, ...) false sind). Nur lesbar boolean.

--------------------

Wenn die Datenbeschriftung sichtbar ist, können Sie sie mit der Hide()-Methode ausblenden. Wenn die Datenbeschriftung jedoch nicht sichtbar ist (IsVisible ist false), können Sie sie sichtbar machen, indem Sie die Show\*-Flags (ShowValue, ...) auf den wahren Zustand setzen.

**Rückgabe:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Macht die Datenbeschriftung unsichtbar, indem alle Show\*-Flags (ShowValue, ...) auf den falschen Zustand gesetzt werden. IsVisible wird nach diesem Aufruf false sein.

--------------------

Wenn die Datenbeschriftung nicht sichtbar ist (IsVisible ist false), können Sie sie sichtbar machen, indem Sie die Show\*-Flags (ShowValue, ...) auf den wahren Zustand setzen.
### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Gibt den tatsächlichen Beschriftungstext basierend auf den DataLabelFormat-Einstellungen oder dem Textwert von TextFrameForOverriding.Text zurück.

**Rückgabe:**
java.lang.String - Das java.lang.String-Objekt.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Initialisiert TextFrameForOverriding mit dem Text im Parameter "text". Wenn TextFrameForOverriding bereits initialisiert ist, wird einfach sein Text geändert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Text für ein neues TextFrameForOverriding. |

**Rückgabe:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Kann einen reich formatierten Text enthalten. Wenn diese Eigenschaft nicht null ist, überschreibt dieser formatierte Textwert den automatisch erzeugten Text der Datenbeschriftung. Der automatisch erzeugte Text der Datenbeschriftung ist der Text, der von den Eigenschaften ShowSeriesName, ShowValue, … verwaltet wird und mit der TextFormatManager.TextFormat-Eigenschaft formatiert ist. Nur lesbar [ITextFrame](../../com.aspose.slides/itextframe).

**Rückgabe:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Gibt das Textformat zurück. Nur lesbar [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Rückgabe:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Gibt die x-Koordinate eines Titels zurück oder setzt sie als Bruchteil der Breite des Diagramms. Lesen/Schreiben float.

**Rückgabe:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Gibt die x-Koordinate eines Titels zurück oder setzt sie als Bruchteil der Breite des Diagramms. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Gibt die y-Koordinate eines Titels zurück oder setzt sie als Bruchteil der Höhe des Diagramms. Lesen/Schreiben float.

**Rückgabe:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Gibt die y-Koordinate eines Titels zurück oder setzt sie als Bruchteil der Höhe des Diagramms. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Gibt die Breite eines Titels zurück oder setzt sie als Bruchteil der Breite des Diagramms. Lesen/Schreiben float.

**Rückgabe:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Gibt die Breite eines Titels zurück oder setzt sie als Bruchteil der Breite des Diagramms. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Gibt die Höhe eines Titels zurück oder setzt sie als Bruchteil der Höhe des Diagramms. Lesen/Schreiben float.

**Rückgabe:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Gibt die Höhe eines Titels zurück oder setzt sie als Bruchteil der Höhe des Diagramms. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

Rechts. Nur lesbar float.

**Rückgabe:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Unten. Nur lesbar float.

**Rückgabe:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Gibt das Datenbeschriftungsformat zurück. Nur lesbar [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Rückgabe:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Ruft die Arbeitsblatt-Datenzelle ab oder legt sie fest. Wird angewendet, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell true ist.

**Rückgabe:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Ruft die Arbeitsblatt-Datenzelle ab oder legt sie fest. Wird angewendet, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell true ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Gibt den tatsächlichen x-Standort (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorab die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Lesen float.

**Rückgabe:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Gibt den tatsächlichen oberen Standort des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorab die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Lesen float.

**Rückgabe:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie vorab die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Lesen float.

**Rückgabe:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie vorab die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Lesen float.

**Rückgabe:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die übergeordnete Folie eines FillFormat zurück. Nur lesbar [BaseSlide](../../com.aspose.slides/baseslide).

**Rückgabe:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation eines FillFormat zurück. Nur lesbar [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)