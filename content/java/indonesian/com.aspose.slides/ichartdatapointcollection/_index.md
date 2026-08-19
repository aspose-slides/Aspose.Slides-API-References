---
title: IChartDataPointCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi titik data seri.
type: docs
url: /id/com.aspose.slides/ichartdatapointcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

Mewakili koleksi titik data seri.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan titik data seri berdasarkan indeks (nomor seri dalam koleksi ini). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Mengembalikan indeks (nomor seri dalam koleksi ini) dari titik data dalam koleksi ini. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual pada objek properti XValue titik data. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual pada objek properti XValue titik data. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual pada objek properti YValue titik data. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual pada objek properti YValue titik data. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual pada objek properti BubbleSize titik data. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual pada objek properti BubbleSize titik data. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual pada objek properti Value titik data. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual pada objek properti Value titik data. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Menentukan tipe nilai dalam daftar properti ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Jika koleksi sudah berisi titik data dengan indeks index maka mengembalikan titik data tersebut. |
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
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Membuat titik data baru dan menambahkannya ke akhir koleksi. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Menghapus nilai yang ditentukan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang diberikan. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Mengembalikan titik data seri berdasarkan indeks (nomor seri dalam koleksi ini).

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

Mengembalikan indeks (nomor seri dalam koleksi ini) dari titik data dalam koleksi ini.

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

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual pada objek properti XValue titik data. Dengan kata lain ini menentukan tipe nilai properti ChartDataPointEx.XValue.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Mengembalikan:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual pada objek properti XValue titik data. Dengan kata lain ini menentukan tipe nilai properti ChartDataPointEx.XValue.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual pada objek properti YValue titik data. Dengan kata lain ini menentukan tipe nilai properti ChartDataPointEx.YValue.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Mengembalikan:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual pada objek properti YValue titik data. Dengan kata lain ini menentukan tipe nilai properti ChartDataPointEx.YValue.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual pada objek properti BubbleSize titik data. Dengan kata lain ini menentukan tipe nilai properti ChartDataPointEx.BubbleSize.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Mengembalikan:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual pada objek properti BubbleSize titik data. Dengan kata lain ini menentukan tipe nilai properti ChartDataPointEx.BubbleSize.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual pada objek properti Value titik data. Dengan kata lain ini menentukan tipe nilai properti ChartDataPoint.Value.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Mengembalikan:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual pada objek properti Value titik data. Dengan kata lain ini menentukan tipe nilai properti ChartDataPoint.Value.Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Menentukan tipe nilai dalam daftar properti ChartDataPoint.ErrorBarsCustomValues. Baca-saja [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Mengembalikan:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Jika koleksi sudah berisi titik data dengan indeks index maka mengembalikan titik data tersebut. Jika koleksi tidak berisi titik data dengan indeks index==N (ketika jumlah titik data dalam koleksi ini kurang atau sama dengan N) maka menambahkan titik data yang kurang dan mengembalikan yang terakhir (yang memiliki indeks yang diminta). Sebagai contoh, indeks koleksi adalah \{0, 1, 2\}, dan indeks yang diminta adalah 5. Maka metode menambahkan titik data yang kurang: \{0, 1, 2, 3, 4, 5\}. Dan mengembalikan titik data dengan indeks 5.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | long | Indeks. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Mengembalikan titik data dengan indeks yang diminta.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Stock (lihat juga metode ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai titik data. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Stock (lihat juga metode ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai titik data. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Line (lihat juga metode ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nilai titik data. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Line (lihat juga metode ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Nilai titik data. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Scatter (lihat juga metode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data YValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Scatter (lihat juga metode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | Titik data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data YValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Scatter (lihat juga metode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | Titik data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data YValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Scatter (lihat juga metode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data XValue |
| yValue | double | Titik data YValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Scatter (lihat juga metode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | Titik data XValue |
| yValue | double | Titik data YValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Scatter (lihat juga metode ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | Titik data XValue |
| yValue | double | Titik data YValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Radar (lihat juga metode ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Radar (lihat juga metode ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Titik data Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Column atau Bar (lihat juga metode ChartTypeCharacterizer.IsChartTypeColumn(ChartType) dan ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Column atau Bar (lihat juga metode ChartTypeCharacterizer.IsChartTypeColumn(ChartType) dan ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Titik data Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Area (lihat juga metode ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Area (lihat juga metode ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Titik data Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Pie (lihat juga metode ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Pie (lihat juga metode ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Titik data Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Doughnut (lihat juga metode ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Doughnut (lihat juga metode ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Titik data Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | Titik data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | Titik data XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data XValue |
| yValue | double | Titik data YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | Titik data XValue |
| yValue | double | Titik data YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Titik data BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data baru.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya adalah salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```
Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Bubble (lihat juga metode ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Surface (lihat juga metode ChartTypeCharacterizer.IsChartTypeSurface(ChartType) method).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chartType-nya merupakan salah satu subtipe Surface (lihat juga metode ChartTypeCharacterizer.IsChartTypeSurface(ChartType) method).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double | Data point Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type-nya adalah Sunburst.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point SizeValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type-nya adalah Waterfall.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type-nya adalah BoxAndWhisker.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type-nya adalah Treemap.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point SizeValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type-nya adalah Histogram.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type-nya adalah Funnel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point value |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```


Membuat titik data baru dan menambahkannya ke akhir koleksi. Berlaku untuk seri yang chart type-nya adalah Map.

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
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point ColorValue |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
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
| index | int | Indeks titik data yang akan dihapus. |
