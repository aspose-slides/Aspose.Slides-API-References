---
title: IDataLabel
second_title: Aspose.Slides für Java API Referenz
description: Stellt Serienetiketten dar.
type: docs
url: /de/com.aspose.slides/idatalabel/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Stellt Serienetiketten dar.
## Methoden

| Method | Beschreibung |
| --- | --- |
| [isVisible()](#isVisible--) | False bedeutet, dass das Datenetikett nicht sichtbar ist (und somit alle Show*-Flags (ShowValue, ...) false sind). |
| [hide()](#hide--) | Macht das Datenetikett unsichtbar, indem alle Show*-Flags (ShowValue, ...) in den false-Zustand gesetzt werden. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Gibt das Format des Datenetiketts zurück. |
| [getValueFromCell()](#getValueFromCell--) | Liest oder setzt die Arbeitsmappe-Datenzelle. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Liest oder setzt die Arbeitsmappe-Datenzelle. |
| [getActualLabelText()](#getActualLabelText--) | Gibt den tatsächlichen Etikettentext zurück, basierend auf den Einstellungen von DataLabelFormat oder dem Wert von TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False bedeutet, dass das Datenetikett nicht sichtbar ist (und somit alle Show*-Flags (ShowValue, ...) false sind). Nur lesbar boolean.

--------------------

Wenn das Datenetikett sichtbar ist, können Sie es mit der Hide()-Methode ausblenden. Ist das Datenetikett jedoch nicht sichtbar (IsVisible ist false), können Sie es sichtbar machen, indem Sie die Show*-Flags (ShowValue, ...) auf true setzen.

**Rückgabewert:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Macht das Datenetikett unsichtbar, indem alle Show*-Flags (ShowValue, ...) in den false-Zustand gesetzt werden. IsVisible wird danach false sein.

--------------------

Ist das Datenetikett nicht sichtbar (IsVisible ist false), können Sie es sichtbar machen, indem Sie die Show*-Flags (ShowValue, ...) auf true setzen.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```


Gibt das Format des Datenetiketts zurück. Nur lesbar [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Rückgabewert:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```


Liest oder setzt die Arbeitsmappe-Datenzelle. Wird angewendet, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell true ist.

**Rückgabewert:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```


Liest oder setzt die Arbeitsmappe-Datenzelle. Wird angewendet, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell true ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```


Gibt den tatsächlichen Etikettentext zurück, basierend auf den Einstellungen von DataLabelFormat oder dem Wert von TextFrameForOverriding.Text.

**Rückgabewert:**
java.lang.String - Tatsächlicher Etikettentext String