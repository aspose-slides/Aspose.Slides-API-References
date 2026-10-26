---
title: ChartDataPointCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili kumpulan titik data seri.
type: docs
url: /id/com.aspose.slides/chartdatapointcollection/
---
**Warisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

Mewakili koleksi titik data seri.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan titik data seri berdasarkan indeks (nomor urutnya dalam koleksi ini). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Mengembalikan indeks (nomor urut) titik data dalam koleksi ini. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya ada dalam objek properti XValue titik data. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya ada dalam objek properti XValue titik data. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya ada dalam objek properti YValue titik data. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya ada dalam objek properti YValue titik data. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya ada dalam objek properti BubbleSize titik data. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya ada dalam objek properti BubbleSize titik data. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya ada dalam objek properti Value titik data. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya ada dalam objek properti Value titik data. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Menentukan jenis nilai dalam daftar properti ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Jika koleksi sudah berisi titik data dengan indeks index maka mengembalikan titik data tersebut. |
| [size()](#size--) | Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman terhadap thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Menghapus nilai yang ditentukan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang diberikan. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Mengembalikan titik data seri berdasarkan indeks (nomor urutnya dalam koleksi ini).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

Mengembalikan indeks (nomor urut) titik data dalam koleksi ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Mengembalikan:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya ada dalam objek properti XValue titik data. Dengan kata lain, ini menentukan tipe nilai dari properti ChartDataPoint.XValue.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Mengembalikan:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya ada dalam objek properti XValue titik data. Dengan kata lain, ini menentukan tipe nilai dari properti ChartDataPoint.XValue.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya ada dalam objek properti YValue titik data. Dengan kata lain, ini menentukan tipe nilai dari properti ChartDataPoint.YValue.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Mengembalikan:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya ada dalam objek properti YValue titik data. Dengan kata lain, ini menentukan tipe nilai dari properti ChartDataPoint.YValue.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya ada dalam objek properti BubbleSize titik data. Dengan kata lain, ini menentukan tipe nilai dari properti ChartDataPoint.BubbleSize.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Mengembalikan:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya ada dalam objek properti BubbleSize titik data. Dengan kata lain, ini menentukan tipe nilai dari properti ChartDataPoint.BubbleSize.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya ada dalam objek properti Value titik data. Dengan kata lain, ini menentukan tipe nilai dari properti ChartDataPoint.Value.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Mengembalikan:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya ada dalam objek properti Value titik data. Dengan kata lain, ini menentukan tipe nilai dari properti ChartDataPoint.Value.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Menentukan jenis nilai dalam daftar properti ChartDataPoint.ErrorBarsCustomValues. Baca-saja [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Mengembalikan:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Jika koleksi sudah berisi titik data dengan indeks index maka mengembalikan titik data tersebut. Jika koleksi tidak berisi titik data dengan indeks index==N (ketika jumlah titik data dalam koleksi ini kurang atau sama dengan N) maka menambahkan titik data yang kurang dan mengembalikan yang terakhir (yang memiliki indeks diminta). Misalnya, indeks koleksi adalah \{0, 1, 2\}, dan indeks yang diminta adalah 5. Maka metode menambahkan titik data yang kurang: \{0, 1, 2, 3, 4, 5\}. Dan mengembalikan titik data dengan indeks 5.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | long | Indeks. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Mengembalikan titik data dengan indeks yang diminta.
### size() {#size--}
```
public final int size()
```

Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. Baca-saja int.

**Mengembalikan:**
int
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Menyalin ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array tujuan penyalinan. |
| arrayIndex | int | Indeks mulai menyalin. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman terhadap thread). Baca-saja boolean.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Baca-saja Object.

**Mengembalikan:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Sebuah java.util.Iterator untuk seluruh koleksi.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Stock (lihat juga metode [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai titik data. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```
Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Stock (lihat juga [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai titik data. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Line (lihat juga [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai titik data. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Line (lihat juga [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai titik data. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Scatter (lihat juga [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue titik data |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Scatter (lihat juga [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | XValue titik data |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Scatter (lihat juga [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | XValue titik data |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Scatter (lihat juga [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue titik data |
| yValue | double | YValue titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Scatter (lihat juga [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | XValue titik data |
| yValue | double | YValue titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Scatter (lihat juga [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | XValue titik data |
| yValue | double | YValue titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Radar (lihat juga [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Radar (lihat juga [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Column atau Bar (lihat juga [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) dan [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Column atau Bar (lihat juga [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) dan [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Area (lihat juga [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Area (lihat juga [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Pie (lihat juga [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Pie (lihat juga [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Doughnut (lihat juga [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Doughnut (lihat juga [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Bubble (lihat juga [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue titik data |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue titik data |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Bubble (lihat juga [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | XValue titik data |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue titik data |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Bubble (lihat juga [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | XValue titik data |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue titik data |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Bubble (lihat juga [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue titik data |
| yValue | double | YValue titik data |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Bubble (lihat juga [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | XValue titik data |
| yValue | double | YValue titik data |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize titik data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Bubble (lihat juga [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) metode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | Titik data XValue |
| yValue | double | Titik data YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Bubble (lihat juga metode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data YValue |
| bubbleSize | double | Titik data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Bubble (lihat juga metode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | Titik data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data YValue |
| bubbleSize | double | Titik data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Bubble (lihat juga metode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | Titik data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data YValue |
| bubbleSize | double | Titik data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Bubble (lihat juga metode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data XValue |
| yValue | double | Titik data YValue |
| bubbleSize | double | Titik data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Bubble (lihat juga metode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | Titik data XValue |
| yValue | double | Titik data YValue |
| bubbleSize | double | Titik data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Bubble (lihat juga metode [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | Titik data XValue |
| yValue | double | Titik data YValue |
| bubbleSize | double | Titik data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Surface (lihat juga metode [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType adalah salah satu subtipe Surface (lihat juga metode [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Titik data Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type adalah Sunburst.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data SizeValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type adalah Treemap.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data SizeValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type adalah BoxAndWhisker.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type adalah Waterfall.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type adalah Histogram.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type adalah Funnel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type adalah Map.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Map, 50, 50, 500, 400, false);
>      IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>      IChartSeries series = chart.getChartData().getSeries().add(ChartType.Map);
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B2", 5));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B3", 1));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B4", 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data ColorValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### clear() {#clear--}
```
public final void clear()
```

Menghapus semua elemen dari koleksi.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

Menghapus nilai yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Nilai. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus elemen pada indeks yang diberikan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks titik data yang akan dihapus. |