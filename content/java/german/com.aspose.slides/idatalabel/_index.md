---
title: IDataLabel
second_title: Aspose.Slides für Java API-Referenz
description: Stellt Serienbeschriftungen dar.
type: docs
url: /de/com.aspose.slides/idatalabel/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Stellt eine Serienbeschriftung dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isVisible()](#isVisible--) | False bedeutet, dass die Datenbeschriftung nicht sichtbar ist (und daher alle Show*-Flags (ShowValue, ...) false sind). |
| [hide()](#hide--) | Macht die Datenbeschriftung verborgen, indem alle Show*-Flags (ShowValue, ...) auf den falschen Zustand gesetzt werden. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Gibt das Format der Datenbeschriftung zurück. |
| [getValueFromCell()](#getValueFromCell--) | Liest oder setzt die Datenzelle der Arbeitsmappe. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Liest oder setzt die Datenzelle der Arbeitsmappe. |
| [getActualLabelText()](#getActualLabelText--) | Gibt den tatsächlichen Beschriftungstext zurück, basierend auf den DataLabelFormat-Einstellungen oder dem Wert TextFrameForOverriding.Text. |
| [getLabelShapeType()](#getLabelShapeType--) | Liest oder setzt den Formtyp der Datenbeschriftung. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Liest oder setzt den Formtyp der Datenbeschriftung. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False bedeutet, dass die Datenbeschriftung nicht sichtbar ist (und daher alle Show*-Flags (ShowValue, ...) false sind). Nur-Lese-Boolean.

--------------------

Wenn die Datenbeschriftung sichtbar ist, können Sie sie mit der Hide()-Methode ausblenden. Ist die Datenbeschriftung jedoch nicht sichtbar (IsVisible ist false), können Sie sie sichtbar machen, indem Sie die Show*-Flags (ShowValue, ...) auf den wahren Zustand setzen.

**Rückgabewert:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Macht die Datenbeschriftung verborgen, indem alle Show*-Flags (ShowValue, ...) auf den falschen Zustand gesetzt werden. IsVisible wird danach false sein.

--------------------

Ist die Datenbeschriftung nicht sichtbar (IsVisible ist false), können Sie sie sichtbar machen, indem Sie die Show*-Flags (ShowValue, ...) auf den wahren Zustand setzen.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Gibt das Format der Datenbeschriftung zurück. Nur-Lese [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Rückgabewert:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Liest oder setzt die Datenzelle der Arbeitsmappe. Wird angewendet, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell true ist.

**Rückgabewert:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Liest oder setzt die Datenzelle der Arbeitsmappe. Wird angewendet, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell true ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Gibt den tatsächlichen Beschriftungstext zurück, basierend auf den DataLabelFormat-Einstellungen oder dem Wert TextFrameForOverriding.Text.

**Rückgabewert:**
java.lang.String - Tatsächlicher Beschriftungstext String
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

Liest oder setzt den Formtyp der Datenbeschriftung. Gibt [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) zurück, wenn keine Form definiert ist.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Setzen Sie den Formtyp der ersten Datenbeschriftung auf Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

Liest oder setzt den Formtyp der Datenbeschriftung. Gibt [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) zurück, wenn keine Form definiert ist.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Setzen Sie den Formtyp der ersten Datenbeschriftung auf Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |