---
title: DataLabelFormat
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili opsi pemformatan untuk DataLabel.
type: docs
url: /id/com.aspose.slides/datalabelformat/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Mewakili opsi pemformatan untuk DataLabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Baca/tulis boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Baca/tulis boolean. |
| [getNumberFormat()](#getNumberFormat--) | Mewakili string format untuk objek DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Mewakili string format untuk objek DataLabels. |
| [getFormat()](#getFormat--) | Mewakili format label data. |
| [getPosition()](#getPosition--) | Mewakili posisi label data. |
| [setPosition(int value)](#setPosition-int-) | Mewakili posisi label data. |
| [getShowLegendKey()](#getShowLegendKey--) | Mewakili perilaku tampilan kunci legenda label data pada diagram tertentu. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Mewakili perilaku tampilan kunci legenda label data pada diagram tertentu. |
| [getShowValue()](#getShowValue--) | Mewakili perilaku tampilan nilai persentase label data pada diagram tertentu. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Mewakili perilaku tampilan nilai persentase label data pada diagram tertentu. |
| [getShowCategoryName()](#getShowCategoryName--) | Mewakili perilaku tampilan nama kategori label data pada diagram tertentu. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Mewakili perilaku tampilan nama kategori label data pada diagram tertentu. |
| [getShowSeriesName()](#getShowSeriesName--) | Mengembalikan atau menetapkan Boolean untuk menunjukkan perilaku tampilan nama seri pada label data di diagram. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Mengembalikan atau menetapkan Boolean untuk menunjukkan perilaku tampilan nama seri pada label data di diagram. |
| [getShowPercentage()](#getShowPercentage--) | Mewakili perilaku tampilan nilai persentase label data pada diagram tertentu. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Mewakili perilaku tampilan nilai persentase label data pada diagram tertentu. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Mewakili perilaku tampilan nilai ukuran gelembung label data pada diagram tertentu. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Mewakili perilaku tampilan nilai ukuran gelembung label data pada diagram tertentu. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Mewakili perilaku tampilan garis pemimpin label data pada diagram tertentu. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Mewakili perilaku tampilan garis pemimpin label data pada diagram tertentu. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Mewakili perilaku tampilan nilai sel label data pada diagram tertentu. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Mewakili perilaku tampilan nilai sel label data pada diagram tertentu. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Menentukan apakah label data pada diagram tertentu akan ditampilkan sebagai panggilan data atau sebagai label data. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Menentukan apakah label data pada diagram tertentu akan ditampilkan sebagai panggilan data atau sebagai label data. |
| [getSeparator()](#getSeparator--) | Menetapkan atau mengembalikan Variant yang mewakili pemisah yang digunakan untuk label data pada diagram. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Menetapkan atau mengembalikan Variant yang mewakili pemisah yang digunakan untuk label data pada diagram. |
| [getTextFormat()](#getTextFormat--) | Mengembalikan format teks diagram. |
| [getChart()](#getChart--) | Mengembalikan diagram. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Baca-saja long.

**Mengembalikan:**
long
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection yang berisi label data, maka properti ini mendapatkan atau menetapkan nilai default properti IsNumberFormatLinkedToSource untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai tersebut ke properti IsNumberFormatLinkedToSource untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" menyebabkan semua DataLabels.get_Item(i).isNumberFormatLinkedToSource() menjadi equal dengan val).

**Mengembalikan:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection yang berisi label data, maka properti ini mendapatkan atau menetapkan nilai default properti IsNumberFormatLinkedToSource untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai tersebut ke properti IsNumberFormatLinkedToSource untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" menyebabkan semua DataLabels.get_Item(i).isNumberFormatLinkedToSource() menjadi equal dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Mewakili string format untuk objek DataLabels. Baca/tulis String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection yang berisi label data, maka properti ini mendapatkan atau menetapkan nilai default properti NumberFormat untuk label data baru dalam koleksi DataLabelCollection. Ketika properti ini diatur dengan nilai, nilai tersebut juga diatur untuk properti NumberFormat untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" menyebabkan semua DataLabels.get_Item(i).getNumberFormat() menjadi equal dengan val).

**Mengembalikan:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Mewakili string format untuk objek DataLabels. Baca/tulis String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection yang berisi label data, maka properti ini mendapatkan atau menetapkan nilai default properti NumberFormat untuk label data baru dalam koleksi DataLabelCollection. Ketika properti ini diatur dengan nilai, nilai tersebut juga diatur untuk properti NumberFormat untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" menyebabkan semua DataLabels.get_Item(i).getNumberFormat() menjadi equal dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Mewakili format label data. Baca-saja [IFormat](../../com.aspose.slides/iformat).

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection yang berisi label data, maka properti ini mewakili format default untuk label data baru dalam koleksi DataLabelCollection.

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Mewakili posisi label data. Baca/tulis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection yang berisi label data, maka properti ini mendapatkan atau menetapkan nilai default properti Position untuk label data baru dalam koleksi DataLabelCollection. Mewakili posisi untuk objek DataLabel. Menetapkan properti ini dengan nilai juga menetapkan nilai tersebut ke properti Position untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setPosition(val);" menyebabkan semua DataLabels.get_Item(i).getPosition() menjadi equal dengan val).

**Mengembalikan:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Mewakili posisi label data. Baca/tulis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection yang berisi label data, maka properti ini mendapatkan atau menetapkan nilai default properti Position untuk label data baru dalam koleksi DataLabelCollection. Mewakili posisi untuk objek DataLabel. Menetapkan properti ini dengan nilai juga menetapkan nilai tersebut ke properti Position untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setPosition(val);" menyebabkan semua DataLabels.get_Item(i).getPosition() menjadi equal dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Mewakili perilaku tampilan kunci legenda label data pada diagram tertentu. True jika kunci legenda label data terlihat. Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection yang berisi label data, maka properti ini mendapatkan atau menetapkan nilai default properti ShowLegendKey untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai tersebut ke properti ShowLegendKey untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" menyebabkan semua DataLabels.get_Item(i).getShowLegendKey() menjadi equal dengan val).

**Mengembalikan:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Mewakili perilaku tampilan kunci legenda label data pada diagram tertentu. True jika kunci legenda label data terlihat. Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection yang berisi label data, maka properti ini mendapatkan atau menetapkan nilai default properti ShowLegendKey untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai tersebut ke properti ShowLegendKey untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" menyebabkan semua DataLabels.get_Item(i).getShowLegendKey() menjadi equal dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Mewakili perilaku tampilan nilai persentase label data pada diagram tertentu. True menampilkan nilai persentase. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection yang berisi label data, maka properti ini mendapatkan atau menetapkan nilai default properti ShowValue untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai tersebut ke properti ShowValue untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" menyebabkan semua DataLabels.get_Item(i).getShowValue() menjadi equal dengan val).

**Mengembalikan:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Mewakili perilaku tampilan nilai persentase label data pada diagram tertentu. True menampilkan nilai persentase. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection yang berisi label data, maka properti ini mendapatkan atau menetapkan nilai default properti ShowValue untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai tersebut ke properti ShowValue untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" menyebabkan semua DataLabels.get_Item(i).getShowValue() menjadi equal dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Mewakili perilaku tampilan nama kategori label data pada diagram tertentu. True untuk menampilkan nama kategori pada label data di diagram. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection yang berisi label data, maka properti ini mendapatkan atau menetapkan nilai default properti ShowCategoryName untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai tersebut ke properti ShowCategoryName untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" menyebabkan semua DataLabels.get_Item(i).getShowCategoryName() menjadi equal dengan val).

**Mengembalikan:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Mewakili perilaku tampilan nama kategori label data pada diagram tertentu. True untuk menampilkan nama kategori pada label data di diagram. False untuk menyembunyikan. Baca/tulis boolean.

--------------------
Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau mengatur nilai default dari properti ShowCategoryName untuk label data baru di koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga mengatur nilai ini ke properti ShowCategoryName untuk semua label data di koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" menyebabkan semua DataLabels.get_Item(i).getShowCategoryName() sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Mengembalikan atau mengatur Boolean untuk menunjukkan perilaku tampilan nama seri pada label data di diagram. True untuk menampilkan nama seri. False untuk menyembunyikannya. Boolean baca/tulis.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau mengatur nilai default dari properti ShowSeriesName untuk label data baru di koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga mengatur nilai ini ke properti ShowSeriesName untuk semua label data di koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" menyebabkan semua DataLabels.get_Item(i).getShowSeriesName() sama dengan val).

**Mengembalikan:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Mengembalikan atau mengatur Boolean untuk menunjukkan perilaku tampilan nama seri pada label data di diagram. True untuk menampilkan nama seri. False untuk menyembunyikannya. Boolean baca/tulis.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau mengatur nilai default dari properti ShowSeriesName untuk label data baru di koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga mengatur nilai ini ke properti ShowSeriesName untuk semua label data di koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" menyebabkan semua DataLabels.get_Item(i).getShowSeriesName() sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Mewakili perilaku tampilan nilai persentase label data pada diagram tertentu. True menampilkan nilai persentase. False untuk menyembunyikannya. Boolean baca/tulis.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau mengatur nilai default dari properti ShowPercentage untuk label data baru di koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga mengatur nilai ini ke properti ShowPercentage untuk semua label data di koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" menyebabkan semua DataLabels.get_Item(i).getShowPercentage() sama dengan val).

**Mengembalikan:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Mewakili perilaku tampilan nilai persentase label data pada diagram tertentu. True menampilkan nilai persentase. False untuk menyembunyikannya. Boolean baca/tulis.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau mengatur nilai default dari properti ShowPercentage untuk label data baru di koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga mengatur nilai ini ke properti ShowPercentage untuk semua label data di koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" menyebabkan semua DataLabels.get_Item(i).getShowPercentage() sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Mewakili perilaku tampilan nilai ukuran gelembung label data pada diagram tertentu. True menampilkan nilai ukuran gelembung. False untuk menyembunyikannya. Boolean baca/tulis.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau mengatur nilai default dari properti ShowBubbleSize untuk label data baru di koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga mengatur nilai ini ke properti ShowBubbleSize untuk semua label data di koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" menyebabkan semua DataLabels.get_Item(i).getShowBubbleSize() sama dengan val).

**Mengembalikan:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Mewakili perilaku tampilan nilai ukuran gelembung label data pada diagram tertentu. True menampilkan nilai ukuran gelembung. False untuk menyembunyikannya. Boolean baca/tulis.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau mengatur nilai default dari properti ShowBubbleSize untuk label data baru di koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga mengatur nilai ini ke properti ShowBubbleSize untuk semua label data di koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" menyebabkan semua DataLabels.get_Item(i).getShowBubbleSize() sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Mewakili perilaku tampilan garis pemimpin label data pada diagram tertentu. True menampilkan garis pemimpin. False untuk menyembunyikannya. Boolean baca/tulis.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau mengatur nilai default dari properti ShowLeaderLines untuk label data baru di koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga mengatur nilai ini ke properti ShowLeaderLines untuk semua label data di koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" menyebabkan semua DataLabels.get_Item(i).getShowLeaderLines() sama dengan val).

**Mengembalikan:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Mewakili perilaku tampilan garis pemimpin label data pada diagram tertentu. True menampilkan garis pemimpin. False untuk menyembunyikannya. Boolean baca/tulis.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau mengatur nilai default dari properti ShowLeaderLines untuk label data baru di koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga mengatur nilai ini ke properti ShowLeaderLines untuk semua label data di koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" menyebabkan semua DataLabels.get_Item(i).getShowLeaderLines() sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Mewakili perilaku tampilan nilai sel label data pada diagram tertentu. True menampilkan nilai sel. False untuk menyembunyikannya. Boolean baca/tulis.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau mengatur nilai default dari properti ShowLabelValueFromCell untuk label data baru di koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga mengatur nilai ini ke properti ShowLabelValueFromCell untuk semua label data di koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" menyebabkan semua DataLabels.get_Item(i).getShowLabelValueFromCell() sama dengan val).

**Mengembalikan:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Mewakili perilaku tampilan nilai sel label data pada diagram tertentu. True menampilkan nilai sel. False untuk menyembunyikannya. Boolean baca/tulis.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau mengatur nilai default dari properti ShowLabelValueFromCell untuk label data baru di koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga mengatur nilai ini ke properti ShowLabelValueFromCell untuk semua label data di koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" menyebabkan semua DataLabels.get_Item(i).getShowLabelValueFromCell() sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Menentukan apakah label data pada diagram tertentu akan ditampilkan sebagai panggilan data atau sebagai label data.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau mengatur nilai default dari properti ShowLabelAsDataCallout untuk label data baru di koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga mengatur nilai ini ke properti ShowLabelAsDataCallout untuk semua label data di koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" menyebabkan semua DataLabels.get_Item(i).getShowLabelAsDataCallout() sama dengan val).

**Mengembalikan:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Menentukan apakah label data pada diagram tertentu akan ditampilkan sebagai panggilan data atau sebagai label data.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau mengatur nilai default dari properti ShowLabelAsDataCallout untuk label data baru di koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga mengatur nilai ini ke properti ShowLabelAsDataCallout untuk semua label data di koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" menyebabkan semua DataLabels.get_Item(i).getShowLabelAsDataCallout() sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Mengatur atau mengembalikan Variant yang mewakili pemisah yang digunakan untuk label data pada diagram. String baca/tulis.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau mengatur nilai default dari properti Separator untuk label data baru di koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga mengatur nilai ini ke properti Separator untuk semua label data di koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" menyebabkan semua DataLabels.get_Item(i).getSeparator() sama dengan val).

**Mengembalikan:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Mengatur atau mengembalikan Variant yang mewakili pemisah yang digunakan untuk label data pada diagram. String baca/tulis.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau mengatur nilai default dari properti Separator untuk label data baru di koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga mengatur nilai ini ke properti Separator untuk semua label data di koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" menyebabkan semua DataLabels.get_Item(i).getSeparator() sama dengan val).
**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Mengembalikan format teks chart. Baca-saja [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Mengembalikan:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Mengembalikan chart. Baca-saja [IChart](../../com.aspose.slides/ichart).

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart)