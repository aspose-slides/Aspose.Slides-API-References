---
title: DataLabelCollection
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili label seri.
type: docs
url: /id/com.aspose.slides/datalabelcollection/
---
**Pewarisan:**
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
| [getChart()](#getChart--) | Returns the parent chart. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [isVisible()](#isVisible--) | False means that data label is not visible by default (and so all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). |
| [hide()](#hide--) | Make data label hidden by default by setting all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to false state. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Gets the number of visible data labels in the collection. |
| [getCount()](#getCount--) | Gets the number of all data labels in the collection. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Gets the default data label format. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Represents data labels leader lines format. |
| [getParentSeries()](#getParentSeries--) | Gets the parent series. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Returns an index of the specified DataLabel in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the data label for the data point with the specified index. |
| [getSlide()](#getSlide--) | Returns the parent slide of a FillFormat. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Mengembalikan chart induk. Hanya-baca [IChart](../../com.aspose.slides/ichart).

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

False berarti label data tidak terlihat secara default (dan semua Show\*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat adalah false). Boolean hanya-baca.

--------------------

Jika label data terlihat secara default, Anda dapat membuatnya tersembunyi secara default dengan metode Hide(). Tetapi jika label data tidak terlihat secara default (IsVisible bernilai false), Anda dapat membuat label data "terlihat secara default" dengan mengatur Show\*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat ke keadaan true.

**Mengembalikan:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Membuat label data tersembunyi secara default dengan mengatur semua Show\*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat ke keadaan false. IsVisible akan menjadi false setelah ini.

--------------------

Jika label data tidak terlihat secara default (IsVisible bernilai false), Anda dapat membuat label data "terlihat secara default" dengan mengatur Show\*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat ke keadaan true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Mendapatkan jumlah label data yang terlihat dalam koleksi. int hanya-baca.

**Mengembalikan:**
int
### getCount() {#getCount--}
```
public final int getCount()
```

Mendapatkan jumlah semua label data dalam koleksi. int hanya-baca.

**Mengembalikan:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Mendapatkan format label data default. Hanya-baca [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Mengembalikan:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
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

Mendapatkan seri induk. Hanya-baca [IChartSeries](../../com.aspose.slides/ichartseries).

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

Mengembalikan indeks DataLabel yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel untuk dicari. |

**Mengembalikan:**
int - Indeks DataLabel atau -1 jika DataLabel bukan dari koleksi ini.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Mendapatkan label data untuk titik data dengan indeks yang ditentukan.

--------------------

Cara alternatif untuk mengakses label data adalah: - series.getDataPoints().get_Item(i).getLabel() - mengelola properti label.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide induk dari sebuah FillFormat. Hanya-baca [BaseSlide](../../com.aspose.slides/baseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk dari sebuah FillFormat. Hanya-baca [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)