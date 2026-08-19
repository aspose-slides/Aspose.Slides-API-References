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
| [isVisible()](#isVisible--) | False betyder att datamärket inte är synligt (och så är alla Show*-flags (ShowValue, ...) falska). |
| [hide()](#hide--) | Gör datamärket dolt genom att sätta alla Show*-flags (ShowValue, ...) till falskt läge. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Returnerar formatet för datamärket. |
| [getValueFromCell()](#getValueFromCell--) | Hämtar eller sätter arbetsbokens datacell. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Hämtar eller sätter arbetsbokens datacell. |
| [getActualLabelText()](#getActualLabelText--) | Returnerar den faktiska etiketttexten baserat på DataLabelFormat-inställningar eller TextFrameForOverriding.Text-värdet. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False betyder att datamärket inte är synligt (och så är alla Show*-flags (ShowValue, ...) falska). Skrivskyddad boolean.

--------------------

Om datamärket är synligt kan du dölja det med Hide()-metoden. Men om datamärket inte är synligt (IsVisible är falskt) kan du göra datamärket synligt genom att sätta Show*-flags (ShowValue, ...) till sant läge.

**Returnerar:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Gör datamärket dolt genom att sätta alla Show*-flags (ShowValue, ...) till falskt läge. IsVisible kommer att vara falskt efter detta.

--------------------

Om datamärket inte är synligt (IsVisible är falskt) kan du göra datamärket synligt genom att sätta Show*-flags (ShowValue, ...) till sant läge.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Returnerar formatet för datamärket. Skrivskyddad [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returnerar:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Hämtar eller sätter arbetsbokens datacell. Tillämpas om egenskapen IDataLabelFormat.ShowLabelValueFromCell är sann.

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Hämtar eller sätter arbetsbokens datacell. Tillämpas om egenskapen IDataLabelFormat.ShowLabelValueFromCell är sann.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Returnerar den faktiska etiketttexten baserat på DataLabelFormat-inställningar eller TextFrameForOverriding.Text-värdet.

**Returnerar:**
java.lang.String - Faktisk etiketttext String