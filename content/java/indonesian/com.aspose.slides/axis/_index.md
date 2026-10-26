---
title: Axis
second_title: Referensi API Aspose.Slides untuk Java
description: Menyatukan objek yang mewakili sumbu grafik.
type: docs
url: /id/com.aspose.slides/axis/
---
**Warisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Membungkus objek yang mewakili sumbu chart.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getChart()](#getChart--) | Mengembalikan chart induk. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Mewakili apakah sumbu nilai melintasi sumbu kategori di antara kategori. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Mewakili apakah sumbu nilai melintasi sumbu kategori di antara kategori. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Menentukan tipe sumbu kategori. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Menentukan tipe sumbu kategori. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Mengatur properti IAxis.CategoryAxisType dengan nilai yang secara otomatis ditentukan berdasarkan data sumbu. |
| [getCrossAt()](#getCrossAt--) | Mewakili titik pada sumbu dimana sumbu tegak lurus melintasinya. |
| [setCrossAt(float value)](#setCrossAt-float-) | Mewakili titik pada sumbu dimana sumbu tegak lurus melintasinya. |
| [getDisplayUnit()](#getDisplayUnit--) | Menentukan nilai skala satuan tampilan untuk sumbu nilai. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Menentukan nilai skala satuan tampilan untuk sumbu nilai. |
| [getActualMaxValue()](#getActualMaxValue--) | Menentukan nilai maksimum aktual pada sumbu. |
| [getActualMinValue()](#getActualMinValue--) | Menentukan nilai minimum aktual pada sumbu. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Menentukan satuan utama aktual dari sumbu. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Menentukan satuan minor aktual dari sumbu. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Menentukan skala satuan utama aktual dari sumbu. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Menentukan skala satuan minor aktual dari sumbu. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Menunjukkan apakah nilai maksimum ditetapkan secara otomatis. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Menunjukkan apakah nilai maksimum ditetapkan secara otomatis. |
| [getMaxValue()](#getMaxValue--) | Mewakili nilai maksimum pada sumbu nilai. |
| [setMaxValue(double value)](#setMaxValue-double-) | Mewakili nilai maksimum pada sumbu nilai. |
| [getMinorUnit()](#getMinorUnit--) | Mewakili satuan minor untuk sumbu tanggal atau nilai. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Mewakili satuan minor untuk sumbu tanggal atau nilai. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Menunjukkan apakah satuan minor sumbu ditetapkan secara otomatis. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Menunjukkan apakah satuan minor sumbu ditetapkan secara otomatis. |
| [getMajorUnit()](#getMajorUnit--) | Mewakili satuan utama untuk sumbu tanggal atau nilai. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Mewakili satuan utama untuk sumbu tanggal atau nilai. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Menunjukkan apakah satuan utama sumbu ditetapkan secara otomatis. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Menunjukkan apakah satuan utama sumbu ditetapkan secara otomatis. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Menunjukkan apakah nilai minimum ditetapkan secara otomatis. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Menunjukkan apakah nilai minimum ditetapkan secara otomatis. |
| [getMinValue()](#getMinValue--) | Mewakili nilai minimum pada sumbu nilai. |
| [setMinValue(double value)](#setMinValue-double-) | Mewakili nilai minimum pada sumbu nilai. |
| [isLogarithmic()](#isLogarithmic--) | Mewakili apakah tipe skala sumbu nilai bersifat logaritmik atau tidak. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Mewakili apakah tipe skala sumbu nilai bersifat logaritmik atau tidak. |
| [getLogBase()](#getLogBase--) | Mewakili basis logaritma. |
| [setLogBase(double value)](#setLogBase-double-) | Mewakili basis logaritma. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Mewakili apakah MS PowerPoint memplot titik data dari terakhir ke pertama. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Mewakili apakah MS PowerPoint memplot titik data dari terakhir ke pertama. |
| [isVisible()](#isVisible--) | Mewakili apakah sumbu terlihat. |
| [setVisible(boolean value)](#setVisible-boolean-) | Mewakili apakah sumbu terlihat. |
| [getMajorTickMark()](#getMajorTickMark--) | Mewakili tipe tanda utama untuk sumbu yang ditentukan. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Mewakili tipe tanda utama untuk sumbu yang ditentukan. |
| [getMinorTickMark()](#getMinorTickMark--) | Mewakili tipe tanda minor untuk sumbu yang ditentukan. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Mewakili tipe tanda minor untuk sumbu yang ditentukan. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Mewakili posisi label tanda pada sumbu yang ditentukan. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Mewakili posisi label tanda pada sumbu yang ditentukan. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Mewakili skala satuan utama untuk sumbu tanggal. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Mewakili skala satuan utama untuk sumbu tanggal. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Mewakili skala satuan utama untuk sumbu tanggal. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Mewakili skala satuan utama untuk sumbu tanggal. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Menentukan satuan waktu terkecil yang direpresentasikan pada sumbu tanggal. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Menentukan satuan waktu terkecil yang direpresentasikan pada sumbu tanggal. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Mewakili format garis kisi minor pada sumbu chart. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Mewakili format garis kisi utama pada sumbu chart. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Untuk menyembunyikan garis kisi minor, set MinorGridLinesFormat.Line.FillFormat.FillType ke FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Untuk menyembunyikan garis kisi utama, set MajorGridLinesFormat.Line.FillFormat.FillType ke FillType.NoFill. |
| [getFormat()](#getFormat--) | Mewakili format sumbu. |
| [getTextFormat()](#getTextFormat--) | Mewakili format teks. |
| [getTitle()](#getTitle--) | Mendapatkan judul sumbu. |
| [getCrossType()](#getCrossType--) | Mewakili CrossType pada sumbu yang ditentukan dimana sumbu lain melintasinya. |
| [setCrossType(int value)](#setCrossType-int-) | Mewakili CrossType pada sumbu yang ditentukan dimana sumbu lain melintasinya. |
| [getPosition()](#getPosition--) | Mewakili posisi sumbu. |
| [setPosition(int value)](#setPosition-int-) | Mewakili posisi sumbu. |
| [hasTitle()](#hasTitle--) | Menentukan apakah sumbu memiliki judul yang terlihat. |
| [setTitle(boolean value)](#setTitle-boolean-) | Menentukan apakah sumbu memiliki judul yang terlihat. |
| [getNumberFormat()](#getNumberFormat--) | Mewakili string format untuk Label Sumbu. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Mewakili string format untuk Label Sumbu. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Menunjukkan apakah format terhubung ke data sumber. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Menunjukkan apakah format terhubung ke data sumber. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Mewakili sudut rotasi label tick. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Mewakili sudut rotasi label tick. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Menentukan berapa banyak label tick yang dilewati antara label yang digambar. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Menentukan berapa banyak label tick yang dilewati antara label yang digambar. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Menentukan nilai spasi label tick otomatis. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Menentukan nilai spasi label tick otomatis. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Menentukan berapa banyak tanda tick yang harus dilewati sebelum yang berikutnya digambar. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Menentukan berapa banyak tanda tick yang harus dilewati sebelum yang berikutnya digambar. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Menentukan nilai spasi tanda tick otomatis. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Menentukan nilai spasi tanda tick otomatis. |
| [getLabelOffset()](#getLabelOffset--) | Menentukan jarak label dari sumbu. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Menentukan jarak label dari sumbu. |
| [getAggregationType()](#getAggregationType--) | Mewakili tipe agregasi sumbu kategori (binning). |
| [setAggregationType(int value)](#setAggregationType-int-) | Mewakili tipe agregasi sumbu kategori (binning). |
| [getBinWidth()](#getBinWidth--) | Menentukan lebar bin ketika nilai properti AggregationType diset ke AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Menentukan lebar bin ketika nilai properti AggregationType diset ke AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Menentukan jumlah bin ketika nilai properti AggregationType diset ke AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Menentukan jumlah bin ketika nilai properti AggregationType diset ke AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Menentukan apakah bin overflow diterapkan. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Menentukan apakah bin overflow diterapkan. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Menentukan nilai bin overflow otomatis. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Menentukan nilai bin overflow otomatis. |
| [getOverflowBin()](#getOverflowBin--) | Menentukan nilai khusus bin overflow. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Menentukan nilai khusus bin overflow. |
| [isUnderflowBin()](#isUnderflowBin--) | Menentukan apakah bin underflow diterapkan. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Menentukan apakah bin underflow diterapkan. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Menentukan nilai bin underflow otomatis. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Menentukan nilai bin underflow otomatis. |
| [getUnderflowBin()](#getUnderflowBin--) | Menentukan nilai khusus bin underflow. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Menentukan nilai khusus bin underflow. |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari sebuah FillFormat. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari sebuah FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Mengembalikan chart induk. Hanya-baca [IChart](../../com.aspose.slides/ichart).

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Mewakili apakah sumbu nilai melintasi sumbu kategori di antara kategori. Properti ini hanya berlaku untuk sumbu kategori, dan tidak berlaku untuk chart 3-D. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Mewakili apakah sumbu nilai melintasi sumbu kategori di antara kategori. Properti ini hanya berlaku untuk sumbu kategori, dan tidak berlaku untuk chart 3-D. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Menentukan tipe sumbu kategori. Baca/tulis [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Mengembalikan:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Menentukan tipe sumbu kategori. Baca/tulis [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Mengatur properti IAxis.CategoryAxisType dengan nilai yang secara otomatis ditentukan berdasarkan data sumbu.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Mewakili titik pada sumbu dimana sumbu tegak lurus melintasinya. Baca/tulis float.

**Mengembalikan:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Mewakili titik pada sumbu dimana sumbu tegak lurus melintasinya. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Menentukan nilai skala satuan tampilan untuk sumbu nilai. Baca/tulis [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Mengembalikan:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Menentukan nilai skala satuan tampilan untuk sumbu nilai. Baca/tulis [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Menentukan nilai maksimum aktual pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual.

**Mengembalikan:**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Menentukan nilai minimum aktual pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual.

**Mengembalikan:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Menentukan satuan utama aktual dari sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual.

**Mengembalikan:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Menentukan satuan minor aktual dari sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual.

**Mengembalikan:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Menentukan skala satuan utama aktual dari sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual.

**Mengembalikan:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Menentukan skala satuan minor aktual dari sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual.

**Mengembalikan:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Menunjukkan apakah nilai maksimum ditetapkan secara otomatis. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Menunjukkan apakah nilai maksimum ditetapkan secara otomatis. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Mewakili nilai maksimum pada sumbu nilai. Baca/tulis double.

**Mengembalikan:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Mewakili nilai maksimum pada sumbu nilai. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Mewakili satuan minor untuk sumbu tanggal atau nilai. Baca/tulis double.

**Mengembalikan:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Mewakili satuan minor untuk sumbu tanggal atau nilai. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
Menunjukkan apakah unit minor sumbu secara otomatis ditetapkan. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```


Menunjukkan apakah unit minor sumbu secara otomatis ditetapkan. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```


Mewakili unit mayor untuk sumbu tanggal atau nilai. Baca/tulis double.

**Mengembalikan:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```


Mewakili unit mayor untuk sumbu tanggal atau nilai. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```


Menunjukkan apakah unit mayor sumbu secara otomatis ditetapkan. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```


Menunjukkan apakah unit mayor sumbu secara otomatis ditetapkan. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```


Menunjukkan apakah nilai minimum secara otomatis ditetapkan. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```


Menunjukkan apakah nilai minimum secara otomatis ditetapkan. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```


Mewakili nilai minimum pada sumbu nilai. Baca/tulis double.

**Mengembalikan:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```


Mewakili nilai minimum pada sumbu nilai. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```


Mewakili apakah tipe skala sumbu nilai logaritmik atau tidak. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```


Mewakili apakah tipe skala sumbu nilai logaritmik atau tidak. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```


Mewakili basis logaritma. Nilai default adalah 10. Baca/tulis double.

**Mengembalikan:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```


Mewakili basis logaritma. Nilai default adalah 10. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```


Mewakili apakah MS PowerPoint memplot titik data dari akhir ke awal. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```


Mewakili apakah MS PowerPoint memplot titik data dari akhir ke awal. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Mewakili apakah sumbu terlihat. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Mewakili apakah sumbu terlihat. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```


Mewakili tipe tanda centang mayor untuk sumbu yang ditentukan. Baca/tulis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Mengembalikan:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```


Mewakili tipe tanda centang mayor untuk sumbu yang ditentukan. Baca/tulis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```


Mewakili tipe tanda centang minor untuk sumbu yang ditentukan. Baca/tulis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Mengembalikan:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```


Mewakili tipe tanda centang minor untuk sumbu yang ditentukan. Baca/tulis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```


Mewakili posisi label tanda centang pada sumbu yang ditentukan. Baca/tulis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Mengembalikan:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```


Mewakili posisi label tanda centang pada sumbu yang ditentukan. Baca/tulis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```


Mewakili skala unit mayor untuk sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Mengembalikan:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```


Mewakili skala unit mayor untuk sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```


Mewakili skala unit mayor untuk sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Mengembalikan:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```


Mewakili skala unit mayor untuk sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```


Menentukan satuan waktu terkecil yang diwakili pada sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Mengembalikan:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```


Menentukan satuan waktu terkecil yang diwakili pada sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```


Mewakili format garis kisi minor pada sumbu diagram. Baca saja [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Mengembalikan:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```


Mewakili format garis kisi mayor pada sumbu diagram. Baca saja [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Mengembalikan:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```


Untuk menyembunyikan garis kisi minor, atur MinorGridLinesFormat.Line.FillFormat.FillType ke FillType.NoFill. Baca saja boolean.

**Mengembalikan:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMinorGridLines()
```


Untuk menyembunyikan garis kisi mayor, atur MajorGridLinesFormat.Line.FillFormat.FillType ke FillType.NoFill. Baca saja boolean.

**Mengembalikan:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```


Mewakili format sumbu. Baca saja [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Mengembalikan:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Mewakili format teks. Baca saja [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Mengembalikan:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```


Mendapatkan judul sumbu. Baca saja [IChartTitle](../../com.aspose.slides/icharttitle).

**Mengembalikan:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```


Mewakili CrossType pada sumbu yang ditentukan di mana sumbu lain memotong. Baca/tulis [CrossesType](../../com.aspose.slides/crossestype).

**Mengembalikan:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```


Mewakili CrossType pada sumbu yang ditentukan di mana sumbu lain memotong. Baca/tulis [CrossesType](../../com.aspose.slides/crossestype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


Mewakili posisi sumbu. Baca/tulis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Mengembalikan:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Mewakili posisi sumbu. Baca/tulis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


Menentukan apakah sumbu memiliki judul yang terlihat. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


Menentukan apakah sumbu memiliki judul yang terlihat. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


Mewakili string format untuk Label Sumbu. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```


Mewakili string format untuk Label Sumbu. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


Menunjukkan apakah format terhubung ke data sumber. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


Menunjukkan apakah format terhubung ke data sumber. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```


Mewakili sudut rotasi label tanda centang. Baca/tulis float.

**Mengembalikan:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```


Mewakili sudut rotasi label tanda centang. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```


Menentukan berapa banyak label tanda centang yang dilewati di antara label yang digambar. Diterapkan pada sumbu kategori atau seri. Baca/tulis long.

**Mengembalikan:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```


Menentukan berapa banyak label tanda centang yang dilewati di antara label yang digambar. Diterapkan pada sumbu kategori atau seri. Baca/tulis long.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```


Menentukan nilai spasi label tanda centang otomatis. Jika false: gunakan properti TickLabelSpacing. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```


Menentukan nilai spasi label tanda centang otomatis. Jika false: gunakan properti TickLabelSpacing. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```


Menentukan berapa banyak tanda centang yang dilewati sebelum yang berikutnya digambar. Diterapkan pada sumbu kategori atau seri. Baca/tulis int.

**Mengembalikan:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```


Menentukan berapa banyak tanda centang yang dilewati sebelum yang berikutnya digambar. Diterapkan pada sumbu kategori atau seri. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```


Menentukan nilai spasi tanda centang otomatis. Jika false: gunakan properti TickMarksSpacing. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```


Menentukan nilai spasi tanda centang otomatis. Jika false: gunakan properti TickMarksSpacing. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```


Menentukan jarak label dari sumbu. Diterapkan pada sumbu kategori atau tanggal. Nilai harus antara 0% dan 1000%. Baca/tulis int.

**Mengembalikan:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```


Menentukan jarak label dari sumbu. Diterapkan pada sumbu kategori atau tanggal. Nilai harus antara 0% dan 1000%. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Mewakili tipe agregasi pada sumbu kategori (binning). Diterapkan pada kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Mengembalikan:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Mewakili tipe agregasi pada sumbu kategori (binning). Diterapkan pada kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Menentukan lebar bin ketika nilai properti AggregationType diatur ke AxisAggregationType.ByBinWidth. Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Mengembalikan:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Menentukan lebar bin ketika nilai properti AggregationType diatur ke AxisAggregationType.ByBinWidth. Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Menentukan jumlah bin ketika nilai properti AggregationType diatur ke AxisAggregationType.ByNumberOfBins. Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Mengembalikan:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Menentukan jumlah bin ketika nilai properti AggregationType diatur ke AxisAggregationType.ByNumberOfBins. Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |
### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Menentukan apakah bin overflow diterapkan. Gunakan IsAutomaticOverflowBin dan OverflowBin untuk menyesuaikan nilai bin overflow.

**Mengembalikan:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Menentukan apakah bin overflow diterapkan. Gunakan IsAutomaticOverflowBin dan OverflowBin untuk menyesuaikan nilai bin overflow.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Menentukan nilai bin overflow otomatis. Jika false: gunakan properti OverflowBin.

**Mengembalikan:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Menentukan nilai bin overflow otomatis. Jika false: gunakan properti OverflowBin.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Menentukan nilai khusus bin overflow. Diterapkan ketika properti IsAutomaticOverflowBin diatur ke false dan properti IsOverflowBin bernilai true.

**Mengembalikan:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Menentukan nilai khusus bin overflow. Diterapkan ketika properti IsAutomaticOverflowBin diatur ke false dan properti IsOverflowBin bernilai true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Menentukan apakah bin underflow diterapkan. Gunakan IsAutomaticUnderflowBin dan UnderflowBin untuk menyesuaikan nilai bin underflow.

**Mengembalikan:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Menentukan apakah bin underflow diterapkan. Gunakan IsAutomaticUnderflowBin dan UnderflowBin untuk menyesuaikan nilai bin underflow.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Menentukan nilai bin underflow otomatis. Jika false: gunakan properti UnderflowBin.

**Mengembalikan:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Menentukan nilai bin underflow otomatis. Jika false: gunakan properti UnderflowBin.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Menentukan nilai khusus bin underflow. Diterapkan ketika properti IsAutomaticUnderflowBin diatur ke false dan properti IsUnderflowBin bernilai true.

**Mengembalikan:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Menentukan nilai khusus bin underflow. Diterapkan ketika properti IsAutomaticUnderflowBin diatur ke false dan properti IsUnderflowBin bernilai true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide induk dari FillFormat. Baca-saja [BaseSlide](../../com.aspose.slides/baseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk dari FillFormat. Baca-saja [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)