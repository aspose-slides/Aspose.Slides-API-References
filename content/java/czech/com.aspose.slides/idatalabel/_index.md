---
title: IDataLabel
second_title: Aspose.Slides pro Java - referenční příručka API
description: Reprezentuje štítky řady.
type: docs
url: /cs/com.aspose.slides/idatalabel/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Reprezentuje štítky řady.
## Metody

| Metoda | Popis |
| --- | --- |
| [isVisible()](#isVisible--) | False znamená, že popisek dat není viditelný (a všechny příznaky Show*- (ShowValue, ...) jsou nastaveny na false). |
| [hide()](#hide--) | Skryje popisek dat nastavením všech příznaků Show*- (ShowValue, ...) do stavu false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Vrací formát popisku dat. |
| [getValueFromCell()](#getValueFromCell--) | Získá nebo nastaví buňku dat sešitu. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Získá nebo nastaví buňku dat sešitu. |
| [getActualLabelText()](#getActualLabelText--) | Vrací skutečný text popisku na základě nastavení DataLabelFormat nebo hodnoty TextFrameForOverriding.Text. |
| [getLabelShapeType()](#getLabelShapeType--) | Získá nebo nastaví typ tvaru popisku dat. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Získá nebo nastaví typ tvaru popisku dat. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False znamená, že popisek dat není viditelný (a všechny příznaky Show*- (ShowValue, ...) jsou nastaveny na false). Pouze pro čtení boolean.

--------------------

Pokud je popisek dat viditelný, můžete jej skrýt metodou Hide(). Pokud však popisek dat není viditelný (IsVisible je false), můžete jej zobrazit nastavením příznaků Show*- (ShowValue, ...) do stavu true.

**Vrací:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Skryje popisek dat nastavením všech příznaků Show*- (ShowValue, ...) do stavu false. IsVisible bude po tomto nastavení false.

--------------------

Pokud popisek dat není viditelný (IsVisible je false), můžete jej zobrazit nastavením příznaků Show*- (ShowValue, ...) do stavu true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Vrací formát popisku dat. Pouze pro čtení [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Vrací:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Získá nebo nastaví buňku dat sešitu. Použije se, pokud má vlastnost IDataLabelFormat.ShowLabelValueFromCell hodnotu true.

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Získá nebo nastaví buňku dat sešitu. Použije se, pokud má vlastnost IDataLabelFormat.ShowLabelValueFromCell hodnotu true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Vrací skutečný text popisku na základě nastavení DataLabelFormat nebo hodnoty TextFrameForOverriding.Text.

**Vrací:**
java.lang.String - Skutečný text popisku typu String
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

Získá nebo nastaví typ tvaru popisku dat. Vrací [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined), pokud není tvar definován.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Nastavte typ tvaru prvního popisku dat na Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

Získá nebo nastaví typ tvaru popisku dat. Vrací [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined), pokud není tvar definován.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      //      // Nastavte typ tvaru prvního popisku dat na Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |