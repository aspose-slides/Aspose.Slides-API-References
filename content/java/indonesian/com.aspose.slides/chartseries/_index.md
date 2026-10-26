---
title: ChartSeries
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili seri diagram.
type: docs
url: /id/com.aspose.slides/chartseries/
---
**Warisan:**  
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**  
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject  
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Mewakili seri bagan.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Mengembalikan bagan induk. |
| [getExplosion()](#getExplosion--) | Jarak irisan pai terbuka dari pusat bagan pai dinyatakan sebagai persentase dari diameter pai. |
| [setExplosion(int value)](#setExplosion-int-) | Jarak irisan pai terbuka dari pusat bagan pai dinyatakan sebagai persentase dari diameter pai. |
| [getSmooth()](#getSmooth--) | Mewakili pelicinan kurva. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Mewakili pelicinan kurva. |
| [getName()](#getName--) | Mengembalikan nama seri. |
| [getDataPoints()](#getDataPoints--) | Mengembalikan koleksi titik data dari seri ini. |
| [getType()](#getType--) | Mengembalikan tipe seri ini. |
| [setType(int value)](#setType-int-) | Mengembalikan tipe seri ini. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Menunjukkan apakah seri ini dipetakan pada sumbu sekunder. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Menunjukkan apakah seri ini dipetakan pada sumbu sekunder. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Mengembalikan format seri. |
| [getOrder()](#getOrder--) | Mengembalikan urutan seri. |
| [setOrder(int value)](#setOrder-int-) | Mengembalikan urutan seri. |
| [getLabels()](#getLabels--) | Mengembalikan Label seri. |
| [getTrendLines()](#getTrendLines--) | Koleksi garis tren seri. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Mewakili ErrorBars seri dengan arah X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Mewakili ErrorBars seri dengan arah Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Mewakili entri legenda yang terkait dengan seri ini Hanya-baca [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Menentukan bentuk seri pada bagan batang 3-D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Menentukan bentuk seri pada bagan batang 3-D. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Menentukan bar, kolom, atau seri gelembung harus membalikkan warnanya bila nilai negatif. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Menentukan bar, kolom, atau seri gelembung harus membalikkan warnanya bila nilai negatif. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Menentukan warna padat terbalik untuk seri. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Mengembalikan warna otomatis seri berdasarkan indeks seri dan gaya bagan. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Mewakili titik dalam. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Mewakili titik dalam. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Mewakili titik outlier. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Mewakili titik outlier. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Mewakili penanda rata-rata. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Mewakili penanda rata-rata. |
| [getShowMeanLine()](#getShowMeanLine--) | Mewakili garis rata-rata. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Mewakili garis rata-rata. |
| [getQuartileMethod()](#getQuartileMethod--) | Mewakili metode kuartil. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Mewakili metode kuartil. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Mewakili garis konektor. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Mewakili garis konektor. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Mewakili tata letak label kategori induk. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Mewakili tata letak label kategori induk. |
| [hasUpDownBars()](#hasUpDownBars--) | Menentukan apakah bagan Garis atau Saham memiliki batang naik/turun. |
| [getGapWidth()](#getGapWidth--) | Menentukan ruang antara gugusan batang atau kolom, sebagai persentase lebar batang atau kolom. |
| [getGapDepth()](#getGapDepth--) | Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam bagan 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Menentukan sudut irisan pertama bagan pai atau donat, dalam derajat (searah jarum jam dari atas, 0 hingga 360 derajat). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Menentukan ukuran lubang dalam bagan donat (bisa antara 10 hingga 90 persen dari ukuran area plot). |
| [getOverlap()](#getOverlap--) | Menentukan sejauh mana batang dan kolom tumpang tindih pada bagan 2-D, sebagai persentase (dari -100% hingga 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Menentukan ukuran pai atau batang kedua pada bagan pai-dalam-pai atau batang-dalam-pai, sebagai persentase ukuran pai pertama (bisa antara 5 hingga 200 persen). |
| [hasSeriesLines()](#hasSeriesLines--) | Menentukan apakah ada garis seri untuk seri ini dan seri terkait. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada bagan gelembung. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada bagan pai-dalam-pai atau batang-dalam-pai. |
| [getPieSplitBy()](#getPieSplitBy--) | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada bagan pai-dalam-pai atau batang-dalam-pai. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Informasi pemisahan khusus untuk bagan pai-dalam-pai atau batang-dalam-pai dengan pemisahan khusus. |
| [isColorVaried()](#isColorVaried--) | Menentukan bahwa setiap penanda data dalam seri memiliki warna berbeda. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Menentukan faktor skala untuk bagan gelembung (bisa antara 0 hingga 300 persen dari ukuran default). |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari FillFormat. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari FillFormat. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Mengembalikan bagan induk. Hanya-baca [IChart](../../com.aspose.slides/ichart).

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Jarak irisan pai terbuka dari pusat bagan pai dinyatakan sebagai persentase dari diameter pai. Baca/tulis int.

**Mengembalikan:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Jarak irisan pai terbuka dari pusat bagan pai dinyatakan sebagai persentase dari diameter pai. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Mewakili pelicinan kurva. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Mewakili pelicinan kurva. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

Mengembalikan nama seri. Hanya-baca [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Mengembalikan:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Mengembalikan koleksi titik data dari seri ini. Hanya-baca [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Mengembalikan:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

Mengembalikan tipe seri ini. Baca/tulis [ChartType](../../com.aspose.slides/charttype).

**Mengembalikan:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Mengembalikan tipe seri ini. Baca/tulis [ChartType](../../com.aspose.slides/charttype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Menunjukkan apakah seri ini dipetakan pada sumbu sekunder. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Menunjukkan apakah seri ini dipetakan pada sumbu sekunder. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Hanya-baca [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Mengembalikan:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Mengembalikan format seri. Hanya-baca [IFormat](../../com.aspose.slides/iformat).

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

Mengembalikan urutan seri. Baca/tulis int.

**Mengembalikan:**
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Mengembalikan urutan seri. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Mengembalikan Label seri. Hanya-baca [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Mengembalikan:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Koleksi garis tren seri. Hanya-baca [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

Garis Tren tersedia (tidak null) untuk seri data pada bagan area 2-D tidak bertumpuk, batang, kolom, garis, saham, xy (scatter), dan gelembung. Garis tren tidak tersedia untuk seri data pada jenis bagan yang bertumpuk atau 3-D. Garis Tren juga tidak tersedia untuk bagan radar, pai, permukaan, atau donat.

**Mengembalikan:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Mewakili ErrorBars seri dengan arah X. Hanya-baca [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars dengan arah X tersedia untuk seri tipe area, batang, scatter, dan bubble. Untuk semua jenis bagan lainnya properti ini mengembalikan null (termasuk bagan 3D). Jika menggunakan nilai khusus, gunakan koleksi DataPoints untuk menentukan nilai (dengan properti ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Mengembalikan:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Mewakili ErrorBars seri dengan arah Y. Hanya-baca [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars dengan arah Y tersedia untuk seri tipe area, batang, garis, scatter, dan bubble. Untuk semua jenis bagan lainnya properti ini mengembalikan null (termasuk bagan 3D). Jika menggunakan nilai khusus, gunakan koleksi DataPoints untuk menentukan nilai (dengan properti ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Mengembalikan:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Mewakili entri legenda yang terkait dengan seri ini Hanya-baca [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Mengembalikan:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. Hanya-baca [IMarker](../../com.aspose.slides/imarker).

**Mengembalikan:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Menentukan bentuk seri pada bagan batang 3-D. Mengubah nilai properti ini dapat menyebabkan otomatis mengubah Tipe seri. Baca/tulis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Mengembalikan:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Menentukan bentuk seri pada bagan batang 3-D. Mengubah nilai properti ini dapat menyebabkan otomatis mengubah Tipe seri. Baca/tulis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Menentukan bar, kolom, atau seri gelembung harus membalikkan warnanya bila nilai negatif. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Menentukan bar, kolom, atau seri gelembung harus membalikkan warnanya bila nilai negatif. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
Menentukan warna solid terbalik untuk seri. Untuk menerapkan pengaturan warna, atur format seri FillType menjadi FillType.Solid. Baca/tulis [ColorFormat](../../com.aspose.slides/colorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```

Mengembalikan warna otomatis series berdasarkan indeks series dan gaya diagram. Warna ini digunakan secara default jika FillType sama dengan NotDefined.

**Mengembalikan:**
java.awt.Color - Objek java.awt.Color.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Mewakili titik dalam. True jika titik dalam ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Mewakili titik dalam. True jika titik dalam ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Mewakili titik outlier. True jika titik outlier ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Mewakili titik outlier. True jika titik outlier ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Mewakili penanda rata-rata. True jika penanda rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Mewakili penanda rata-rata. True jika penanda rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Mewakili garis rata-rata. True jika garis rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Mewakili garis rata-rata. True jika garis rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Mewakili metode kuartil. Hanya berlaku untuk diagram BoxAndWhisker.

**Mengembalikan:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Mewakili metode kuartil. Hanya berlaku untuk diagram BoxAndWhisker.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Mewakili garis penghubung. Hanya berlaku untuk diagram Waterfall.

**Mengembalikan:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Mewakili garis penghubung. Hanya berlaku untuk diagram Waterfall.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Mewakili tata letak label kategori induk. Hanya berlaku untuk diagram Treemap.

**Mengembalikan:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Mewakili tata letak label kategori induk. Hanya berlaku untuk diagram Treemap.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Menentukan apakah diagram Line atau Stock memiliki batang naik/turun. Properti ini bukan hanya milik series ini tetapi juga semua series dalam grup series induk — ini merupakan proyeksi properti grup yang bersangkutan. Karena itu properti ini hanya baca. Gunakan properti ParentSeriesGroup untuk mengakses grup series induk. Gunakan properti baca/tulis ParentSeriesGroup.UpDownBars.HasUpDownBars untuk mengubah nilai. Gunakan properti ParentSeriesGroup.UpDownBars untuk memformat batang naik/turun. Boolean hanya baca.

--------------------

Ini adalah proyeksi dari properti ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Mengembalikan:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Menentukan ruang antara klaster batang atau kolom, sebagai persentase lebar batang atau kolom. Properti ini bukan hanya milik series ini tetapi juga semua series dalam grup series induk — ini merupakan proyeksi properti grup yang bersangkutan. Karena itu properti ini hanya baca. Gunakan properti ParentSeriesGroup untuk mengakses grup series induk. Gunakan properti baca/tulis ParentSeriesGroup.GapWidth untuk mengubah nilai. Int hanya baca.

--------------------

Ini adalah proyeksi dari properti ParentSeriesGroup.GapWidth.

**Mengembalikan:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara series data pada diagram 3D. Properti ini bukan hanya milik series ini tetapi juga semua series dalam grup series induk — ini merupakan proyeksi properti grup yang bersangkutan. Karena itu properti ini hanya baca. Gunakan properti ParentSeriesGroup untuk mengakses grup series induk. Gunakan properti baca/tulis ParentSeriesGroup.GapDepth untuk mengubah nilai. Int hanya baca.

--------------------

Ini adalah proyeksi dari properti ParentSeriesGroup.GapDepth.

**Mengembalikan:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Menentukan sudut irisan pertama diagram pie atau doughnut, dalam derajat (searah jarum jam dari atas, dari 0 sampai 360 derajat). Properti ini bukan hanya milik series ini tetapi juga semua series dalam grup series induk — ini merupakan proyeksi properti grup yang bersangkutan. Karena itu properti ini hanya baca. Gunakan properti ParentSeriesGroup untuk mengakses grup series induk. Gunakan properti baca/tulis ParentSeriesGroup.FirstSliceAngle untuk mengubah nilai. Int hanya baca.

--------------------

Ini adalah proyeksi dari properti ParentSeriesGroup.FirstSliceAngle.

**Mengembalikan:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Menentukan ukuran lubang pada diagram doughnut (bisa antara 10 % dan 90 % dari ukuran area plot). Properti ini bukan hanya milik series ini tetapi juga semua series dalam grup series induk — ini merupakan proyeksi properti grup yang bersangkutan. Karena itu properti ini hanya baca. Gunakan properti ParentSeriesGroup untuk mengakses grup series induk. Gunakan properti baca/tulis ParentSeriesGroup.DoughnutHoleSize untuk mengubah nilai. Byte hanya baca.

--------------------

Ini adalah proyeksi dari properti ParentSeriesGroup.DoughnutHoleSize.

**Mengembalikan:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Menentukan berapa banyak batang dan kolom saling tumpang tindih pada diagram 2-D, sebagai persentase (dari -100 % sampai 100 %). Properti ini bukan hanya milik series ini tetapi juga semua series dalam grup series induk. Ini adalah proyeksi properti yang sesuai dalam grup series induk, sehingga properti ini hanya baca. Untuk mengubah nilai, gunakan properti baca/tulis ParentSeriesGroup.Overlap. Byte hanya baca.

--------------------

Overlap menentukan tingkat tumpang tindih atau jarak antara batang dan kolom sebagai persentase lebar mereka: - -100 %: Jarak maksimum (batang terpisah sepenuhnya). - 0 %: Batang ditempatkan berdampingan tanpa tumpang tindih atau jarak. - 100 %: Tumpang tindih maksimum (batang saling menutupi sepenuhnya). Ini adalah proyeksi dari properti ParentSeriesGroup.Overlap.

**Mengembalikan:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Menentukan ukuran pie atau batang kedua pada diagram pie-of-pie atau bar-of-pie, sebagai persentase ukuran pie pertama (bisa antara 5 % dan 200 %). Properti ini bukan hanya milik series ini tetapi juga semua series dalam grup series induk — ini merupakan proyeksi properti grup yang bersangkutan. Karena itu properti ini hanya baca. Gunakan properti ParentSeriesGroup untuk mengakses grup series induk. Gunakan properti baca/tulis ParentSeriesGroup.SecondPieSize untuk mengubah nilai. Int hanya baca.

--------------------

Ini adalah proyeksi dari properti ParentSeriesGroup.SecondPieSize.

**Mengembalikan:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Menentukan apakah ada garis series untuk series ini dan series terkait. Properti ini bukan hanya milik series ini tetapi juga semua series dalam grup series induk — ini merupakan proyeksi properti grup yang bersangkutan. Karena itu properti ini hanya baca. Gunakan properti ParentSeriesGroup untuk mengakses grup series induk. Gunakan properti baca/tulis ParentSeriesGroup.HasSeriesLines untuk mengubah nilai. Gunakan properti ParentSeriesGroup.SeriesLinesFormat untuk memformat garis series. Boolean hanya baca.

--------------------

Ini adalah proyeksi dari properti ParentSeriesGroup.HasSeriesLines.

**Mengembalikan:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. Properti ini bukan hanya milik series ini tetapi juga semua series dalam grup series induk — ini merupakan proyeksi properti grup yang bersangkutan. Karena itu properti ini hanya baca. Gunakan properti ParentSeriesGroup untuk mengakses grup series induk. Gunakan properti baca/tulis ParentSeriesGroup.BubbleSizeRepresentation untuk mengubah nilai.

--------------------

Ini adalah proyeksi dari properti ParentSeriesGroup.BubbleSizeRepresentation.

**Mengembalikan:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pie atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Properti ini bukan hanya milik series ini tetapi juga semua series dalam grup series induk — ini merupakan proyeksi properti grup yang bersangkutan. Karena itu properti ini hanya baca. Gunakan properti ParentSeriesGroup untuk mengakses grup series induk. Gunakan properti baca/tulis ParentSeriesGroup.PieSplitPosition untuk mengubah nilai. Double hanya baca.

--------------------

Ini adalah proyeksi dari properti ParentSeriesGroup.PieSplitPosition.

**Mengembalikan:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Menentukan cara menentukan titik data mana yang berada di pie atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Properti ini bukan hanya milik series ini tetapi juga semua series dalam grup series induk — ini merupakan proyeksi properti grup yang bersangkutan. Karena itu properti ini hanya baca. Gunakan properti ParentSeriesGroup untuk mengakses grup series induk. Gunakan properti baca/tulis ParentSeriesGroup.PieSplitBy untuk mengubah nilai. Baca/tulis [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Ini adalah proyeksi dari properti ParentSeriesGroup.PieSplitBy. 2) Jika nilai properti adalah PieSplitType.Custom maka Anda dapat mendefinisikan informasi split kustom dengan properti ParentSeriesGroup.PieSplitCustomPoints.

**Mengembalikan:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Informasi split kustom untuk diagram pie-of-pie atau bar-of-pie dengan split kustom. Berisi titik data yang akan digambar pada pie atau batang kedua dalam diagram pie-of-pie atau bar-of-pie. Properti ini bukan hanya milik series ini tetapi juga semua series dalam grup series induk — ini merupakan proyeksi properti grup yang bersangkutan. Baca saja [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Ini adalah proyeksi dari properti ParentSeriesGroup.PieSplitCustomPoints.

**Mengembalikan:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. Properti ini bukan hanya milik seri ini tetapi milik semua seri dalam grup seri induk — ini merupakan proyeksi properti grup yang sesuai. Oleh karena itu properti ini bersifat read-only. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.IsColorVaried read/write untuk mengubah nilai. Boolean hanya-baca.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.IsColorVaried.

**Mengembalikan:**  
boolean  

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Menentukan faktor skala untuk grafik gelembung (dapat antara 0 dan 300 persen dari ukuran default). Properti ini bukan hanya milik seri ini tetapi milik semua seri dalam grup seri induk — ini merupakan proyeksi properti grup yang sesuai. Oleh karena itu properti ini bersifat read-only. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.BubbleSizeScale read/write untuk mengubah nilai.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.BubbleSizeScale.

**Mengembalikan:**  
int  

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide induk dari FillFormat. Hanya-baca [BaseSlide](../../com.aspose.slides/baseslide).

**Mengembalikan:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)  

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk dari FillFormat. Hanya-baca [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**  
[IPresentation](../../com.aspose.slides/ipresentation)