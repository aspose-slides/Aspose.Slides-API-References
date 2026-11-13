---
title: DataLabel
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili label seri.
type: docs
url: /id/com.aspose.slides/datalabel/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Mewakili label seri.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Membuat instance baru dari kelas DataLabel. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Mengembalikan chart induk. |
| [isVisible()](#isVisible--) | False berarti label data tidak terlihat (dan semua Show\\*-flags (ShowValue, ...) menjadi false). |
| [hide()](#hide--) | Menyembunyikan label data dengan mengatur semua Show\\*-flags (ShowValue, ...) ke keadaan false. |
| [getActualLabelText()](#getActualLabelText--) | Mengembalikan teks label sebenarnya berdasarkan pengaturan DataLabelFormat atau nilai TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inisialisasi TextFrameForOverriding dengan teks pada parameter "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Dapat berisi teks berformat kaya. |
| [getTextFormat()](#getTextFormat--) | Mengembalikan format teks. |
| [getX()](#getX--) | Mengembalikan atau mengatur koordinat x judul sebagai fraksi lebar chart. |
| [setX(float value)](#setX-float-) | Mengembalikan atau mengatur koordinat x judul sebagai fraksi lebar chart. |
| [getY()](#getY--) | Mengembalikan atau mengatur koordinat y judul sebagai fraksi tinggi chart. |
| [setY(float value)](#setY-float-) | Mengembalikan atau mengatur koordinat y judul sebagai fraksi tinggi chart. |
| [getWidth()](#getWidth--) | Mengembalikan atau mengatur lebar judul sebagai fraksi lebar chart. |
| [setWidth(float value)](#setWidth-float-) | Mengembalikan atau mengatur lebar judul sebagai fraksi lebar chart. |
| [getHeight()](#getHeight--) | Mengembalikan atau mengatur tinggi judul sebagai fraksi tinggi chart. |
| [setHeight(float value)](#setHeight-float-) | Mengembalikan atau mengatur tinggi judul sebagai fraksi tinggi chart. |
| [getRight()](#getRight--) | Kanan. |
| [getBottom()](#getBottom--) | Bawah. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Mengembalikan format label data. |
| [getValueFromCell()](#getValueFromCell--) | Mendapatkan atau mengatur sel data workbook. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Mendapatkan atau mengatur sel data workbook. |
| [getLabelShapeType()](#getLabelShapeType--) | Mendapatkan atau mengatur tipe bentuk label data. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Mendapatkan atau mengatur tipe bentuk label data. |
| [getActualX()](#getActualX--) | Menentukan lokasi x aktual (kiri) elemen chart relatif terhadap sudut kiri atas chart. |
| [getActualY()](#getActualY--) | Menentukan posisi atas aktual elemen chart relatif terhadap sudut kiri atas chart. |
| [getActualWidth()](#getActualWidth--) | Menentukan lebar aktual elemen chart. |
| [getActualHeight()](#getActualHeight--) | Menentukan tinggi aktual elemen chart. |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari FillFormat. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Membuat instance baru dari kelas DataLabel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ChartDataPoint induk. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Baca-saja IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Mengembalikan chart induk. Baca-saja [IChart](../../com.aspose.slides/ichart).

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False berarti label data tidak terlihat (dan semua Show\\*-flags (ShowValue, ...) menjadi false). Baca-saja boolean.

--------------------

Jika label data terlihat, Anda dapat menyembunyikannya dengan metode Hide(). Namun jika label data tidak terlihat (IsVisible adalah false), Anda dapat membuat label data terlihat dengan mengatur Show\\*-flags (ShowValue, ...) ke keadaan true.

**Mengembalikan:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Menyembunyikan label data dengan mengatur semua Show\\*-flags (ShowValue, ...) ke keadaan false. IsVisible akan menjadi false setelah ini.

--------------------

Jika label data tidak terlihat (IsVisible adalah false), Anda dapat membuat label data terlihat dengan mengatur Show\\*-flags (ShowValue, ...) ke keadaan true.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Mengembalikan teks label sebenarnya berdasarkan pengaturan DataLabelFormat atau nilai TextFrameForOverriding.Text.

**Mengembalikan:**
java.lang.String - objek java.lang.String.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inisialisasi TextFrameForOverriding dengan teks pada parameter "text". Jika TextFrameForOverriding sudah diinisialisasi maka cukup mengubah teksnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks untuk TextFrameForOverriding baru. |

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Dapat berisi teks berformat kaya. Jika properti ini tidak null maka nilai teks berformat ini menggantikan teks yang dihasilkan otomatis dari label data. Teks yang dihasilkan otomatis dari label data berarti teks yang dikelola oleh properti ShowSeriesName, ShowValue, ... dan diformat dengan properti TextFormatManager.TextFormat. Baca-saja [ITextFrame](../../com.aspose.slides/itextframe).

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Mengembalikan format teks. Baca-saja [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Mengembalikan:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Mengembalikan atau mengatur koordinat x judul sebagai fraksi lebar chart. Baca/tulis float.

**Mengembalikan:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Mengembalikan atau mengatur koordinat x judul sebagai fraksi lebar chart. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Mengembalikan atau mengatur koordinat y judul sebagai fraksi tinggi chart. Baca/tulis float.

**Mengembalikan:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Mengembalikan atau mengatur koordinat y judul sebagai fraksi tinggi chart. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Mengembalikan atau mengatur lebar judul sebagai fraksi lebar chart. Baca/tulis float.

**Mengembalikan:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Mengembalikan atau mengatur lebar judul sebagai fraksi lebar chart. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Mengembalikan atau mengatur tinggi judul sebagai fraksi tinggi chart. Baca/tulis float.

**Mengembalikan:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Mengembalikan atau mengatur tinggi judul sebagai fraksi tinggi chart. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

Kanan. Baca-saja float.

**Mengembalikan:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Bawah. Baca-saja float.

**Mengembalikan:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Mengembalikan format label data. Baca-saja [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Mengembalikan:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Mendapatkan atau mengatur sel data workbook. Diterapkan jika properti IDataLabelFormat.ShowLabelValueFromCell bernilai true.

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Mendapatkan atau mengatur sel data workbook. Diterapkan jika properti IDataLabelFormat.ShowLabelValueFromCell bernilai true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```

Mendapatkan atau mengatur tipe bentuk label data. Mengembalikan [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) jika tidak ada bentuk yang didefinisikan.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Atur tipe bentuk label data pertama menjadi Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public final void setLabelShapeType(int value)
```

Mendapatkan atau mengatur tipe bentuk label data. Mengembalikan [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) jika tidak ada bentuk yang didefinisikan.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Atur tipe bentuk label data pertama menjadi Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Menentukan lokasi x aktual (kiri) elemen chart relatif terhadap sudut kiri atas chart. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. Baca float.

**Mengembalikan:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Menentukan posisi atas aktual elemen chart relatif terhadap sudut kiri atas chart. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. Baca float.

**Mengembalikan:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Menentukan lebar aktual elemen chart. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. Baca float.

**Mengembalikan:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Menentukan tinggi aktual elemen chart. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. Baca float.

**Mengembalikan:**
float
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