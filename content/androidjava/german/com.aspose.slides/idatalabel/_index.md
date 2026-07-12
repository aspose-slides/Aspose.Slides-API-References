---
title: IDataLabel
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt Serienbeschriftungen dar.
type: docs
url: /de/com.aspose.slides/idatalabel/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Stellt Serienbeschriftungen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isVisible()](#isVisible--) | False bedeutet, dass die Datenbeschriftung nicht sichtbar ist (und daher alle Show*-Flags (ShowValue, ...) false sind). |
| [hide()](#hide--) | Macht die Datenbeschriftung verborgen, indem alle Show*-Flags (ShowValue, ...) auf den false-Zustand gesetzt werden. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Gibt das Format der Datenbeschriftung zurück. |
| [getValueFromCell()](#getValueFromCell--) | Liest oder setzt die Arbeitsmappendatenzelle. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Liest oder setzt die Arbeitsmappendatenzelle. |
| [getActualLabelText()](#getActualLabelText--) | Gibt den tatsächlichen Beschriftungstext zurück, basierend auf den DataLabelFormat-Einstellungen oder dem Wert TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False bedeutet, dass die Datenbeschriftung nicht sichtbar ist (und daher alle Show*-Flags (ShowValue, ...) false sind). Nur lesbarer boolescher Wert.

--------------------

Wenn die Datenbeschriftung sichtbar ist, können Sie sie mit der Methode Hide() ausblenden. Wenn die Datenbeschriftung nicht sichtbar ist (IsVisible ist false), können Sie sie sichtbar machen, indem Sie die Show*-Flags (ShowValue, ...) auf den true-Zustand setzen.

**Rückgabe:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Macht die Datenbeschriftung verborgen, indem alle Show*-Flags (ShowValue, ...) auf den false-Zustand gesetzt werden. IsVisible wird danach false sein.

--------------------

Wenn die Datenbeschriftung nicht sichtbar ist (IsVisible ist false), können Sie sie sichtbar machen, indem Sie die Show*-Flags (ShowValue, ...) auf den true-Zustand setzen.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Gibt das Format der Datenbeschriftung zurück. Nur lesbar [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Rückgabe:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Liest oder setzt die Arbeitsmappendatenzelle. Wird angewendet, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell den Wert true hat.

**Rückgabe:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Liest oder setzt die Arbeitsmappendatenzelle. Wird angewendet, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell den Wert true hat.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Gibt den tatsächlichen Beschriftungstext zurück, basierend auf den DataLabelFormat-Einstellungen oder dem Wert TextFrameForOverriding.Text.

**Rückgabe:**
java.lang.String - Tatsächlicher Beschriftungstext String