---
title: DataLabel
second_title: Aspose.Slides für Android über Java API-Referenz
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
| [isVisible()](#isVisible--) | False bedeutet, dass die Datenbeschriftung nicht sichtbar ist (und daher alle Show*-Flags (ShowValue, ...) false sind). |
| [hide()](#hide--) | Macht die Datenbeschriftung unsichtbar, indem alle Show*-Flags (ShowValue, ...) auf false gesetzt werden. |
| [getActualLabelText()](#getActualLabelText--) | Gibt den tatsächlichen Beschriftungstext basierend auf den DataLabelFormat-Einstellungen oder dem TextFrameForOverriding.Text-Wert zurück. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialisiert TextFrameForOverriding mit dem Text im Parameter "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Kann einen reich formatierten Text enthalten. |
| [getTextFormat()](#getTextFormat--) | Gibt das Textformat zurück. |
| [getX()](#getX--) | Gibt die x-Koordinate eines Titels als Bruchteil der Diagrammbreite zurück oder setzt sie. |
| [setX(float value)](#setX-float-) | Gibt die x-Koordinate eines Titels als Bruchteil der Diagrammbreite zurück oder setzt sie. |
| [getY()](#getY--) | Gibt die y-Koordinate eines Titels als Bruchteil der Diagrammhöhe zurück oder setzt sie. |
| [setY(float value)](#setY-float-) | Gibt die y-Koordinate eines Titels als Bruchteil der Diagrammhöhe zurück oder setzt sie. |
| [getWidth()](#getWidth--) | Gibt die Breite eines Titels als Bruchteil der Diagrammbreite zurück oder setzt sie. |
| [setWidth(float value)](#setWidth-float-) | Gibt die Breite eines Titels als Bruchteil der Diagrammbreite zurück oder setzt sie. |
| [getHeight()](#getHeight--) | Gibt die Höhe eines Titels als Bruchteil der Diagrammhöhe zurück oder setzt sie. |
| [setHeight(float value)](#setHeight-float-) | Gibt die Höhe eines Titels als Bruchteil der Diagrammhöhe zurück oder setzt sie. |
| [getRight()](#getRight--) | Rechts. |
| [getBottom()](#getBottom--) | Unten. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Gibt das Datenbeschriftungsformat zurück. |
| [getValueFromCell()](#getValueFromCell--) | Liest oder setzt die Arbeitsmappenzelle. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Liest oder setzt die Arbeitsmappenzelle. |
| [getActualX()](#getActualX--) | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. |
| [getActualY()](#getActualY--) | Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. |
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
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Übergeordnetes ChartDataPoint. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Read-only IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Gibt das übergeordnete Diagramm zurück. Read-only [IChart](../../com.aspose.slides/ichart).

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False bedeutet, dass die Datenbeschriftung nicht sichtbar ist (und daher alle Show*-Flags (ShowValue, ...) false sind). Read-only  boolean .

--------------------

Wenn die Datenbeschriftung sichtbar ist, können Sie sie mit der Hide()-Methode ausblenden. Wenn die Datenbeschriftung jedoch nicht sichtbar ist (IsVisible ist false), können Sie sie sichtbar machen, indem Sie die Show*-Flags (ShowValue, ...) auf den true-Zustand setzen.

**Rückgabe:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Macht die Datenbeschriftung unsichtbar, indem alle Show*-Flags (ShowValue, ...) auf false gesetzt werden. IsVisible wird danach false sein.

--------------------

Wenn die Datenbeschriftung nicht sichtbar ist (IsVisible ist false), können Sie sie sichtbar machen, indem Sie die Show*-Flags (ShowValue, ...) auf true setzen.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Gibt den tatsächlichen Beschriftungstext basierend auf den DataLabelFormat-Einstellungen oder dem TextFrameForOverriding.Text-Wert zurück.

**Rückgabe:**
java.lang.String - Das java.lang.String-Objekt.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Initialisiert TextFrameForOverriding mit dem Text im Parameter "text". Wenn TextFrameForOverriding bereits initialisiert ist, ändert es einfach dessen Text.

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

Kann einen reich formatierten Text enthalten. Wenn diese Eigenschaft nicht null ist, überschreibt dieser formatierte Textwert den automatisch generierten Text der Datenbeschriftung. Der automatisch generierte Text der Datenbeschriftung bedeutet Text, der von den Eigenschaften ShowSeriesName, ShowValue, ... verwaltet wird und mit der TextFormatManager.TextFormat-Eigenschaft formatiert ist. Read-only [ITextFrame](../../com.aspose.slides/itextframe).

**Rückgabe:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Gibt das Textformat zurück. Read-only [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Rückgabe:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Gibt die x-Koordinate eines Titels als Bruchteil der Diagrammbreite zurück oder setzt sie. Read/write  float .

**Rückgabe:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Gibt die x-Koordinate eines Titels als Bruchteil der Diagrammbreite zurück oder setzt sie. Read/write  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Gibt die y-Koordinate eines Titels als Bruchteil der Diagrammhöhe zurück oder setzt sie. Read/write  float .

**Rückgabe:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Gibt die y-Koordinate eines Titels als Bruchteil der Diagrammhöhe zurück oder setzt sie. Read/write  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Gibt die Breite eines Titels als Bruchteil der Diagrammbreite zurück oder setzt sie. Read/write  float .

**Rückgabe:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Gibt die Breite eines Titels als Bruchteil der Diagrammbreite zurück oder setzt sie. Read/write  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Gibt die Höhe eines Titels als Bruchteil der Diagrammhöhe zurück oder setzt sie. Read/write  float .

**Rückgabe:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Gibt die Höhe eines Titels als Bruchteil der Diagrammhöhe zurück oder setzt sie. Read/write  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

Rechts. Read-only  float .

**Rückgabe:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Unten. Read-only  float .

**Rückgabe:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Gibt das Datenbeschriftungsformat zurück. Read-only [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Rückgabe:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Liest oder setzt die Arbeitsmappenzelle. Wird angewendet, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell true ist.

**Rückgabe:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Liest oder setzt die Arbeitsmappenzelle. Wird angewendet, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell true ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Read  float .

**Rückgabe:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Read  float .

**Rückgabe:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Read  float .

**Rückgabe:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Read  float .

**Rückgabe:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die übergeordnete Folie eines FillFormat zurück. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Rückgabe:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation eines FillFormat zurück. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)