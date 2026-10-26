---
title: IChartDataPointCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi poin data seri.
type: docs
url: /id/com.aspose.slides/ichartdatapointcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

Mewakili kumpulan poin data seri.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan poin data seri berdasarkan indeks (nomor urutnya dalam koleksi ini). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Mengembalikan indeks (nomor urut dalam koleksi ini) dari poin data dalam koleksi ini. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual dalam objek properti XValue pada poin data. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual dalam objek properti XValue pada poin data. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual dalam objek properti YValue pada poin data. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual dalam objek properti YValue pada poin data. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual dalam objek properti BubbleSize pada poin data. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual dalam objek properti BubbleSize pada poin data. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual dalam objek properti Value pada poin data. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual dalam objek properti Value pada poin data. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Menentukan jenis nilai dalam daftar properti ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Jika koleksi sudah berisi poin data dengan indeks index, maka mengembalikan poin data tersebut. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Membuat poin data baru dan menambahkannya ke akhir koleksi. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Menghapus nilai yang ditentukan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang diberikan. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Mengembalikan poin data seri berdasarkan indeks (nomor urutnya dalam koleksi ini).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

Mengembalikan indeks (nomor urut dalam koleksi ini) dari poin data dalam koleksi ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Mengembalikan:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual dalam objek properti XValue pada poin data. Dengan kata lain, ini menentukan jenis nilai properti ChartDataPointEx.XValue.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Mengembalikan:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual dalam objek properti XValue pada poin data. Dengan kata lain, ini menentukan jenis nilai properti ChartDataPointEx.XValue.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual dalam objek properti YValue pada poin data. Dengan kata lain, ini menentukan jenis nilai properti ChartDataPointEx.YValue.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Mengembalikan:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual dalam objek properti YValue pada poin data. Dengan kata lain, ini menentukan jenis nilai properti ChartDataPointEx.YValue.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual dalam objek properti BubbleSize pada poin data. Dengan kata lain, ini menentukan jenis nilai properti ChartDataPointEx.BubbleSize.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Mengembalikan:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceForBubbleSizes(int value)
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual dalam objek properti BubbleSize pada poin data. Dengan kata lain, ini menentukan jenis nilai properti ChartDataPointEx.BubbleSize.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual dalam objek properti Value pada poin data. Dengan kata lain, ini menentukan jenis nilai properti ChartDataPoint.Value.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Mengembalikan:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual dalam objek properti Value pada poin data. Dengan kata lain, ini menentukan jenis nilai properti ChartDataPoint.Value.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Menentukan jenis nilai dalam daftar properti ChartDataPoint.ErrorBarsCustomValues. Baca-saja [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Mengembalikan:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Jika koleksi sudah berisi poin data dengan indeks index, maka mengembalikan poin data tersebut. Jika koleksi tidak berisi poin data dengan indeks index==N (ketika jumlah poin data dalam koleksi ini kurang atau sama dengan N), maka menambahkan poin data yang kurang dan mengembalikan yang terakhir (yang memiliki indeks diminta). Sebagai contoh, indeks koleksi adalah \{0, 1, 2\}, dan indeks diminta adalah 5. Maka metode menambahkan poin data yang kurang: \{0, 1, 2, 3, 4, 5\}. Dan mengembalikan poin data dengan indeks 5.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | long | Indeks. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Mengembalikan poin data dengan indeks yang diminta.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Stock (lihat juga metode ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai Poin Data. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Stock (lihat juga metode ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai Poin Data. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Line (lihat juga metode ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai Poin Data. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Line (lihat juga metode ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai Poin Data. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Scatter (lihat juga metode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data YValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Scatter (lihat juga metode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | Poin data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data YValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Scatter (lihat juga metode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | Poin data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data YValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Scatter (lihat juga metode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data XValue |
| yValue | double | Poin data YValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Scatter (lihat juga metode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | Poin data XValue |
| yValue | double | Poin data YValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Scatter (lihat juga metode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | Poin data XValue |
| yValue | double | Poin data YValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Radar (lihat juga metode ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai Poin Data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Radar (lihat juga metode ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai Poin Data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Column atau Bar (lihat juga metode ChartTypeCharacterizer.IsChartTypeColumn(ChartType) dan ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai Poin Data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Column atau Bar (lihat juga metode ChartTypeCharacterizer.IsChartTypeColumn(ChartType) dan ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai Poin Data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Area (lihat juga metode ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai Poin Data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Area (lihat juga metode ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai Poin Data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Pie (lihat juga metode ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai Poin Data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Pie (lihat juga metode ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai Poin Data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Doughnut (lihat juga metode ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai Poin Data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Doughnut (lihat juga metode ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai Poin Data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | Poin data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | Poin data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data XValue |
| yValue | double | Poin data YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | Poin data XValue |
| yValue | double | Poin data YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | Poin data XValue |
| yValue | double | Poin data YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data YValue |
| bubbleSize | double | Poin data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | Poin data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data YValue |
| bubbleSize | double | Poin data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | Poin data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data YValue |
| bubbleSize | double | Poin data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Poin data XValue |
| yValue | double | Poin data YValue |
| bubbleSize | double | Poin data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | Poin data XValue |
| yValue | double | Poin data YValue |
| bubbleSize | double | Poin data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | Poin data XValue |
| yValue | double | Poin data YValue |
| bubbleSize | double | Poin data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Surface (lihat juga metode ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai Poin Data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract I.......



```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Surface (lihat juga metode ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai Poin Data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type-nya Sunburst.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai SizeValue Poin Data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type-nya Waterfall.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai poin data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type-nya BoxAndWhisker.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai Poin Data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type-nya Treemap.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai SizeValue Poin Data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type-nya Histogram.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai poin data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type-nya Funnel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai poin data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Membuat poin data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type-nya Map.

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
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai ColorValue Poin Data |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Poin data baru.
### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua elemen dari koleksi.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

Menghapus nilai yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Nilai. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus elemen pada indeks yang diberikan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks poin data yang akan dihapus. |