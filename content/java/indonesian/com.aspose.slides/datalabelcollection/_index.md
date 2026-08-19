---
title: DataLabelCollection
second_title: Referensi API Aspose.Slides untuk Java
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
| [getChart()](#getChart--) | Mengembalikan chart induk. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [isVisible()](#isVisible--) | False berarti DataLabel tidak terlihat secara default (dan sehingga semua Show*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat bernilai false). |
| [hide()](#hide--) | Buat DataLabel tersembunyi secara default dengan mengatur semua Show*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat ke keadaan false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Mendapatkan jumlah DataLabel yang terlihat dalam koleksi. |
| [getCount()](#getCount--) | Mendapatkan jumlah semua DataLabel dalam koleksi. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Mendapatkan format DataLabel default. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Mewakili format leader lines DataLabel. |
| [getParentSeries()](#getParentSeries--) | Mendapatkan Series induk. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Mengembalikan indeks DataLabel yang ditentukan dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan DataLabel untuk data point dengan indeks yang ditentukan. |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari FillFormat. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```


Mengembalikan chart induk. Hanya baca [IChart](../../com.aspose.slides/ichart).

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```


Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - java.util.Iterator untuk seluruh koleksi.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


False berarti DataLabel tidak terlihat secara default (dan sehingga semua Show*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat bernilai false). Boolean hanya baca.

--------------------

Jika DataLabel terlihat secara default, Anda dapat menyembunyikannya secara default dengan metode Hide(). Namun jika DataLabel tidak terlihat secara default (IsVisible false), Anda dapat membuat DataLabel "terlihat secara default" dengan mengatur Show*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat ke keadaan true.

**Mengembalikan:**
boolean
### hide() {#hide--}
```
public final void hide()
```


Buat DataLabel tersembunyi secara default dengan mengatur semua Show*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat ke keadaan false. IsVisible akan menjadi false setelah ini.

--------------------

Jika DataLabel tidak terlihat secara default (IsVisible false), Anda dapat membuat DataLabel "terlihat secara default" dengan mengatur Show*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat ke keadaan true.
### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```


Mendapatkan jumlah DataLabel yang terlihat dalam koleksi. Int hanya baca.

**Mengembalikan:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Mendapatkan jumlah semua DataLabel dalam koleksi. Int hanya baca.

**Mengembalikan:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```


Mendapatkan format DataLabel default. Hanya baca [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Mengembalikan:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```


Mewakili format leader lines DataLabel. Hanya baca [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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


Mendapatkan Series induk. Hanya baca [IChartSeries](../../com.aspose.slides/ichartseries).

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
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel yang akan dicari. |

**Mengembalikan:**
int - Indeks DataLabel atau -1 jika DataLabel tidak berasal dari koleksi ini.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```


Mendapatkan DataLabel untuk data point dengan indeks yang ditentukan.

--------------------

Cara alternatif untuk mengakses DataLabel adalah: - series.getDataPoints().get_Item(i).getLabel() - mengelola properti label.

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


Mengembalikan slide induk dari FillFormat. Hanya baca [BaseSlide](../../com.aspose.slides/baseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Mengembalikan presentasi induk dari FillFormat. Hanya baca [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)