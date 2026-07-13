---
title: ChartSeries
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili seri diagram.
type: docs
url: /id/com.aspose.slides/chartseries/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Mewakili seri diagram.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Mengembalikan diagram induk. |
| [getExplosion()](#getExplosion--) | Jarak irisan pai terbuka dari pusat diagram pai diekspresikan sebagai persentase dari diameter pai. |
| [setExplosion(int value)](#setExplosion-int-) | Jarak irisan pai terbuka dari pusat diagram pai diekspresikan sebagai persentase dari diameter pai. |
| [getSmooth()](#getSmooth--) | Mewakili pelunakan kurva. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Mewakili pelunakan kurva. |
| [getName()](#getName--) | Mengembalikan nama seri. |
| [getDataPoints()](#getDataPoints--) | Mengembalikan koleksi titik data seri ini. |
| [getType()](#getType--) | Mengembalikan tipe seri ini. |
| [setType(int value)](#setType-int-) | Mengembalikan tipe seri ini. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Menunjukkan apakah seri ini diplot pada sumbu sekunder. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Menunjukkan apakah seri ini diplot pada sumbu sekunder. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Mengembalikan format sebuah seri. |
| [getOrder()](#getOrder--) | Mengembalikan urutan sebuah seri. |
| [setOrder(int value)](#setOrder-int-) | Mengembalikan urutan sebuah seri. |
| [getLabels()](#getLabels--) | Mengembalikan Label sebuah seri. |
| [getTrendLines()](#getTrendLines--) | Koleksi garis tren seri. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Mewakili ErrorBars seri dengan arah X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Mewakili ErrorBars seri dengan arah Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Mewakili entri legenda yang berhubungan dengan seri ini Hanya-baca [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Menentukan bentuk seri diagram batang 3-D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Menentukan bentuk seri diagram batang 3-D. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Menentukan bahwa seri bar, kolom, atau gelembung harus menukar warnanya bila nilai negatif. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Menentukan bahwa seri bar, kolom, atau gelembung harus menukar warnanya bila nilai negatif. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Menentukan warna padat terbalik untuk seri. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Mengembalikan warna otomatis seri berdasarkan indeks seri dan gaya diagram. |
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
| [getShowConnectorLines()](#getShowConnectorLines--) | Mewakili garis penghubung. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Mewakili garis penghubung. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Mewakili tata letak label kategori induk. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Mewakili tata letak label kategori induk. |
| [hasUpDownBars()](#hasUpDownBars--) | Menentukan apakah diagram Garis atau Saham memiliki bar naik/turun. |
| [getGapWidth()](#getGapWidth--) | Menentukan ruang antara klaster bar atau kolom, sebagai persentase lebar bar atau kolom. |
| [getGapDepth()](#getGapDepth--) | Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam diagram 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Menentukan sudut irisan pai atau donat pertama, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Menentukan ukuran lubang pada diagram donat (antara 10 % hingga 90 % dari ukuran area plot). |
| [getOverlap()](#getOverlap--) | Menentukan seberapa banyak bar dan kolom saling tumpang pada diagram 2-D, sebagai persentase (dari –100 % hingga 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Menentukan ukuran pai atau bar kedua pada diagram pai-dalam-pai atau bar-dalam-pai, sebagai persentase ukuran pai pertama (antara 5 % hingga 200 %). |
| [hasSeriesLines()](#hasSeriesLines--) | Menentukan apakah ada garis seri untuk seri ini dan seri terkait. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Menentukan bagaimana nilai ukuran gelembung diwakili pada diagram gelembung. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Menentukan nilai yang digunakan untuk menentukan titik data mana yang berada pada pai atau bar kedua pada diagram pai-dalam-pai atau bar-dalam-pai. |
| [getPieSplitBy()](#getPieSplitBy--) | Menentukan cara menentukan titik data mana yang berada pada pai atau bar kedua pada diagram pai-dalam-pai atau bar-dalam-pai. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Informasi pemisahan khusus untuk diagram pai-dalam-pai atau bar-dalam-pai dengan pemisahan khusus. |
| [isColorVaried()](#isColorVaried--) | Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Menentukan faktor skala untuk diagram gelembung (antara 0 % hingga 300 % ukuran bawaan). |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari sebuah FillFormat. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari sebuah FillFormat. |

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

Mengembalikan diagram induk. Hanya-baca [IChart](../../com.aspose.slides/ichart).

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Jarak irisan pai terbuka dari pusat diagram pai diekspresikan sebagai persentase dari diameter pai. Baca/tulis int.

**Mengembalikan:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Jarak irisan pai terbuka dari pusat diagram pai diekspresikan sebagai persentase dari diameter pai. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Mewakili pelunakan kurva. True jika pelunakan kurva diaktifkan untuk diagram garis atau diagram sebar. Hanya berlaku untuk diagram garis dan sebar yang dihubungkan oleh garis. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Mewakili pelunakan kurva. True jika pelunakan kurva diaktifkan untuk diagram garis atau diagram sebar. Hanya berlaku untuk diagram garis dan sebar yang dihubungkan oleh garis. Baca/tulis boolean.

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

Mengembalikan koleksi titik data seri ini. Hanya-baca [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

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

Menunjukkan apakah seri ini diplot pada sumbu sekunder. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Menunjukkan apakah seri ini diplot pada sumbu sekunder. Baca/tulis boolean.

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

Mengembalikan format sebuah seri. Hanya-baca [IFormat](../../com.aspose.slides/iformat).

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

Mengembalikan urutan sebuah seri. Baca/tulis int.

**Mengembalikan:**
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Mengembalikan urutan sebuah seri. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Mengembalikan Label sebuah seri. Hanya-baca [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Mengembalikan:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Koleksi garis tren seri. Hanya-baca [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

TrendLines tersedia (tidak null) untuk seri data pada diagram area, batang, kolom, garis, saham, xy (sebar), dan gelembung 2-D yang tidak ditumpuk. Trendline tidak tersedia untuk seri data pada tipe diagram apapun yang ditumpuk atau 3-D. Trendlines juga tidak tersedia untuk diagram radar, pai, permukaan, atau donat.

**Mengembalikan:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Mewakili ErrorBars seri dengan arah X. Hanya-baca [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars dengan arah X tersedia untuk seri tipe area, batang, sebar, dan gelembung. Untuk tipe diagram lain properti ini mengembalikan null (termasuk diagram 3D). Jika menggunakan nilai khusus, gunakan koleksi DataPoints untuk menentukan nilai (dengan properti ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Mengembalikan:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Mewakili ErrorBars seri dengan arah Y. Hanya-baca [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars dengan arah Y tersedia untuk seri tipe area, batang, garis, sebar, dan gelembung. Untuk tipe diagram lain properti ini mengembalikan null (termasuk diagram 3D). Jika menggunakan nilai khusus, gunakan koleksi DataPoints untuk menentukan nilai (dengan properti ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Mengembalikan:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Mewakili entri legenda yang berhubungan dengan seri ini Hanya-baca [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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

Menentukan bentuk seri diagram batang 3-D. Mengubah nilai properti ini dapat menyebabkan otomatis mengubah Tipe seri. Baca/tulis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Mengembalikan:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Menentukan bentuk seri diagram batang 3-D. Mengubah nilai properti ini dapat menyebabkan otomatis mengubah Tipe seri. Baca/tulis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Menentukan bahwa seri bar, kolom, atau gelembung harus menukar warnanya bila nilai negatif. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Menentukan bahwa seri bar, kolom, atau gelembung harus menukar warnanya bila nilai negatif. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

Menentukan warna padat terbalik untuk seri. Untuk menerapkan pengaturan warna, set format seri FillType ke FillType.Solid. Baca/tulis [ColorFormat](../../com.aspose.slides/colorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

Mengembalikan warna otomatis seri berdasarkan indeks seri dan gaya diagram. Warna ini digunakan secara default bila FillType = NotDefined.

**Mengembalikan:**
java.lang.Integer - Objek java.lang.Integer.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Mewakili titik dalam. True bila titik dalam ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Mewakili titik dalam. True bila titik dalam ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Mewakili titik outlier. True bila titik outlier ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Mewakili titik outlier. True bila titik outlier ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Mewakili penanda rata-rata. True bila penanda rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Mewakili penanda rata-rata. True bila penanda rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Mewakili garis rata-rata. True bila garis rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Mewakili garis rata-rata. True bila garis rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Menentukan apakah diagram Garis atau Saham memiliki bar naik/turun. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini Hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.UpDownBars.HasUpDownBars Baca/tulis untuk mengubah nilai. Gunakan properti ParentSeriesGroup.UpDownBars untuk format bar naik/turun. Hanya-baca boolean.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Mengembalikan:**
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Menentukan ruang antara klaster bar atau kolom, sebagai persentase lebar bar atau kolom. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini Hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.GapWidth Baca/tulis untuk mengubah nilai. Hanya-baca int.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.GapWidth.

**Mengembalikan:**
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam diagram 3D. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini Hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.GapDepth Baca/tulis untuk mengubah nilai. Hanya-baca int.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.GapDepth.

**Mengembalikan:**
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Menentukan sudut irisan pai atau donat pertama, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini Hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.FirstSliceAngle Baca/tulis untuk mengubah nilai. Hanya-baca int.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.FirstSliceAngle.

**Mengembalikan:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Menentukan ukuran lubang pada diagram donat (antara 10 % hingga 90 % dari ukuran area plot). Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini Hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.DoughnutHoleSize Baca/tulis untuk mengubah nilai. Hanya-baca byte.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.DoughnutHoleSize.

**Mengembalikan:**
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Menentukan seberapa banyak bar dan kolom saling tumpang pada diagram 2-D, sebagai persentase (dari –100 % hingga 100 %). Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk. Ini merupakan proyeksi properti yang sesuai di grup seri induk, sehingga properti ini Hanya-baca. Untuk mengubah nilai, gunakan properti ParentSeriesGroup.Overlap Baca/tulis. Hanya-baca byte.

--------------------

Overlap menentukan tingkat tumpang atau jarak antara bar dan kolom sebagai persentase lebar mereka: –100 %: Jarak maksimum (bar terpisah sepenuhnya). 0 %: Bar ditempatkan berdampingan tanpa tumpang atau jarak. 100 %: Tumpang maksimum (bar saling menutupi sepenuhnya). Ini adalah proyeksi properti ParentSeriesGroup.Overlap.

**Mengembalikan:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Menentukan ukuran pai atau bar kedua pada diagram pai-dalam-pai atau bar-dalam-pai, sebagai persentase ukuran pai pertama (antara 5 % hingga 200 %). Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini Hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.SecondPieSize Baca/tulis untuk mengubah nilai. Hanya-baca int.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.SecondPieSize.

**Mengembalikan:**
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Menentukan apakah ada garis seri untuk seri ini dan seri terkait. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini Hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.HasSeriesLines Baca/tulis untuk mengubah nilai. Gunakan properti ParentSeriesGroup.SeriesLinesFormat untuk format garis seri. Hanya-baca boolean.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.HasSeriesLines.

**Mengembalikan:**
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Menentukan bagaimana nilai ukuran gelembung diwakili pada diagram gelembung. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini Hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.BubbleSizeRepresentation Baca/tulis untuk mengubah nilai.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.BubbleSizeRepresentation.

**Mengembalikan:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada pada pai atau bar kedua pada diagram pai-dalam-pai atau bar-dalam-pai. Digunakan bersama properti PieSplitBy. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini Hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.PieSplitPosition Baca/tulis untuk mengubah nilai. Hanya-baca double.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.PieSplitPosition.

**Mengembalikan:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Menentukan cara menentukan titik data mana yang berada pada pai atau bar kedua pada diagram pai-dalam-pai atau bar-dalam-pai. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini Hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.PieSplitBy Baca/tulis untuk mengubah nilai. Hanya-baca [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Ini adalah proyeksi properti ParentSeriesGroup.PieSplitBy. 2) Jika nilai properti adalah PieSplitType.Custom maka Anda dapat mendefinisikan informasi pemisahan khusus dengan properti ParentSeriesGroup.PieSplitCustomPoints.

**Mengembalikan:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Informasi pemisahan khusus untuk diagram pai-dalam-pai atau bar-dalam-pai dengan pemisahan khusus. Berisi titik data yang akan digambar pada pai atau bar kedua dalam diagram pai-dalam-pai atau bar-dalam-pai. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai Hanya-baca [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.PieSplitCustomPoints.

**Mengembalikan:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini Hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.IsColorVaried Baca/tulis untuk mengubah nilai. Hanya-baca boolean.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.IsColorVaried.

**Mengembalikan:**
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Menentukan faktor skala untuk diagram gelembung (antara 0 % hingga 300 % ukuran bawaan). Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini Hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.BubbleSizeScale Baca/tulis untuk mengubah nilai.

--------------------

Ini adalah proyeksi properti ParentSeriesGroup.BubbleSizeScale.

**Mengembalikan:**
int

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