---
title: IChartSeries
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili seri grafik.
type: docs
url: /id/com.aspose.slides/ichartseries/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Mewakili seri grafik.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getExplosion()](#getExplosion--) | Jarak sebuah irisan pai terbuka dari pusat diagram pai diungkapkan sebagai persentase dari diameter pai. |
| [setExplosion(int value)](#setExplosion-int-) | Jarak sebuah irisan pai terbuka dari pusat diagram pai diungkapkan sebagai persentase dari diameter pai. |
| [getSmooth()](#getSmooth--) | Mewakili penghalusan kurva. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Mewakili penghalusan kurva. |
| [getMarker()](#getMarker--) | Mengembalikan penanda seri. |
| [getBar3DShape()](#getBar3DShape--) | Menentukan bentuk seri pada diagram batang 3-D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Menentukan bentuk seri pada diagram batang 3-D. |
| [getName()](#getName--) | Mengembalikan nama seri. |
| [getDataPoints()](#getDataPoints--) | Mengembalikan koleksi titik data dari seri ini. |
| [getType()](#getType--) | Mengembalikan tipe seri ini. |
| [setType(int value)](#setType-int-) | Mengembalikan tipe seri ini. |
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
| [getInvertIfNegative()](#getInvertIfNegative--) | Menentukan seri batang, kolom, atau gelembung harus membalikkan warnanya jika nilai negatif. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Menentukan seri batang, kolom, atau gelembung harus membalikkan warnanya jika nilai negatif. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Menentukan warna solid terbalik untuk seri. |
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
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Menentukan faktor skala untuk diagram gelembung (bisa antara 0 dan 300 persen dari ukuran default). |
| [hasUpDownBars()](#hasUpDownBars--) | Menentukan apakah diagram Garis atau Saham memiliki batang naik/turun. |
| [getGapWidth()](#getGapWidth--) | Menentukan ruang antara kelompok batang atau kolom, sebagai persentase lebar batang atau kolom. |
| [getGapDepth()](#getGapDepth--) | Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam diagram 3D. |
| [isColorVaried()](#isColorVaried--) | Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. |
| [hasSeriesLines()](#hasSeriesLines--) | Menentukan apakah ada garis seri untuk seri ini dan seri terkait. |
| [getOverlap()](#getOverlap--) | Menentukan seberapa banyak batang dan kolom tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Menentukan ukuran pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai, sebagai persentase ukuran pai pertama (bisa antara 5 hingga 200 persen). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai. |
| [getPieSplitBy()](#getPieSplitBy--) | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Menentukan ukuran lubang pada diagram donat (bisa antara 10 hingga 90 persen dari ukuran area plot). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Menentukan sudut irisan pai atau donat pertama, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Informasi pemisahan khusus untuk diagram pai-dalam-pai atau batang-dalam-pai dengan pemisahan khusus. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Jarak sebuah irisan pai terbuka dari pusat diagram pai diungkapkan sebagai persentase dari diameter pai. Baca/tulis int.

**Mengembalikan:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Jarak sebuah irisan pai terbuka dari pusat diagram pai diungkapkan sebagai persentase dari diameter pai. Baca/tulis int.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Mewakili penghalusan kurva. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Mewakili penghalusan kurva. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Baca/tulis boolean.

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

Menentukan bentuk seri pada diagram batang 3-D. Changing of value of this property can cause to automatically changing Type of series. Baca/tulis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Mengembalikan:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Menentukan bentuk seri pada diagram batang 3-D. Changing of value of this property can cause to automatically changing Type of series. Baca/tulis [ChartShapeType](../../com.aspose.slides/chartshapetype).

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

Mengembalikan tipe seri ini. Baca/tulis [ChartType](../../com.aspose.slides/charttype).

**Mengembalikan:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Mengembalikan tipe seri ini. Baca/tulis [ChartType](../../com.aspose.slides/charttype).

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

ErrorBars dengan arah X tersedia untuk seri tipe area, bar, scatter, dan bubble. Untuk tipe diagram lain properti ini mengembalikan null (termasuk diagram 3D). Jika menggunakan nilai khusus, gunakan koleksi DataPoints untuk menentukan nilai (dengan properti ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Mengembalikan:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Mewakili ErrorBars seri dengan arah Y. Baca-saja [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars dengan arah Y tersedia untuk seri tipe area, bar, line, scatter, dan bubble. Untuk tipe diagram lain properti ini mengembalikan null (termasuk diagram 3D). Jika menggunakan nilai khusus, gunakan koleksi DataPoints untuk menentukan nilai (dengan properti ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

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

Menentukan seri batang, kolom, atau gelembung harus membalikkan warnanya jika nilai negatif. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Menentukan seri batang, kolom, atau gelembung harus membalikkan warnanya jika nilai negatif. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Menentukan warna solid terbalik untuk seri. To apply color setting set series format FillType to FillType.Solid. Baca/tulis [IColorFormat](../../com.aspose.slides/icolorformat).

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
public abstract Integer getAutomaticSeriesColor()
```

Mengembalikan warna otomatis seri berdasarkan indeks seri dan gaya diagram. This color is used by default if FillType equals NotDefined.

**Mengembalikan:**
java.lang.Integer - Automatic color of series java.lang.Integer
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Mewakili titik dalam. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Mewakili titik dalam. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Mewakili titik outlier. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Mewakili titik outlier. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Mewakili penanda rata-rata. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Mewakili penanda rata-rata. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Mewakili penanda rata-rata. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Mewakili penanda rata-rata. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Mewakili metode kuartil. Applies only to BoxAndWhisker charts.

**Mengembalikan:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Mewakili metode kuartil. Applies only to BoxAndWhisker charts.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Mewakili garis penghubung. Applies only to Waterfall charts.

**Mengembalikan:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Mewakili garis penghubung. Applies only to Waterfall charts.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Mewakili tata letak label kategori induk. Applies only to Treemap charts.

**Mengembalikan:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Mewakili tata letak label kategori induk. Applies only to Treemap charts.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Menentukan faktor skala untuk diagram gelembung (bisa antara 0 dan 300 persen dari ukuran default). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeScale read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeScale.

**Mengembalikan:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Menentukan apakah diagram Garis atau Saham memiliki batang naik/turun. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.UpDownBars.HasUpDownBars read/write property for change value. Use ParentSeriesGroup.UpDownBars property for format up/down bars. Baca-saja boolean.

--------------------

This is the projection of the property ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Mengembalikan:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Menentukan ruang antara kelompok batang atau kolom, sebagai persentase lebar batang atau kolom. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapWidth read/write property for change value. Baca-saja int.

--------------------

This is the projection of the property ParentSeriesGroup.GapWidth.

**Mengembalikan:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam diagram 3D. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapDepth read/write property for change value. Baca-saja int.

--------------------

This is the projection of the property ParentSeriesGroup.GapDepth.

**Mengembalikan:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Baca-saja boolean.

--------------------

This is the projection of the property ParentSeriesGroup.IsColorVaried.

**Mengembalikan:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Menentukan apakah ada garis seri untuk seri ini dan seri terkait. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.HasSeriesLines read/write property for change value. Use ParentSeriesGroup.SeriesLinesFormat property for format series lines. Baca-saja boolean.

--------------------

This is the projection of the property ParentSeriesGroup.HasSeriesLines.

**Mengembalikan:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Menentukan seberapa banyak batang dan kolom tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). This is the property not only of this series but of all series of parent series group. It is a projection of the appropriate property in the parent series group, and so this property is read-only. To change the value, use the ParentSeriesGroup.Overlap read/write property. Baca-saja byte .

--------------------

Overlap specifies the degree of overlap or spacing between bars and columns as a percentage of their width: - -100%: Maximum spacing (bars are completely separated). - 0%: Bars are placed side by side without overlap or spacing. - 100%: Maximum overlap (bars completely overlap each other). This is a projection of the property ParentSeriesGroup.Overlap.

**Mengembalikan:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Menentukan ukuran pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai, sebagai persentase ukuran pai pertama (bisa antara 5 hingga 200 persen). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.SecondPieSize read/write property for change value. Baca-saja int.

--------------------

This is the projection of the property ParentSeriesGroup.SecondPieSize.

**Mengembalikan:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai. Is used together with PieSplitBy property. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitPosition read/write property for change value. Baca-saja double.

--------------------

This is the projection of the property ParentSeriesGroup.PieSplitPosition.

**Mengembalikan:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitBy read/write property for change value. Baca-saja [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) This is the projection of the property ParentSeriesGroup.PieSplitBy. 2) If property value is PieSplitType.Custom then you can define custom split information with ParentSeriesGroup.PieSplitCustomPoints property.

**Mengembalikan:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Menentukan ukuran lubang pada diagram donat (bisa antara 10 hingga 90 persen dari ukuran area plot). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.DoughnutHoleSize read/write property for change value. Baca-saja byte.

--------------------

This is the projection of the property ParentSeriesGroup.DoughnutHoleSize.

**Mengembalikan:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Menentukan sudut irisan pai atau donat pertama, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.FirstSliceAngle read/write property for change value. Baca-saja int.

--------------------

This is the projection of the property ParentSeriesGroup.FirstSliceAngle.

**Mengembalikan:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Informasi pemisahan khusus untuk diagram pai-dalam-pai atau batang-dalam-pai dengan pemisahan khusus. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property Baca-saja [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

This is the projection of the property ParentSeriesGroup.PieSplitCustomPoints.

**Mengembalikan:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeRepresentation read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeRepresentation.

**Mengembalikan:**
int