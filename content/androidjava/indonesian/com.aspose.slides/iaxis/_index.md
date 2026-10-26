---
title: IAxis
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menyatukan objek yang merepresentasikan sumbu grafik.
type: docs
url: /id/com.aspose.slides/iaxis/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Mewakili objek yang merepresentasikan sumbu grafik.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Mewakili apakah sumbu nilai melintasi sumbu kategori di antara kategori. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Mewakili apakah sumbu nilai melintasi sumbu kategori di antara kategori. |
| [getCrossAt()](#getCrossAt--) | Mewakili titik pada sumbu tempat sumbu tegak lurus melintasinya. |
| [setCrossAt(float value)](#setCrossAt-float-) | Mewakili titik pada sumbu tempat sumbu tegak lurus melintasinya. |
| [getDisplayUnit()](#getDisplayUnit--) | Menentukan nilai skala unit tampilan untuk sumbu nilai. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Menentukan nilai skala unit tampilan untuk sumbu nilai. |
| [getActualMaxValue()](#getActualMaxValue--) | Menentukan nilai maksimum sebenarnya pada sumbu. |
| [getActualMinValue()](#getActualMinValue--) | Menentukan nilai minimum sebenarnya pada sumbu. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Menentukan satuan utama sebenarnya pada sumbu. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Menentukan satuan minor sebenarnya pada sumbu. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Menentukan skala satuan utama sebenarnya pada sumbu. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Menentukan skala satuan minor sebenarnya pada sumbu. |
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
| [isLogarithmic()](#isLogarithmic--) | Mewakili apakah tipe skala sumbu nilai logaritmik atau tidak. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Mewakili apakah tipe skala sumbu nilai logaritmik atau tidak. |
| [getLogBase()](#getLogBase--) | Mewakili basis logaritmik. |
| [setLogBase(double value)](#setLogBase-double-) | Mewakili basis logaritmik. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Mewakili apakah MS PowerPoint memplot titik data dari terakhir ke pertama. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Mewakili apakah MS PowerPoint memplot titik data dari terakhir ke pertama. |
| [isVisible()](#isVisible--) | Mewakili apakah sumbu terlihat. |
| [setVisible(boolean value)](#setVisible-boolean-) | Mewakili apakah sumbu terlihat. |
| [getMajorTickMark()](#getMajorTickMark--) | Mewakili tipe tanda centang utama untuk sumbu yang ditentukan. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Mewakili tipe tanda centang utama untuk sumbu yang ditentukan. |
| [getMinorTickMark()](#getMinorTickMark--) | Mewakili tipe tanda centang minor untuk sumbu yang ditentukan. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Mewakili tipe tanda centang minor untuk sumbu yang ditentukan. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Mewakili posisi label tanda centang pada sumbu yang ditentukan. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Mewakili posisi label tanda centang pada sumbu yang ditentukan. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Mewakili skala satuan utama untuk sumbu tanggal. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Mewakili skala satuan utama untuk sumbu tanggal. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Mewakili skala satuan utama untuk sumbu tanggal. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Mewakili skala satuan utama untuk sumbu tanggal. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Menentukan unit waktu terkecil yang diwakili pada sumbu tanggal. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Menentukan unit waktu terkecil yang diwakili pada sumbu tanggal. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Mewakili format garis kisi minor pada sumbu grafik. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Mewakili format garis kisi utama pada sumbu grafik. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Mewakili apakah garis kisi minor ditampilkan. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Mewakili apakah garis kisi utama ditampilkan. |
| [getFormat()](#getFormat--) | Mewakili format sumbu. |
| [getTitle()](#getTitle--) | Mendapatkan judul sumbu. |
| [getCrossType()](#getCrossType--) | Mewakili CrossType pada sumbu yang ditentukan di mana sumbu lain melintasinya. |
| [setCrossType(int value)](#setCrossType-int-) | Mewakili CrossType pada sumbu yang ditentukan di mana sumbu lain melintasinya. |
| [getPosition()](#getPosition--) | Mewakili posisi sumbu. |
| [setPosition(int value)](#setPosition-int-) | Mewakili posisi sumbu. |
| [hasTitle()](#hasTitle--) | Menentukan apakah suatu sumbu memiliki judul yang terlihat. |
| [setTitle(boolean value)](#setTitle-boolean-) | Menentukan apakah suatu sumbu memiliki judul yang terlihat. |
| [getNumberFormat()](#getNumberFormat--) | Mewakili string format untuk Label Sumbu. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Mewakili string format untuk Label Sumbu. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Menunjukkan apakah format terhubung ke data sumber. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Menunjukkan apakah format terhubung ke data sumber. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Mewakili sudut rotasi label centang Baca/tulis float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Mewakili sudut rotasi label centang Baca/tulis float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Menentukan berapa banyak label centang yang dilewati antara label yang digambar. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Menentukan berapa banyak label centang yang dilewati antara label yang digambar. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Menentukan nilai jarak otomatis label centang. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Menentukan nilai jarak otomatis label centang. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Menentukan berapa banyak tanda centang yang harus dilewatkan sebelum tanda berikutnya digambar. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Menentukan berapa banyak tanda centang yang harus dilewatkan sebelum tanda berikutnya digambar. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Menentukan nilai jarak otomatis tanda centang. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Menentukan nilai jarak otomatis tanda centang. |
| [getLabelOffset()](#getLabelOffset--) | Menentukan jarak label dari sumbu. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Menentukan jarak label dari sumbu. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Menentukan tipe sumbu kategori. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Menentukan tipe sumbu kategori. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Mengatur properti IAxis.CategoryAxisType dengan nilai yang ditentukan secara otomatis berdasarkan data sumbu. |
| [getAggregationType()](#getAggregationType--) | Mewakili tipe agregasi sumbu kategori (pengelompokan). |
| [setAggregationType(int value)](#setAggregationType-int-) | Mewakili tipe agregasi sumbu kategori (pengelompokan). |
| [getBinWidth()](#getBinWidth--) | Menentukan lebar bin ketika nilai properti AggregationType diatur ke AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Menentukan lebar bin ketika nilai properti AggregationType diatur ke AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Menentukan jumlah bin ketika nilai properti AggregationType diatur ke AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Menentukan jumlah bin ketika nilai properti AggregationType diatur ke AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Menentukan apakah bin overflow diterapkan. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Menentukan apakah bin overflow diterapkan. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Menentukan nilai overflow bin otomatis. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Menentukan nilai overflow bin otomatis. |
| [getOverflowBin()](#getOverflowBin--) | Menentukan nilai khusus overflow bin. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Menentukan nilai khusus overflow bin. |
| [isUnderflowBin()](#isUnderflowBin--) | Menentukan apakah bin underflow diterapkan. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Menentukan apakah bin underflow diterapkan. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Menentukan nilai underflow bin otomatis. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Menentukan nilai underflow bin otomatis. |
| [getUnderflowBin()](#getUnderflowBin--) | Menentukan nilai khusus underflow bin. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Menentukan nilai khusus underflow bin. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Mewakili apakah sumbu nilai melintasi sumbu kategori di antara kategori. Properti ini hanya berlaku untuk sumbu kategori, dan tidak berlaku pada grafik 3-D. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Mewakili apakah sumbu nilai melintasi sumbu kategori di antara kategori. Properti ini hanya berlaku untuk sumbu kategori, dan tidak berlaku pada grafik 3-D. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Mewakili titik pada sumbu tempat sumbu tegak lurus melintasinya. Baca/tulis float.

**Mengembalikan:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Mewakili titik pada sumbu tempat sumbu tegak lurus melintasinya. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Menentukan nilai skala unit tampilan untuk sumbu nilai. Baca/tulis [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Mengembalikan:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Menentukan nilai skala unit tampilan untuk sumbu nilai. Baca/tulis [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Menentukan nilai maksimum sebenarnya pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai sebenarnya.

**Mengembalikan:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Menentukan nilai minimum sebenarnya pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai sebenarnya.

**Mengembalikan:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Menentukan satuan utama sebenarnya pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai sebenarnya.

**Mengembalikan:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Menentukan satuan minor sebenarnya pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai sebenarnya.

**Mengembalikan:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Menentukan skala satuan utama sebenarnya pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai sebenarnya.

**Mengembalikan:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Menentukan skala satuan minor sebenarnya pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai sebenarnya.

**Mengembalikan:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Menunjukkan apakah nilai maksimum ditetapkan secara otomatis. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Menunjukkan apakah nilai maksimum ditetapkan secara otomatis. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Mewakili nilai maksimum pada sumbu nilai. Baca/tulis double.

**Mengembalikan:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Mewakili nilai maksimum pada sumbu nilai. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Mewakili satuan minor untuk sumbu tanggal atau nilai. Baca/tulis double.

**Mengembalikan:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Mewakili satuan minor untuk sumbu tanggal atau nilai. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Menunjukkan apakah satuan minor sumbu ditetapkan secara otomatis. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Menunjukkan apakah satuan minor sumbu ditetapkan secara otomatis. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Mewakili satuan utama untuk sumbu tanggal atau nilai. Baca/tulis double.

**Mengembalikan:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Mewakili satuan utama untuk sumbu tanggal atau nilai. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Menunjukkan apakah satuan utama sumbu ditetapkan secara otomatis. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Menunjukkan apakah satuan utama sumbu ditetapkan secara otomatis. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Menunjukkan apakah nilai minimum ditetapkan secara otomatis. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Menunjukkan apakah nilai minimum ditetapkan secara otomatis. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Mewakili nilai minimum pada sumbu nilai. Baca/tulis double.

**Mengembalikan:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Mewakili nilai minimum pada sumbu nilai. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Mewakili apakah tipe skala sumbu nilai logaritmik atau tidak. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Mewakili apakah tipe skala sumbu nilai logaritmik atau tidak. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Mewakili basis logaritmik. Nilai default adalah 10. Baca/tulis double.

**Mengembalikan:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Mewakili basis logaritmik. Nilai default adalah 10. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Mewakili apakah MS PowerPoint memplot titik data dari terakhir ke pertama. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Mewakili apakah MS PowerPoint memplot titik data dari terakhir ke pertama. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Mewakili apakah sumbu terlihat. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Mewakili apakah sumbu terlihat. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Mewakili tipe tanda centang utama untuk sumbu yang ditentukan. Baca/tulis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Mengembalikan:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Mewakili tipe tanda centang utama untuk sumbu yang ditentukan. Baca/tulis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Mewakili tipe tanda centang minor untuk sumbu yang ditentukan. Baca/tulis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Mengembalikan:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Mewakili tipe tanda centang minor untuk sumbu yang ditentukan. Baca/tulis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Mewakili posisi label tanda centang pada sumbu yang ditentukan. Baca/tulis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Mengembalikan:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Mewakili posisi label tanda centang pada sumbu yang ditentukan. Baca/tulis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Mewakili skala satuan utama untuk sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Mengembalikan:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Mewakili skala satuan utama untuk sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Mewakili skala satuan utama untuk sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Mengembalikan:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Mewakili skala satuan utama untuk sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Menentukan unit waktu terkecil yang diwakili pada sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Mengembalikan:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Menentukan unit waktu terkecil yang diwakili pada sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Mewakili format garis kisi minor pada sumbu grafik. Hanya-baca [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Mengembalikan:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Mewakili format garis kisi utama pada sumbu grafik. Hanya-baca [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Mengembalikan:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Mewakili apakah garis kisi minor ditampilkan. Hanya-baca boolean.

**Mengembalikan:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Mewakili apakah garis kisi utama ditampilkan. Hanya-baca boolean.

**Mengembalikan:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Mewakili format sumbu. Hanya-baca [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Mengembalikan:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Mendapatkan judul sumbu. Hanya-baca [IChartTitle](../../com.aspose.slides/icharttitle).

**Mengembalikan:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Mewakili CrossType pada sumbu yang ditentukan di mana sumbu lain melintasinya. Baca/tulis [CrossesType](../../com.aspose.slides/crossestype).

**Mengembalikan:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Mewakili CrossType pada sumbu yang ditentukan di mana sumbu lain melintasinya. Baca/tulis [CrossesType](../../com.aspose.slides/crossestype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Mewakili posisi sumbu. Baca/tulis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Mengembalikan:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Mewakili posisi sumbu. Baca/tulis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Menentukan apakah suatu sumbu memiliki judul yang terlihat. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Menentukan apakah suatu sumbu memiliki judul yang terlihat. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Mewakili string format untuk Label Sumbu. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Mewakili string format untuk Label Sumbu. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Menunjukkan apakah format terhubung ke data sumber. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Menunjukkan apakah format terhubung ke data sumber. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Mewakili sudut rotasi label centang. Baca/tulis float.

**Mengembalikan:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Mewakili sudut rotasi label centang. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Menentukan berapa banyak label centang yang dilewati antara label yang digambar. Baca/tulis long.

**Mengembalikan:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Menentukan berapa banyak label centang yang dilewati antara label yang digambar. Baca/tulis long.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Menentukan nilai jarak otomatis label centang. Jika false: gunakan properti TickLabelSpacing. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Menentukan nilai jarak otomatis label centang. Jika false: gunakan properti TickLabelSpacing. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Menentukan berapa banyak tanda centang yang harus dilewatkan sebelum tanda berikutnya digambar. Diterapkan pada sumbu kategori atau seri. Baca/tulis int.

**Mengembalikan:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Menentukan berapa banyak tanda centang yang harus dilewatkan sebelum tanda berikutnya digambar. Diterapkan pada sumbu kategori atau seri. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Menentukan nilai jarak otomatis tanda centang. Jika false: gunakan properti TickMarksSpacing. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Menentukan nilai jarak otomatis tanda centang. Jika false: gunakan properti TickMarksSpacing. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Menentukan jarak label dari sumbu. Diterapkan pada sumbu kategori atau tanggal. Nilai harus antara 0% dan 1000%. Baca/tulis int.

**Mengembalikan:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Menentukan jarak label dari sumbu. Diterapkan pada sumbu kategori atau tanggal. Nilai harus antara 0% dan 1000%. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Menentukan tipe sumbu kategori. Baca/tulis [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Mengembalikan:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Menentukan tipe sumbu kategori. Baca/tulis [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Mengatur properti IAxis.CategoryAxisType dengan nilai yang ditentukan secara otomatis berdasarkan data sumbu.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Mewakili tipe agregasi sumbu kategori (pengelompokan). Diterapkan pada kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Mengembalikan:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Mewakili tipe agregasi sumbu kategori (pengelompokan). Diterapkan pada kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Menentukan lebar bin ketika nilai properti AggregationType diatur ke AxisAggregationType.ByBinWidth. Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Mengembalikan:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Menentukan lebar bin ketika nilai properti AggregationType diatur ke AxisAggregationType.ByBinWidth. Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Menentukan jumlah bin ketika nilai properti AggregationType diatur ke AxisAggregationType.ByNumberOfBins. Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Mengembalikan:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Menentukan jumlah bin ketika nilai properti AggregationType diatur ke AxisAggregationType.ByNumberOfBins. Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Menentukan apakah bin overflow diterapkan. Gunakan IsAutomaticOverflowBin dan OverflowBin untuk menyesuaikan nilai bin overflow.

**Mengembalikan:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Menentukan apakah bin overflow diterapkan. Gunakan IsAutomaticOverflowBin dan OverflowBin untuk menyesuaikan nilai bin overflow.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Menentukan nilai overflow bin otomatis. Jika false: gunakan properti OverflowBin.

**Mengembalikan:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Menentukan nilai overflow bin otomatis. Jika false: gunakan properti OverflowBin.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Menentukan nilai khusus overflow bin. Diterapkan ketika properti IsAutomaticOverflowBin disetel ke false dan properti IsOverflowBin bernilai true.

**Mengembalikan:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Menentukan nilai khusus overflow bin. Diterapkan ketika properti IsAutomaticOverflowBin disetel ke false dan properti IsOverflowBin bernilai true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Menentukan apakah bin underflow diterapkan. Gunakan IsAutomaticUnderflowBin dan UnderflowBin untuk menyesuaikan nilai bin underflow.

**Mengembalikan:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Menentukan apakah bin underflow diterapkan. Gunakan IsAutomaticUnderflowBin dan UnderflowBin untuk menyesuaikan nilai bin underflow.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Menentukan nilai underflow bin otomatis. Jika false: gunakan properti UnderflowBin.

**Mengembalikan:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Menentukan nilai underflow bin otomatis. Jika false: gunakan properti UnderflowBin.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Menentukan nilai khusus underflow bin. Diterapkan ketika properti IsAutomaticUnderflowBin disetel ke false dan properti IsUnderflowBin bernilai true.

**Mengembalikan:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Menentukan nilai khusus underflow bin. Diterapkan ketika properti IsAutomaticUnderflowBin disetel ke false dan properti IsUnderflowBin bernilai true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |