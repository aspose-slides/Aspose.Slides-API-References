---
title: IDataLabel
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili label seri.
type: docs
url: /id/com.aspose.slides/idatalabel/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Mewakili label seri.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isVisible()](#isVisible--) | False berarti label data tidak terlihat (dan sehingga semua Show\*-flags (ShowValue, ...) adalah false). |
| [hide()](#hide--) | Menyembunyikan label data dengan mengatur semua Show\*-flags (ShowValue, ...) ke keadaan false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Mengembalikan format label data. |
| [getValueFromCell()](#getValueFromCell--) | Mendapatkan atau mengatur sel data workbook. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Mendapatkan atau mengatur sel data workbook. |
| [getActualLabelText()](#getActualLabelText--) | Mengembalikan teks label aktual berdasarkan pengaturan DataLabelFormat atau nilai TextFrameForOverriding.Text. |
| [getLabelShapeType()](#getLabelShapeType--) | Mendapatkan atau mengatur tipe bentuk label data. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Mendapatkan atau mengatur tipe bentuk label data. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False berarti label data tidak terlihat (dan sehingga semua Show\*-flags (ShowValue, ...) adalah false). Hanya-baca boolean.

--------------------

Jika label data terlihat Anda dapat menyembunyikannya dengan metode Hide(). Tetapi jika label data tidak terlihat (IsVisible false) Anda dapat membuat label data terlihat dengan mengatur Show\*-flags (ShowValue, ...) ke keadaan true.

**Mengembalikan:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Menyembunyikan label data dengan mengatur semua Show\*-flags (ShowValue, ...) ke keadaan false. IsVisible akan menjadi false setelah ini.

--------------------

Jika label data tidak terlihat (IsVisible false) Anda dapat membuat label data terlihat dengan mengatur Show\*-flags (ShowValue, ...) ke keadaan true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Mengembalikan format label data. Hanya-baca [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Mengembalikan:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Mendapatkan atau mengatur sel data workbook. Diterapkan jika properti IDataLabelFormat.ShowLabelValueFromCell bernilai true.

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Mendapatkan atau mengatur sel data workbook. Diterapkan jika properti IDataLabelFormat.ShowLabelValueFromCell bernilai true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Mengembalikan teks label aktual berdasarkan pengaturan DataLabelFormat atau nilai TextFrameForOverriding.Text.

**Mengembalikan:**
java.lang.String - String teks label aktual
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

Mendapatkan atau mengatur tipe bentuk label data. Mengembalikan [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) jika tidak ada bentuk yang didefinisikan.

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Atur tipe bentuk label data pertama menjadi Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```

**Mengembalikan:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

Mendapatkan atau mengatur tipe bentuk label data. Mengembalikan [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) jika tidak ada bentuk yang didefinisikan.

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Atur tipe bentuk label data pertama menjadi Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |