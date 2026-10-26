---
title: Axis
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mengkapsulkan objek yang mewakili sumbu diagram.
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

Mengkapsulkan objek yang mewakili sumbu diagram.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getChart()](#getChart--) | Mengembalikan diagram induk. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Menyatakan apakah sumbu nilai melintasi sumbu kategori di antara kategori. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Menyatakan apakah sumbu nilai melintasi sumbu kategori di antara kategori. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Menentukan jenis sumbu kategori. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Menentukan jenis sumbu kategori. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Menetapkan properti IAxis.CategoryAxisType dengan nilai yang secara otomatis ditentukan berdasarkan data sumbu. |
| [getCrossAt()](#getCrossAt--) | Menyatakan titik pada sumbu di mana sumbu tegak lurus melintasinya. |
| [setCrossAt(float value)](#setCrossAt-float-) | Menyatakan titik pada sumbu di mana sumbu tegak lurus melintasinya. |
| [getDisplayUnit()](#getDisplayUnit--) | Menentukan nilai skala unit tampilan untuk sumbu nilai. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Menentukan nilai skala unit tampilan untuk sumbu nilai. |
| [getActualMaxValue()](#getActualMaxValue--) | Menentukan nilai maksimum aktual pada sumbu. |
| [getActualMinValue()](#getActualMinValue--) | Menentukan nilai minimum aktual pada sumbu. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Menentukan unit mayor aktual pada sumbu. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Menentukan unit minor aktual pada sumbu. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Menentukan skala unit mayor aktual pada sumbu. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Menentukan skala unit minor aktual pada sumbu. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Menunjukkan apakah nilai maksimum ditetapkan secara otomatis. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Menunjukkan apakah nilai maksimum ditetapkan secara otomatis. |
| [getMaxValue()](#getMaxValue--) | Menyatakan nilai maksimum pada sumbu nilai. |
| [setMaxValue(double value)](#setMaxValue-double-) | Menyatakan nilai maksimum pada sumbu nilai. |
| [getMinorUnit()](#getMinorUnit--) | Menyatakan unit minor untuk sumbu tanggal atau nilai. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Menyatakan unit minor untuk sumbu tanggal atau nilai. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Menunjukkan apakah unit minor sumbu ditetapkan secara otomatis. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Menunjukkan apakah unit minor sumbu ditetapkan secara otomatis. |
| [getMajorUnit()](#getMajorUnit--) | Menyatakan unit mayor untuk sumbu tanggal atau nilai. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Menyatakan unit mayor untuk sumbu tanggal atau nilai. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Menunjukkan apakah unit mayor sumbu ditetapkan secara otomatis. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Menunjukkan apakah unit mayor sumbu ditetapkan secara otomatis. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Menunjukkan apakah nilai minimum ditetapkan secara otomatis. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Menunjukkan apakah nilai minimum ditetapkan secara otomatis. |
| [getMinValue()](#getMinValue--) | Menyatakan nilai minimum pada sumbu nilai. |
| [setMinValue(double value)](#setMinValue-double-) | Menyatakan nilai minimum pada sumbu nilai. |
| [isLogarithmic()](#isLogarithmic--) | Menyatakan apakah jenis skala sumbu nilai bersifat logaritmik atau tidak. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Menyatakan apakah jenis skala sumbu nilai bersifat logaritmik atau tidak. |
| [getLogBase()](#getLogBase--) | Menyatakan basis logaritmik. |
| [setLogBase(double value)](#setLogBase-double-) | Menyatakan basis logaritmik. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Menyatakan apakah MS PowerPoint memplot titik data dari yang terakhir ke yang pertama. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Menyatakan apakah MS PowerPoint memplot titik data dari yang terakhir ke yang pertama. |
| [isVisible()](#isVisible--) | Menyatakan apakah sumbu terlihat. |
| [setVisible(boolean value)](#setVisible-boolean-) | Menyatakan apakah sumbu terlihat. |
| [getMajorTickMark()](#getMajorTickMark--) | Menyatakan jenis tanda centang mayor untuk sumbu yang ditentukan. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Menyatakan jenis tanda centang mayor untuk sumbu yang ditentukan. |
| [getMinorTickMark()](#getMinorTickMark--) | Menyatakan jenis tanda centang minor untuk sumbu yang ditentukan. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Menyatakan jenis tanda centang minor untuk sumbu yang ditentukan. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Menyatakan posisi label tanda centang pada sumbu yang ditentukan. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Menyatakan posisi label tanda centang pada sumbu yang ditentukan. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Menyatakan skala unit mayor untuk sumbu tanggal. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Menyatakan skala unit mayor untuk sumbu tanggal. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Menyatakan skala unit mayor untuk sumbu tanggal. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Menyatakan skala unit mayor untuk sumbu tanggal. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Menentukan unit waktu terkecil yang direpresentasikan pada sumbu tanggal. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Menentukan unit waktu terkecil yang direpresentasikan pada sumbu tanggal. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Menyatakan format garis kisi minor pada sumbu diagram. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Menyatakan format garis kisi mayor pada sumbu diagram. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Untuk menyembunyikan garis kisi minor, atur MinorGridLinesFormat.Line.FillFormat.FillType ke FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Untuk menyembunyikan garis kisi mayor, atur MajorGridLinesFormat.Line.FillFormat.FillType ke FillType.NoFill. |
| [getFormat()](#getFormat--) | Menyatakan format sumbu. |
| [getTextFormat()](#getTextFormat--) | Menyatakan format teks. |
| [getTitle()](#getTitle--) | Mendapatkan judul sumbu. |
| [getCrossType()](#getCrossType--) | Menyatakan CrossType pada sumbu yang ditentukan di mana sumbu lain melintasinya. |
| [setCrossType(int value)](#setCrossType-int-) | Menyatakan CrossType pada sumbu yang ditentukan di mana sumbu lain melintasinya. |
| [getPosition()](#getPosition--) | Menyatakan posisi sumbu. |
| [setPosition(int value)](#setPosition-int-) | Menyatakan posisi sumbu. |
| [hasTitle()](#hasTitle--) | Menentukan apakah sumbu memiliki judul yang terlihat. |
| [setTitle(boolean value)](#setTitle-boolean-) | Menentukan apakah sumbu memiliki judul yang terlihat. |
| [getNumberFormat()](#getNumberFormat--) | Menyatakan string format untuk Label Sumbu. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Menyatakan string format untuk Label Sumbu. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Menunjukkan apakah format terhubung ke data sumber. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Menunjukkan apakah format terhubung ke data sumber. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Menyatakan sudut rotasi label tanda centang. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Menyatakan sudut rotasi label tanda centang. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Menentukan berapa banyak label tanda centang yang dilewati antara label yang digambar. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Menentukan berapa banyak label tanda centang yang dilewati antara label yang digambar. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Menentukan nilai jarak otomatis label tanda centang. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Menentukan nilai jarak otomatis label tanda centang. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Menentukan berapa banyak tanda centang yang harus dilewati sebelum yang berikutnya digambar. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Menentukan berapa banyak tanda centang yang harus dilewati sebelum yang berikutnya digambar. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Menentukan nilai jarak otomatis tanda centang. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Menentukan nilai jarak otomatis tanda centang. |
| [getLabelOffset()](#getLabelOffset--) | Menentukan jarak label dari sumbu. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Menentukan jarak label dari sumbu. |
| [getAggregationType()](#getAggregationType--) | Menyatakan tipe agregasi sumbu kategori (pembuatan bin). |
| [setAggregationType(int value)](#setAggregationType-int-) | Menyatakan tipe agregasi sumbu kategori (pembuatan bin). |
| [getBinWidth()](#getBinWidth--) | Menentukan lebar bin ketika nilai properti AggregationType disetel ke AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Menentukan lebar bin ketika nilai properti AggregationType disetel ke AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Menentukan jumlah bin ketika nilai properti AggregationType disetel ke AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Menentukan jumlah bin ketika nilai properti AggregationType disetel ke AxisAggregationType.ByNumberOfBins. |
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
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari FillFormat. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Mengembalikan diagram induk. Hanya-baca [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)
### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Menyatakan apakah sumbu nilai melintasi sumbu kategori di antara kategori. Properti ini hanya berlaku untuk sumbu kategori, dan tidak berlaku untuk diagram 3-D. Baca/tulis boolean.

**Returns:**
boolean
### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Menyatakan apakah sumbu nilai melintasi sumbu kategori di antara kategori. Properti ini hanya berlaku untuk sumbu kategori, dan tidak berlaku untuk diagram 3-D. Baca/tulis boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Menentukan jenis sumbu kategori. Baca/tulis [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Returns:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Menentukan jenis sumbu kategori. Baca/tulis [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Menetapkan properti IAxis.CategoryAxisType dengan nilai yang secara otomatis ditentukan berdasarkan data sumbu.
### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Menyatakan titik pada sumbu di mana sumbu tegak lurus melintasinya. Baca/tulis float.

**Returns:**
float
### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Menyatakan titik pada sumbu di mana sumbu tegak lurus melintasinya. Baca/tulis float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Menentukan nilai skala unit tampilan untuk sumbu nilai. Baca/tulis [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Returns:**
int
### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Menentukan nilai skala unit tampilan untuk sumbu nilai. Baca/tulis [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Menentukan nilai maksimum aktual pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual.

**Returns:**
double
### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Menentukan nilai minimum aktual pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual.

**Returns:**
double
### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Menentukan unit mayor aktual pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual.

**Returns:**
double
### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Menentukan unit minor aktual pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual.

**Returns:**
double
### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Menentukan skala unit mayor aktual pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual.

**Returns:**
int
### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Menentukan skala unit minor aktual pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual.

**Returns:**
int
### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Menunjukkan apakah nilai maksimum ditetapkan secara otomatis. Baca/tulis boolean.

**Returns:**
boolean
### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Menunjukkan apakah nilai maksimum ditetapkan secara otomatis. Baca/tulis boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Menyatakan nilai maksimum pada sumbu nilai. Baca/tulis double.

**Returns:**
double
### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Menyatakan nilai maksimum pada sumbu nilai. Baca/tulis double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Menyatakan unit minor untuk sumbu tanggal atau nilai. Baca/tulis double.

**Returns:**
double
### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Menyatakan unit minor untuk sumbu tanggal atau nilai. Baca/tulis double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

Menunjukkan apakah unit minor sumbu ditetapkan secara otomatis. Baca/tulis boolean.

**Returns:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

Menunjukkan apakah unit minor sumbu ditetapkan secara otomatis. Baca/tulis boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

Menyatakan unit mayor untuk sumbu tanggal atau nilai. Baca/tulis double.

**Returns:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

Menyatakan unit mayor untuk sumbu tanggal atau nilai. Baca/tulis double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

Menunjukkan apakah unit mayor sumbu ditetapkan secara otomatis. Baca/tulis boolean.

**Returns:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

Menunjukkan apakah unit mayor sumbu ditetapkan secara otomatis. Baca/tulis boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

Menunjukkan apakah nilai minimum ditetapkan secara otomatis. Baca/tulis boolean.

**Returns:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

Menunjukkan apakah nilai minimum ditetapkan secara otomatis. Baca/tulis boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

Menyatakan nilai minimum pada sumbu nilai. Baca/tulis double.

**Returns:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

Menyatakan nilai minimum pada sumbu nilai. Baca/tulis double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

Menyatakan apakah jenis skala sumbu nilai bersifat logaritmik atau tidak. Baca/tulis boolean.

**Returns:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

Menyatakan apakah jenis skala sumbu nilai bersifat logaritmik atau tidak. Baca/tulis boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

Menyatakan basis logaritmik. Nilai default adalah 10. Baca/tulis double.

**Returns:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

Menyatakan basis logaritmik. Nilai default adalah 10. Baca/tulis double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

Menyatakan apakah MS PowerPoint memplot titik data dari yang terakhir ke yang pertama. Baca/tulis boolean.

**Returns:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

Menyatakan apakah MS PowerPoint memplot titik data dari yang terakhir ke yang pertama. Baca/tulis boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Menyatakan apakah sumbu terlihat. Baca/tulis boolean.

**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Menyatakan apakah sumbu terlihat. Baca/tulis boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

Menyatakan jenis tanda centang mayor untuk sumbu yang ditentukan. Baca/tulis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Returns:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

Menyatakan jenis tanda centang mayor untuk sumbu yang ditentukan. Baca/tulis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

Menyatakan jenis tanda centang minor untuk sumbu yang ditentukan. Baca/tulis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Returns:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

Menyatakan jenis tanda centang minor untuk sumbu yang ditentukan. Baca/tulis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

Menyatakan posisi label tanda centang pada sumbu yang ditentukan. Baca/tulis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Returns:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

Menyatakan posisi label tanda centang pada sumbu yang ditentukan. Baca/tulis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

Menyatakan skala unit mayor untuk sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returns:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

Menyatakan skala unit mayor untuk sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

Menyatakan skala unit mayor untuk sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returns:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

Menyatakan skala unit mayor untuk sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

Menentukan unit waktu terkecil yang direpresentasikan pada sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returns:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

Menentukan unit waktu terkecil yang direpresentasikan pada sumbu tanggal. Baca/tulis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

Menyatakan format garis kisi minor pada sumbu diagram. Hanya-baca [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Returns:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

Menyatakan format garis kisi mayor pada sumbu diagram. Hanya-baca [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Returns:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

Untuk menyembunyikan garis kisi minor, atur MinorGridLinesFormat.Line.FillFormat.FillType ke FillType.NoFill. Hanya-baca boolean.

**Returns:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

Untuk menyembunyikan garis kisi mayor, atur MajorGridLinesFormat.Line.FillFormat.FillType ke FillType.NoFill. Hanya-baca boolean.

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

Menyatakan format sumbu. Hanya-baca [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Returns:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Menyatakan format teks. Hanya-baca [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returns:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

Mendapatkan judul sumbu. Hanya-baca [IChartTitle](../../com.aspose.slides/icharttitle).

**Returns:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

Menyatakan CrossType pada sumbu yang ditentukan di mana sumbu lain melintasinya. Baca/tulis [CrossesType](../../com.aspose.slides/crossestype).

**Returns:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

Menyatakan CrossType pada sumbu yang ditentukan di mana sumbu lain melintasinya. Baca/tulis [CrossesType](../../com.aspose.slides/crossestype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Menyatakan posisi sumbu. Baca/tulis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Menyatakan posisi sumbu. Baca/tulis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Menentukan apakah sumbu memiliki judul yang terlihat. Baca/tulis boolean.

**Returns:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Menentukan apakah sumbu memiliki judul yang terlihat. Baca/tulis boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Menyatakan string format untuk Label Sumbu. Baca/tulis String.

**Returns:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Menyatakan string format untuk Label Sumbu. Baca/tulis String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Menunjukkan apakah format terhubung ke data sumber. Baca/tulis boolean.

**Returns:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Menunjukkan apakah format terhubung ke data sumber. Baca/tulis boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

Menyatakan sudut rotasi label tanda centang. Baca/tulis float.

**Returns:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

Menyatakan sudut rotasi label tanda centang. Baca/tulis float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

Menentukan berapa banyak label tanda centang yang dilewati antara label yang digambar. Diterapkan pada sumbu kategori atau seri. Baca/tulis long.

**Returns:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

Menentukan berapa banyak label tanda centang yang dilewati antara label yang digambar. Diterapkan pada sumbu kategori atau seri. Baca/tulis long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

Menentukan nilai jarak otomatis label tanda centang. Jika false: gunakan properti TickLabelSpacing. Baca/tulis boolean.

**Returns:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

Menentukan nilai jarak otomatis label tanda centang. Jika false: gunakan properti TickLabelSpacing. Baca/tulis boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

Menentukan berapa banyak tanda centang yang harus dilewati sebelum yang berikutnya digambar. Diterapkan pada sumbu kategori atau seri. Baca/tulis int.

**Returns:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

Menentukan berapa banyak tanda centang yang harus dilewati sebelum yang berikutnya digambar. Diterapkan pada sumbu kategori atau seri. Baca/tulis int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

Menentukan nilai jarak otomatis tanda centang. Jika false: gunakan properti TickMarksSpacing. Baca/tulis boolean.

**Returns:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

Menentukan nilai jarak otomatis tanda centang. Jika false: gunakan properti TickMarksSpacing. Baca/tulis boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

Menentukan jarak label dari sumbu. Diterapkan pada sumbu kategori atau tanggal. Nilai harus antara 0% dan 1000%. Baca/tulis int.

**Returns:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

Menentukan jarak label dari sumbu. Diterapkan pada sumbu kategori atau tanggal. Nilai harus antara 0% dan 1000%. Baca/tulis int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Menyatakan tipe agregasi sumbu kategori (pembuatan bin). Diterapkan pada kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Returns:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Menyatakan tipe agregasi sumbu kategori (pembuatan bin). Diterapkan pada kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Menentukan lebar bin ketika nilai properti AggregationType disetel ke AxisAggregationType.ByBinWidth. Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Returns:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Menentukan lebar bin ketika nilai properti AggregationType disetel ke AxisAggregationType.ByBinWidth. Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Menentukan jumlah bin ketika nilai properti AggregationType disetel ke AxisAggregationType.ByNumberOfBins. Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Returns:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Menentukan jumlah bin ketika nilai properti AggregationType disetel ke AxisAggregationType.ByNumberOfBins. Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Menentukan apakah bin overflow diterapkan. Gunakan IsAutomaticOverflowBin dan OverflowBin untuk menyesuaikan nilai bin overflow.

**Returns:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Menentukan apakah bin overflow diterapkan. Gunakan IsAutomaticOverflowBin dan OverflowBin untuk menyesuaikan nilai bin overflow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Menentukan nilai bin overflow otomatis. Jika false: gunakan properti OverflowBin.

**Returns:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Menentukan nilai bin overflow otomatis. Jika false: gunakan properti OverflowBin.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Menentukan nilai khusus bin overflow. Diterapkan ketika properti IsAutomaticOverflowBin disetel ke false dan properti IsOverflowBin bernilai true.

**Returns:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Menentukan nilai khusus bin overflow. Diterapkan ketika properti IsAutomaticOverflowBin disetel ke false dan properti IsOverflowBin bernilai true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Menentukan apakah bin underflow diterapkan. Gunakan IsAutomaticUnderflowBin dan UnderflowBin untuk menyesuaikan nilai bin underflow.

**Returns:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Menentukan apakah bin underflow diterapkan. Gunakan IsAutomaticUnderflowBin dan UnderflowBin untuk menyesuaikan nilai bin underflow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Menentukan nilai bin underflow otomatis. Jika false: gunakan properti UnderflowBin.

**Returns:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Menentukan nilai bin underflow otomatis. Jika false: gunakan properti UnderflowBin.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Menentukan nilai khusus bin underflow. Diterapkan ketika properti IsAutomaticUnderflowBin disetel ke false dan properti IsUnderflowBin bernilai true.

**Returns:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Menentukan nilai khusus bin underflow. Diterapkan ketika properti IsAutomaticUnderflowBin disetel ke false dan properti IsUnderflowBin bernilai true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide induk dari FillFormat. Hanya-baca [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk dari FillFormat. Hanya-baca [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)