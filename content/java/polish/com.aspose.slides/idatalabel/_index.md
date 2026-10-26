---
title: IDataLabel
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje etykiety serii.
type: docs
url: /pl/com.aspose.slides/idatalabel/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Reprezentuje etykiety serii.
## Metody

| Metoda | Opis |
| --- | --- |
| [isVisible()](#isVisible--) | False means that data label is not visible (and so all Show\*-flags (ShowValue, ...) are false). |
| [hide()](#hide--) | Make data label hidden by setting all Show\*-flags (ShowValue, ...) to false state. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Returns format of the data label. |
| [getValueFromCell()](#getValueFromCell--) | Gets or sets workbook data cell. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Gets or sets workbook data cell. |
| [getActualLabelText()](#getActualLabelText--) | Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False means that data label is not visible (and so all Show\*-flags (ShowValue, ...) are false). Typ logiczny tylko do odczytu.

--------------------

Jeśli etykieta danych jest widoczna, możesz ją ukryć metodą Hide(). Natomiast jeśli etykieta danych nie jest widoczna (IsVisible jest false), możesz ją uczynić widoczną, ustawiając flagi Show\*-flags (ShowValue, ...) w stan true.

**Zwraca:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Make data label hidden by setting all Show\*-flags (ShowValue, ...) to false state. IsVisible will be false after this.

--------------------

Jeśli etykieta danych nie jest widoczna (IsVisible jest false), możesz ją uczynić widoczną, ustawiając flagi Show\*-flags (ShowValue, ...) w stan true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Returns format of the data label. Read-only [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Zwraca:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true.

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value.

**Zwraca:**
java.lang.String - Actual label text String