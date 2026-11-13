---
title: DataLabelCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili label seri.
type: docs
url: /id/com.aspose.slides/datalabelcollection/
---
**Warisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Mewakili label seri.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getChart()](#getChart--) | Mengembalikan chart induk. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [isVisible()](#isVisible--) | False berarti data label tidak terlihat secara default (dan semua Show\*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat bernilai false). |
| [hide()](#hide--) | Membuat data label tersembunyi secara default dengan mengatur semua Show\*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat ke keadaan false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Mendapatkan jumlah data label yang terlihat dalam koleksi. |
| [getCount()](#getCount--) | Mendapatkan jumlah semua data label dalam koleksi. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Mendapatkan format data label default. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Mewakili format leader lines data label. |
| [getParentSeries()](#getParentSeries--) | Mendapatkan seri induk. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Mengembalikan indeks DataLabel yang ditentukan dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan data label untuk titik data dengan indeks yang ditentukan. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Mendapatkan atau mengatur tipe bentuk default untuk data label. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Mendapatkan atau mengatur tipe bentuk default untuk data label. |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari FillFormat. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Mengembalikan chart induk. **Baca-saja** [IChart](../../com.aspose.slides/ichart).

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator for the entire collection.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False berarti data label tidak terlihat secara default (dan semua Show\*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat bernilai false). **Baca-saja** boolean.

--------------------

Jika data label terlihat secara default, Anda dapat membuatnya tersembunyi secara default dengan metode Hide(). Tetapi jika data label tidak terlihat secara default (IsVisible false), Anda dapat membuat data label "terlihat secara default" dengan mengatur Show\*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat ke keadaan true.

**Mengembalikan:**
boolean

### hide() {#hide--}
```
public final void hide()
```

Membuat data label tersembunyi secara default dengan mengatur semua Show\*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat ke keadaan false. IsVisible akan menjadi false setelah ini.

--------------------

Jika data label tidak terlihat secara default (IsVisible false), Anda dapat membuat data label "terlihat secara default" dengan mengatur Show\*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat ke keadaan true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Mendapatkan jumlah data label yang terlihat dalam koleksi. **Baca-saja** int.

**Mengembalikan:**
int

### getCount() {#getCount--}
```
public final int getCount()
```

Mendapatkan jumlah semua data label dalam koleksi. **Baca-saja** int.

**Mengembalikan:**
int

### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Mendapatkan format data label default. **Baca-saja** [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Mengembalikan:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

Mewakili format leader lines data label. **Baca-saja** [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Mendapatkan seri induk. **Baca-saja** [IChartSeries](../../com.aspose.slides/ichartseries).

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

Mengembalikan indeks DataLabel yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel untuk dicari. |

**Mengembalikan:**
int - Index of a DataLabel or -1 if DataLabel not from this collection.

### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Mendapatkan data label untuk titik data dengan indeks yang ditentukan.

--------------------

Cara alternatif untuk mengakses data label adalah: - series.getDataPoints().get_Item(i).getLabel() - mengelola properti label.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```

Mendapatkan atau mengatur tipe bentuk default untuk data label. Mengembalikan [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) jika tidak ada bentuk yang didefinisikan.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Atur tipe bentuk semua label data pada seri pertama menjadi Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Menetapkan properti ini juga mengatur properti IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) untuk semua data label dalam koleksi ke nilai yang sama.

**Mengembalikan:**
int

### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```

Mendapatkan atau mengatur tipe bentuk default untuk data label. Mengembalikan [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) jika tidak ada bentuk yang didefinisikan.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Atur tipe bentuk semua label data pada seri pertama menjadi Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Menetapkan properti ini juga mengatur properti IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) untuk semua data label dalam koleksi ke nilai yang sama.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide induk dari FillFormat. **Baca-saja** [BaseSlide](../../com.aspose.slides/baseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk dari FillFormat. **Baca-saja** [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)