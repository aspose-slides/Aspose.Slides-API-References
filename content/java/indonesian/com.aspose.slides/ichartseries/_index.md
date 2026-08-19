---
title: IChartSeries
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili seri diagram.
type: docs
url: /id/com.aspose.slides/ichartseries/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Mewakili seri diagram.
## Metode

| Method | Description |
| --- | --- |
| [getExplosion()](#getExplosion--) | Jarak sebuah irisan pai terbuka dari pusat diagram pai dinyatakan sebagai persentase dari diameter pai. |
| [setExplosion(int value)](#setExplosion-int-) | Jarak sebuah irisan pai terbuka dari pusat diagram pai dinyatakan sebagai persentase dari diameter pai. |
| [getSmooth()](#getSmooth--) | Mewakili pelunakan kurva. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Mewakili pelunakan kurva. |
| [getMarker()](#getMarker--) | Mengembalikan penanda seri. |
| [getBar3DShape()](#getBar3DShape--) | Menentukan bentuk seri pada diagram batang 3-D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Menentukan bentuk seri pada diagram batang 3-D. |
| [getName()](#getName--) | Mengembalikan nama seri. |
| [getDataPoints()](#getDataPoints--) | Mengembalikan koleksi titik data dari seri ini. |
| [getType()](#getType--) | Mengembalikan tipe dari seri ini. |
| [setType(int value)](#setType-int-) | Mengembalikan tipe dari seri ini. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Mengembalikan grup seri induk. |
| [getFormat()](#getFormat--) | Mengembalikan format seri. |
| [getOrder()](#getOrder--) | Mengembalikan urutan seri. |
| [setOrder(int value)](#setOrder-int-) | Mengembalikan urutan seri. |
| [getLabels()](#getLabels--) | Mengembalikan Label seri. |
| [getTrendLines()](#getTrendLines--) | Koleksi garis tren seri Baca-saja [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Mewakili ErrorBars seri dengan arah X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Mewakili ErrorBars seri dengan arah Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Menunjukkan apakah seri ini dipetakan pada sumbu nilai kedua. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Menunjukkan apakah seri ini dipetakan pada sumbu nilai kedua. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Mengembalikan atau mengatur format angka untuk nilai seri. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Mengembalikan atau mengatur format angka untuk nilai seri. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Mengembalikan atau mengatur format angka untuk nilai x seri. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Mengembalikan atau mengatur format angka untuk nilai x seri. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Mengembalikan atau mengatur format angka untuk nilai y seri. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Mengembalikan atau mengatur format angka untuk nilai y seri. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Mengembalikan atau mengatur format angka untuk ukuran gelembung seri. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Mengembalikan atau mengatur format angka untuk ukuran gelembung seri. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Menentukan bar, kolom, atau seri gelembung harus membalikkan warnanya jika nilainya negatif. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Menentukan bar, kolom, atau seri gelembung harus membalikkan warnanya jika nilainya negatif. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Menentukan warna padat terbalik untuk seri. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Mewakili entri legenda yang terkait dengan seri ini Baca-saja [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Mengembalikan warna otomatis seri berdasarkan indeks seri dan gaya diagram. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Mewakili titik dalam. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Mewakili titik dalam. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Mewakili titik outlier. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Mewakili titik outlier. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Mewakili penanda rata-rata. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Mewakili penanda rata-rata. |
| [getShowMeanLine()](#getShowMeanLine--) | Mewakili penanda rata-rata. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Mewakili penanda rata-rata. |
| [getQuartileMethod()](#getQuartileMethod--) | Mewakili metode kuartil. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Mewakili metode kuartil. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Mewakili garis penghubung. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Mewakili garis penghubung. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Mewakili tata letak label kategori induk. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Mewakili tata letak label kategori induk. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Menentukan faktor skala untuk diagram gelembung (dapat antara 0 hingga 300 persen dari ukuran default). |
| [hasUpDownBars()](#hasUpDownBars--) | Menentukan apakah diagram Garis atau Saham memiliki batang atas/bawah. |
| [getGapWidth()](#getGapWidth--) | Menentukan ruang antara kelompok bar atau kolom, sebagai persentase lebar bar atau kolom. |
| [getGapDepth()](#getGapDepth--) | Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam diagram 3D. |
| [isColorVaried()](#isColorVaried--) | Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. |
| [hasSeriesLines()](#hasSeriesLines--) | Menentukan apakah ada garis seri untuk seri ini dan seri terkait. |
| [getOverlap()](#getOverlap--) | Menentukan seberapa banyak batang dan kolom tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Menentukan ukuran pai atau bar kedua pada diagram pai-dalam-pai atau bar-dalam-pai, sebagai persentase ukuran pai pertama (dapat antara 5 hingga 200 persen). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau bar kedua pada diagram pai-dalam-pai atau bar-dalam-pai. |
| [getPieSplitBy()](#getPieSplitBy--) | Menentukan cara menentukan titik data mana yang berada di pai atau bar kedua pada diagram pai-dalam-pai atau bar-dalam-pai. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Menentukan ukuran lubang dalam diagram donat (dapat antara 10 hingga 90 persen dari ukuran area plot). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Menentukan sudut irisan pertama pada diagram pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Informasi pembagian kustom untuk diagram pai-dalam-pai atau bar-dalam-pai dengan pembagian kustom. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Jarak sebuah irisan pai terbuka dari pusat diagram pai dinyatakan sebagai persentase dari diameter pai. Baca/tulis int.

**Mengembalikan:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Jarak sebuah irisan pai terbuka dari pusat diagram pai dinyatakan sebagai persentase dari diameter pai. Baca/tulis int.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Mewakili pelunakan kurva. True jika pelunakan kurva diaktifkan untuk diagram garis atau diagram sebar. Hanya berlaku untuk diagram garis dan sebar yang terhubung oleh garis. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Mewakili pelunakan kurva. True jika pelunakan kurva diaktifkan untuk diagram garis atau diagram sebar. Hanya berlaku untuk diagram garis dan sebar yang terhubung oleh garis. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Mengembalikan penanda seri. Baca-saja [IMarker](../../com.aspose.slides/imarker).

**Mengembalikan:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Menentukan bentuk seri pada diagram batang 3-D. Perubahan nilai properti ini dapat menyebabkan perubahan otomatis Tipe seri. Baca/tulis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Mengembalikan:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Menentukan bentuk seri pada diagram batang 3-D. Perubahan nilai properti ini dapat menyebabkan perubahan otomatis Tipe seri. Baca/tulis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Mengembalikan nama seri. Baca-saja [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Mengembalikan:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Mengembalikan koleksi titik data dari seri ini. Baca-saja [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Mengembalikan:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public abstract int getType()
```

Mengembalikan tipe dari seri ini. Baca/tulis [ChartType](../../com.aspose.slides/charttype).

**Mengembalikan:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Mengembalikan tipe dari seri ini. Baca/tulis [ChartType](../../com.aspose.slides/charttype).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Mengembalikan grup seri induk. Baca-saja [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Mengembalikan:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Mengembalikan format seri. Baca-saja [IFormat](../../com.aspose.slides/iformat).

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Mengembalikan urutan seri. Baca/tulis int.

**Mengembalikan:**
int
### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Mengembalikan urutan seri. Baca/tulis int.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Mengembalikan Label seri. Baca-saja [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Mengembalikan:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Koleksi garis tren seri Baca-saja [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Mengembalikan:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Mewakili ErrorBars seri dengan arah X. Baca-saja [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars dengan arah X tersedia untuk seri tipe area, bar, scatter dan bubble. Untuk tipe diagram lainnya properti ini mengembalikan null (termasuk diagram 3D). Jika menggunakan nilai kustom, gunakan koleksi DataPoints untuk menentukan nilai (dengan properti ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).
**Mengembalikan:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Mewakili ErrorBars seri dengan arah Y. Baca-saja [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars dengan arah Y tersedia untuk seri tipe area, bar, line, scatter dan bubble. Untuk tipe diagram lainnya properti ini mengembalikan null (termasuk diagram 3D). Jika menggunakan nilai kustom, gunakan koleksi DataPoints untuk menentukan nilai (dengan properti ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).
**Mengembalikan:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Menunjukkan apakah seri ini dipetakan pada sumbu nilai kedua. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Menunjukkan apakah seri ini dipetakan pada sumbu nilai kedua. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Mengembalikan atau mengatur format angka untuk nilai seri. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Mengembalikan atau mengatur format angka untuk nilai seri. Baca/tulis String.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Mengembalikan atau mengatur format angka untuk nilai x seri. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Mengembalikan atau mengatur format angka untuk nilai x seri. Baca/tulis String.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Mengembalikan atau mengatur format angka untuk nilai y seri. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Mengembalikan atau mengatur format angka untuk nilai y seri. Baca/tulis String.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Mengembalikan atau mengatur format angka untuk ukuran gelembung seri. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Mengembalikan atau mengatur format angka untuk ukuran gelembung seri. Baca/tulis String.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Menentukan bar, kolom, atau seri gelembung harus membalikkan warnanya jika nilainya negatif. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Menentukan bar, kolom, atau seri gelembung harus membalikkan warnanya jika nilainya negatif. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Menentukan warna padat terbalik untuk seri. Untuk menerapkan pengaturan warna, set format seri FillType ke FillType.Solid. Baca/tulis [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Mewakili entri legenda yang terkait dengan seri ini Baca-saja [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Mengembalikan:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
Mengembalikan warna otomatis dari seri berdasarkan indeks seri dan gaya diagram. Warna ini digunakan secara default jika FillType sama dengan NotDefined.

**Mengembalikan:**
java.awt.Color - Warna otomatis dari seri java.awt.Color
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Mewakili titik dalam. Benar jika titik dalam ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. boolean Baca/tulis.

**Mengembalikan:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Mewakili titik dalam. Benar jika titik dalam ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. boolean Baca/tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Mewakili titik outlier. Benar jika titik outlier ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. boolean Baca/tulis.

**Mengembalikan:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Mewakili titik outlier. Benar jika titik outlier ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. boolean Baca/tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Mewakili penanda rata-rata. Benar jika penanda rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. boolean Baca/tulis.

**Mengembalikan:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Mewakili penanda rata-rata. Benar jika penanda rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. boolean Baca/tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Mewakili penanda rata-rata. Benar jika garis rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. boolean Baca/tulis.

**Mengembalikan:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Mewakili penanda rata-rata. Benar jika garis rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. boolean Baca/tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Mewakili metode kuartil. Hanya berlaku untuk diagram BoxAndWhisker.

**Mengembalikan:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Mewakili metode kuartil. Hanya berlaku untuk diagram BoxAndWhisker.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Mewakili garis penghubung. Hanya berlaku untuk diagram Waterfall.

**Mengembalikan:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Mewakili garis penghubung. Hanya berlaku untuk diagram Waterfall.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Mewakili tata letak label kategori induk. Hanya berlaku untuk diagram Treemap.

**Mengembalikan:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Mewakili tata letak label kategori induk. Hanya berlaku untuk diagram Treemap.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Menentukan faktor skala untuk diagram gelembung (dapat berada antara 0 dan 300 persen ukuran default). Ini bukan hanya properti dari seri ini tetapi juga semua seri dari grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini bersifat baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.BubbleSizeScale Baca/tulis untuk mengubah nilai.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.BubbleSizeScale.

**Mengembalikan:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Menentukan apakah diagram Line atau Stock memiliki batang naik/turun. Ini bukan hanya properti dari seri ini tetapi juga semua seri dari grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini bersifat baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.UpDownBars.HasUpDownBars Baca/tulis untuk mengubah nilai. Gunakan properti ParentSeriesGroup.UpDownBars untuk memformat batang naik/turun. boolean Baca-saja.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Mengembalikan:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Menentukan ruang antara klaster batang atau kolom, sebagai persentase lebar batang atau kolom. Ini bukan hanya properti dari seri ini tetapi juga semua seri dari grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini bersifat baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.GapWidth Baca/tulis untuk mengubah nilai. int Baca-saja.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.GapWidth.

**Mengembalikan:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam diagram 3D. Ini bukan hanya properti dari seri ini tetapi juga semua seri dari grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini bersifat baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.GapDepth Baca/tulis untuk mengubah nilai. int Baca-saja.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.GapDepth.

**Mengembalikan:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. Ini bukan hanya properti dari seri ini tetapi juga semua seri dari grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini bersifat baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.IsColorVaried Baca/tulis untuk mengubah nilai. boolean Baca-saja.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.IsColorVaried.

**Mengembalikan:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Menentukan apakah ada garis seri untuk seri ini dan seri terkait. Ini bukan hanya properti dari seri ini tetapi juga semua seri dari grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini bersifat baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.HasSeriesLines Baca/tulis untuk mengubah nilai. Gunakan properti ParentSeriesGroup.SeriesLinesFormat untuk memformat garis seri. boolean Baca-saja.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.HasSeriesLines.

**Mengembalikan:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Menentukan seberapa banyak batang dan kolom saling tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). Ini bukan hanya properti dari seri ini tetapi juga semua seri dari grup seri induk. Ini merupakan proyeksi properti yang sesuai dalam grup seri induk, sehingga properti ini bersifat baca-saja. Untuk mengubah nilai, gunakan properti ParentSeriesGroup.Overlap Baca/tulis. byte Baca-saja.

--------------------

Overlap menentukan tingkat tumpang tindih atau jarak antara batang dan kolom sebagai persentase lebar mereka: - -100%: Jarak maksimum (batang terpisah sepenuhnya). - 0%: Batang ditempatkan bersebelahan tanpa tumpang tindih atau jarak. - 100%: Tumpang tindih maksimum (batang saling menutupi sepenuhnya). Ini adalah proyeksi properti ParentSeriesGroup.Overlap.

**Mengembalikan:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Menentukan ukuran pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie, sebagai persentase ukuran pai pertama (bisa antara 5 dan 200 persen). Ini bukan hanya properti dari seri ini tetapi juga semua seri dari grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini bersifat baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.SecondPieSize Baca/tulis untuk mengubah nilai. int Baca-saja.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.SecondPieSize.

**Mengembalikan:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Ini bukan hanya properti dari seri ini tetapi juga semua seri dari grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini bersifat baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.PieSplitPosition Baca/tulis untuk mengubah nilai. double Baca-saja.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.PieSplitPosition.

**Mengembalikan:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Ini bukan hanya properti dari seri ini tetapi juga semua seri dari grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini bersifat baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.PieSplitBy Baca/tulis untuk mengubah nilai. [PieSplitType](../../com.aspose.slides/piesplittype) Baca-saja.

--------------------

1) Ini adalah proyeksi properti ParentSeriesGroup.PieSplitBy. 2) Jika nilai properti adalah PieSplitType.Custom maka Anda dapat mendefinisikan informasi split khusus dengan properti ParentSeriesGroup.PieSplitCustomPoints.

**Mengembalikan:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Menentukan ukuran lubang pada diagram donat (bisa antara 10 dan 90 persen ukuran area plot). Ini bukan hanya properti dari seri ini tetapi juga semua seri dari grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini bersifat baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.DoughnutHoleSize Baca/tulis untuk mengubah nilai. byte Baca-saja.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.DoughnutHoleSize.

**Mengembalikan:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Menentukan sudut irisan pertama pada diagram pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). Ini bukan hanya properti dari seri ini tetapi juga semua seri dari grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini bersifat baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.FirstSliceAngle Baca/tulis untuk mengubah nilai. int Baca-saja.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.FirstSliceAngle.

**Mengembalikan:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Informasi split khusus untuk diagram pie-of-pie atau bar-of-pie dengan split khusus. Berisi titik data yang harus digambar pada pai atau batang kedua dalam diagram pie-of-pie atau bar-of-pie. Ini bukan hanya properti dari seri ini tetapi juga semua seri dari grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Baca-saja [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.PieSplitCustomPoints.

**Mengembalikan:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. Ini adalah properti tidak hanya untuk series ini tetapi untuk semua series dari grup series induk - ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini bersifat baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup series induk. Gunakan properti ParentSeriesGroup.BubbleSizeRepresentation baca/tulis untuk mengubah nilai.

--------------------

Ini adalah proyeksi dari properti ParentSeriesGroup.BubbleSizeRepresentation.

**Mengembalikan:**
int