---
title: IDataLabel
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een reeks labels voor.
type: docs
url: /nl/com.aspose.slides/idatalabel/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Stelt een reeks labels voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isVisible()](#isVisible--) | False betekent dat het gegevenslabel niet zichtbaar is (en dus alle Show*-flags (ShowValue, ...) onwaar zijn). |
| [hide()](#hide--) | Verberg het gegevenslabel door alle Show*-flags (ShowValue, ...) op een onwaar status te zetten. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Retourneert het formaat van het gegevenslabel. |
| [getValueFromCell()](#getValueFromCell--) | Haalt op of stelt de werkboekgegevenscel in. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Haalt op of stelt de werkboekgegevenscel in. |
| [getActualLabelText()](#getActualLabelText--) | Retourneert de werkelijke labeltekst op basis van DataLabelFormat-instellingen of de waarde van TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False betekent dat het gegevenslabel niet zichtbaar is (en dus alle Show*-flags (ShowValue, ...) onwaar zijn). Alleen-lezen boolean.

--------------------

Als het gegevenslabel zichtbaar is, kun je het verbergen met de Hide()-methode. Maar als het gegevenslabel niet zichtbaar is (IsVisible is false) kun je het gegevenslabel zichtbaar maken door de Show*-flags (ShowValue, ...) op een waar status te zetten.

**Retourneert:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Verberg het gegevenslabel door alle Show*-flags (ShowValue, ...) op een onwaar status te zetten. IsVisible zal daarna onwaar zijn.

--------------------

Als het gegevenslabel niet zichtbaar is (IsVisible is false) kun je het gegevenslabel zichtbaar maken door de Show*-flags (ShowValue, ...) op een waar status te zetten.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```


Retourneert het formaat van het gegevenslabel. Alleen-lezen [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Retourneert:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```


Haalt op of stelt de werkboekgegevenscel in. Toegepast als de eigenschap IDataLabelFormat.ShowLabelValueFromCell waar is.

**Retourneert:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```


Haalt op of stelt de werkboekgegevenscel in. Toegepast als de eigenschap IDataLabelFormat.ShowLabelValueFromCell waar is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```


Retourneert de werkelijke labeltekst op basis van DataLabelFormat-instellingen of de waarde van TextFrameForOverriding.Text.

**Retourneert:**
java.lang.String - Werkelijke labeltekst String