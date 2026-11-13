---
title: IDataLabel
second_title: Aspose.Slides için Java API Referansı
description: Bir dizi etiketini temsil eder.
type: docs
url: /tr/com.aspose.slides/idatalabel/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Bir dizi etiketini temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [isVisible()](#isVisible--) | False, veri etiketinin görünür olmadığını (ve bu nedenle tüm Show*-bayraklarının (ShowValue, ...) false olduğunu) ifade eder. |
| [hide()](#hide--) | Tüm Show*-bayraklarını (ShowValue, ...) false durumuna ayarlayarak veri etiketini gizler. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Veri etiketinin biçimini döndürür. |
| [getValueFromCell()](#getValueFromCell--) | Çalışma kitabı veri hücresini alır veya ayarlar. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Çalışma kitabı veri hücresini alır veya ayarlar. |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat ayarlarına veya TextFrameForOverriding.Text değerine göre gerçek etiket metnini döndürür. |
| [getLabelShapeType()](#getLabelShapeType--) | Veri etiketinin şekil türünü alır veya ayarlar. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Veri etiketinin şekil türünü alır veya ayarlar. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False, veri etiketinin görünür olmadığını (ve bu nedenle tüm Show*-bayraklarının (ShowValue, ...) false olduğunu) ifade eder. Salt-okunur boolean.

--------------------

Veri etiketi görünürse Hide() yöntemiyle gizleyebilirsiniz. Ancak veri etiketi görünür değilse (IsVisible false ise) Show*-bayraklarını (ShowValue, ...) true durumuna ayarlayarak veri etiketini görünür yapabilirsiniz.

**Döndürür:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Tüm Show*-bayraklarını (ShowValue, ...) false durumuna ayarlayarak veri etiketini gizler. Bu işlemden sonra IsVisible false olur.

--------------------

Veri etiketi görünür değilse (IsVisible false ise) Show*-bayraklarını (ShowValue, ...) true durumuna ayarlayarak veri etiketini görünür yapabilirsiniz.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Veri etiketinin biçimini döndürür. Salt-okunur [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Döndürür:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Çalışma kitabı veri hücresini alır veya ayarlar. IDataLabelFormat.ShowLabelValueFromCell özelliği true olduğunda uygulanır.

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Çalışma kitabı veri hücresini alır veya ayarlar. IDataLabelFormat.ShowLabelValueFromCell özelliği true olduğunda uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

DataLabelFormat ayarlarına veya TextFrameForOverriding.Text değerine göre gerçek etiket metnini döndürür.

**Döndürür:**
java.lang.String - Gerçek etiket metni String
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

Veri etiketinin şekil türünü alır veya ayarlar. Şekil tanımlı değilse [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) döndürür.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // İlk veri etiketinin şekil türünü Elips olarak ayarla.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

Veri etiketinin şekil türünü alır veya ayarlar. Şekil tanımlı değilse [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) döndürür.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // İlk veri etiketinin şekil tipini Elips olarak ayarla.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |