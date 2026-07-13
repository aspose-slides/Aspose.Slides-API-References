---
title: IDataLabelCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
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

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan label data untuk titik data dengan indeks yang ditentukan. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Mengembalikan format default dari semua label data dalam koleksi. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Mewakili format garis pemimpin label data. |
| [isVisible()](#isVisible--) | False berarti label data tidak terlihat secara default (dan sehingga semua flag Show* (ShowValue, ...) pada properti DefaultDataLabelFormat bernilai false). |
| [hide()](#hide--) | Membuat label data tersembunyi secara default dengan mengatur semua flag Show* (ShowValue, ...) pada properti DefaultDataLabelFormat ke keadaan false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Mendapatkan jumlah label data yang terlihat dalam koleksi. |
| [getCount()](#getCount--) | Mendapatkan jumlah semua label data dalam koleksi. |
| [getParentSeries()](#getParentSeries--) | Mengembalikan seri chart induk. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Mengembalikan indeks dari DataLabel yang ditentukan dalam koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Mendapatkan label data untuk titik data dengan indeks yang ditentukan.

--------------------

Cara alternatif untuk mengakses label data adalah: - getSeries().getDataPoints().get_Item(i).getLabel() - mengelola properti label.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```


Mengembalikan format default dari semua label data dalam koleksi. Hanya baca [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Mengembalikan:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```


Mewakili format garis pemimpin label data. Hanya baca [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False berarti label data tidak terlihat secara default (dan sehingga semua flag Show* (ShowValue, ...) pada properti DefaultDataLabelFormat bernilai false). Hanya baca  boolean .

--------------------

Jika label data terlihat secara default Anda dapat membuatnya tersembunyi secara default dengan metode Hide(). Tetapi jika label data tidak terlihat secara default (IsVisible false) Anda dapat membuat label data "terlihat secara default" dengan mengatur flag Show* (ShowValue, ...) pada properti DefaultDataLabelFormat ke keadaan true.

**Mengembalikan:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Membuat label data tersembunyi secara default dengan mengatur semua flag Show* (ShowValue, ...) pada properti DefaultDataLabelFormat ke keadaan false. IsVisible akan menjadi false setelah ini.

--------------------

Jika label data tidak terlihat secara default (IsVisible false) Anda dapat membuat label data "terlihat secara default" dengan mengatur flag Show* (ShowValue, ...) pada properti DefaultDataLabelFormat ke keadaan true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


Mendapatkan jumlah label data yang terlihat dalam koleksi. Hanya baca  int .

**Mengembalikan:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


Mendapatkan jumlah semua label data dalam koleksi. Hanya baca  int .

**Mengembalikan:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


Mengembalikan seri chart induk. Hanya baca [IChartSeries](../../com.aspose.slides/ichartseries).

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```


Mengembalikan indeks dari DataLabel yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel untuk dicari. |

**Mengembalikan:**
int - Indeks dari DataLabel atau -1 jika DataLabel bukan dari koleksi ini.