---
title: IDataLabelCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili label seri.
type: docs
url: /id/com.aspose.slides/idatalabelcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Mewakili label seri.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan label data untuk titik data dengan indeks yang ditentukan. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Mengembalikan format default semua label data dalam koleksi. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Mewakili format garis pemimpin label data. |
| [isVisible()](#isVisible--) | False berarti label data tidak terlihat secara default (dan semua flag Show\*-flags (ShowValue, ...) pada properti DefaultDataLabelFormat adalah false). |
| [hide()](#hide--) | Membuat label data tersembunyi secara default dengan mengatur semua flag Show\*-flags (ShowValue, ...) pada properti DefaultDataLabelFormat ke keadaan false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Mendapatkan jumlah label data yang terlihat dalam koleksi. |
| [getCount()](#getCount--) | Mendapatkan jumlah semua label data dalam koleksi. |
| [getParentSeries()](#getParentSeries--) | Mengembalikan seri diagram induk. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Mengembalikan indeks DataLabel yang ditentukan dalam koleksi. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Mendapatkan atau mengatur tipe bentuk default untuk label data. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Mendapatkan atau mengatur tipe bentuk default untuk label data. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Mendapatkan label data untuk titik data dengan indeks yang ditentukan.

--------------------

Cara alternatif untuk mengakses label data adalah: - getSeries().getDataPoints().get\_Item(i).getLabel() - mengelola properti label.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```


Mengembalikan format default semua label data dalam koleksi. Hanya-baca [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Mengembalikan:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```


Mewakili format garis pemimpin label data. Hanya-baca [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False berarti label data tidak terlihat secara default (dan semua flag Show\*-flags (ShowValue, ...) pada properti DefaultDataLabelFormat adalah false). Hanya-baca boolean.

--------------------

Jika label data terlihat secara default, Anda dapat menyembunyikannya secara default dengan metode Hide(). Tetapi jika label data tidak terlihat secara default (IsVisible bernilai false), Anda dapat membuat label data "terlihat secara default" dengan mengatur flag Show\*-flags (ShowValue, ...) pada properti DefaultDataLabelFormat ke keadaan true.

**Mengembalikan:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Membuat label data tersembunyi secara default dengan mengatur semua flag Show\*-flags (ShowValue, ...) pada properti DefaultDataLabelFormat ke keadaan false. IsVisible akan menjadi false setelah ini.

--------------------

Jika label data tidak terlihat secara default (IsVisible bernilai false), Anda dapat membuat label data "terlihat secara default" dengan mengatur flag Show\*-flags (ShowValue, ...) pada properti DefaultDataLabelFormat ke keadaan true.
### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


Mendapatkan jumlah label data yang terlihat dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


Mendapatkan jumlah semua label data dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


Mengembalikan seri diagram induk. Hanya-baca [IChartSeries](../../com.aspose.slides/ichartseries).

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```


Mengembalikan indeks DataLabel yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel yang dicari. |

**Mengembalikan:**
int - Indeks dari sebuah DataLabel atau -1 jika DataLabel tidak berasal dari koleksi ini.
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```


Mendapatkan atau mengatur tipe bentuk default untuk label data. Mengembalikan [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) jika tidak ada bentuk yang ditentukan.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Tetapkan tipe bentuk semua label data dalam seri pertama menjadi Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Mengatur properti ini juga mengatur properti IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) untuk semua label data dalam koleksi ke nilai yang sama.

**Mengembalikan:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```


Mendapatkan atau mengatur tipe bentuk default untuk label data. Mengembalikan [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) jika tidak ada bentuk yang ditentukan.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Tetapkan tipe bentuk semua label data dalam seri pertama menjadi Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Mengatur properti ini juga mengatur properti IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) untuk semua label data dalam koleksi ke nilai yang sama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |