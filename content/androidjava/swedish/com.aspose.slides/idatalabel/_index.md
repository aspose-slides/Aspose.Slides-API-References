---
title: IDataLabel
second_title: Aspose.Slides för Android via Java API-referens
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
| [isVisible()](#isVisible--) | False betyder att dataetiketten inte är synlig (och så är alla Show*-flags (ShowValue, ...) false). |
| [hide()](#hide--) | Gör dataetiketten dold genom att sätta alla Show*-flags (ShowValue, ...) till false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Returnerar formatet för dataetiketten. |
| [getValueFromCell()](#getValueFromCell--) | Hämtar eller anger arbetsbokens datacell. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Hämtar eller anger arbetsbokens datacell. |
| [getActualLabelText()](#getActualLabelText--) | Returnerar den faktiska etiketttexten baserat på DataLabelFormat-inställningarna eller TextFrameForOverriding.Text-värdet. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False betyder att dataetiketten inte är synlig (och så är alla Show*-flags (ShowValue, ...) false). Skrivskyddad boolesk.

--------------------

Om dataetiketten är synlig kan du göra den dold med Hide()-metoden. Men om dataetiketten inte är synlig (IsVisible är false) kan du göra dataetiketten synlig genom att ställa in Show*-flags (ShowValue, ...) till true.

**Returnerar:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Gör dataetiketten dold genom att sätta alla Show*-flags (ShowValue, ...) till false. IsVisible kommer att vara false efter detta.

--------------------

Om dataetiketten inte är synlig (IsVisible är false) kan du göra den synlig genom att ställa in Show*-flags (ShowValue, ...) till true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Returnerar formatet för dataetiketten. Skrivskyddad [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returnerar:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Hämtar eller anger arbetsbokens datacell. Tillämpar om egenskapen IDataLabelFormat.ShowLabelValueFromCell är true.

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Hämtar eller anger arbetsbokens datacell. Tillämpar om egenskapen IDataLabelFormat.ShowLabelValueFromCell är true.

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