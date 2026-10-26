---
title: IDataLabelFormat
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili opsi pemformatan untuk DataLabel.
type: docs
url: /id/com.aspose.slides/idatalabelformat/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

Mewakili opsi format untuk DataLabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
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
| [getShowSeriesName()](#getShowSeriesName--) | Mengembalikan atau mengatur Boolean untuk menunjukkan perilaku tampilan nama seri pada label data di diagram. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Mengembalikan atau mengatur Boolean untuk menunjukkan perilaku tampilan nama seri pada label data di diagram. |
| [getShowPercentage()](#getShowPercentage--) | Mewakili perilaku tampilan nilai persentase label data pada diagram tertentu. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Mewakili perilaku tampilan nilai persentase label data pada diagram tertentu. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Mewakili perilaku tampilan nilai ukuran gelembung label data pada diagram tertentu. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Mewakili perilaku tampilan nilai ukuran gelembung label data pada diagram tertentu. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Mewakili perilaku tampilan garis penghubung label data pada diagram tertentu. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Mewakili perilaku tampilan garis penghubung label data pada diagram tertentu. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Menentukan apakah label data pada diagram tertentu akan ditampilkan sebagai panggilan data atau sebagai label data. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Menentukan apakah label data pada diagram tertentu akan ditampilkan sebagai panggilan data atau sebagai label data. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Mewakili perilaku tampilan nilai sel label data pada diagram tertentu. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Mewakili perilaku tampilan nilai sel label data pada diagram tertentu. |
| [getSeparator()](#getSeparator--) | Mengatur atau mengembalikan Variant yang mewakili pemisah yang digunakan untuk label data pada diagram. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Mengatur atau mengembalikan Variant yang mewakili pemisah yang digunakan untuk label data pada diagram. |
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```


Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection, properti ini mengambil atau mengatur nilai default properti IsNumberFormatLinkedToSource untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai ini ke properti IsNumberFormatLinkedToSource untuk semua label data dalam koleksi DataLabelCollection (mis. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" menyebabkan semua DataLabels.get_Item(i).isNumberFormatLinkedToSource() sama dengan val).

**Mengembalikan:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```


Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection, properti ini mengambil atau mengatur nilai default properti IsNumberFormatLinkedToSource untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai ini ke properti IsNumberFormatLinkedToSource untuk semua label data dalam koleksi DataLabelCollection (mis. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" menyebabkan semua DataLabels.get_Item(i).isNumberFormatLinkedToSource() sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```


Mewakili string format untuk objek DataLabels. Baca/tulis String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection, properti ini mengambil atau mengatur nilai default properti NumberFormat untuk label data baru dalam koleksi DataLabelCollection. Ketika properti ini diatur dengan nilai, nilai tersebut juga diatur untuk properti NumberFormat semua label data dalam koleksi DataLabelCollection (mis. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" menyebabkan semua DataLabels.get_Item(i).getNumberFormat() menjadi val).

**Mengembalikan:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```


Mewakili string format untuk objek DataLabels. Baca/tulis String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection, properti ini mengambil atau mengatur nilai default properti NumberFormat untuk label data baru dalam koleksi DataLabelCollection. Ketika properti ini diatur dengan nilai, nilai tersebut juga diatur untuk properti NumberFormat semua label data dalam koleksi DataLabelCollection (mis. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" menyebabkan semua DataLabels.get_Item(i).getNumberFormat() menjadi val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Mewakili format label data. Baca-saja [IFormat](../../com.aspose.slides/iformat).

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection, properti ini mewakili format default untuk label data baru dalam koleksi DataLabelCollection.

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Mewakili posisi label data. Baca/tulis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection, properti ini mengambil atau mengatur nilai default properti Position untuk label data baru dalam koleksi DataLabelCollection. Mewakili posisi untuk objek DataLabel. Mengatur properti ini dengan nilai juga mengatur nilai ini ke properti Position semua label data dalam koleksi DataLabelCollection (mis. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" menyebabkan semua DataLabels.get_Item(i).getPosition() menjadi val).

**Mengembalikan:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Mewakili posisi label data. Baca/tulis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection, properti ini mengambil atau mengatur nilai default properti Position untuk label data baru dalam koleksi DataLabelCollection. Mewakili posisi untuk objek DataLabel. Mengatur properti ini dengan nilai juga mengatur nilai ini ke properti Position semua label data dalam koleksi DataLabelCollection (mis. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" menyebabkan semua DataLabels.get_Item(i).getPosition() menjadi val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```


Mewakili perilaku tampilan kunci legenda label data pada diagram tertentu. True jika kunci legenda label data terlihat. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection, properti ini mengambil atau mengatur nilai default properti ShowLegendKey untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai ini ke properti ShowLegendKey semua label data dalam koleksi DataLabelCollection (mis. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" menyebabkan semua DataLabels.get_Item(i).getShowLegendKey() sama dengan val).

**Mengembalikan:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```


Mewakili perilaku tampilan kunci legenda label data pada diagram tertentu. True jika kunci legenda label data terlihat. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection, properti ini mengambil atau mengatur nilai default properti ShowLegendKey untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai ini ke properti ShowLegendKey semua label data dalam koleksi DataLabelCollection (mis. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" menyebabkan semua DataLabels.get_Item(i).getShowLegendKey() sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```


Mewakili perilaku tampilan nilai persentase label data pada diagram tertentu. True menampilkan nilai persentase. False menyembunyikannya. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection, properti ini mengambil atau mengatur nilai default properti ShowValue untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai ini ke properti ShowValue semua label data dalam koleksi DataLabelCollection (mis. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" menyebabkan semua DataLabels.get_Item(i).getShowValue() sama dengan val).

**Mengembalikan:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```


Mewakili perilaku tampilan nilai persentase label data pada diagram tertentu. True menampilkan nilai persentase. False menyembunyikannya. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection, properti ini mengambil atau mengatur nilai default properti ShowValue untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai ini ke properti ShowValue semua label data dalam koleksi DataLabelCollection (mis. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" menyebabkan semua DataLabels.get_Item(i).getShowValue() sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```


Mewakili perilaku tampilan nama kategori label data pada diagram tertentu. True untuk menampilkan nama kategori pada label data di diagram. False untuk menyembunyikannya. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection, properti ini mengambil atau mengatur nilai default properti ShowCategoryName untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai ini ke properti ShowCategoryName semua label data dalam koleksi DataLabelCollection (mis. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" menyebabkan semua DataLabels.get_Item(i).getShowCategoryName() sama dengan val).

**Mengembalikan:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```


Mewakili perilaku tampilan nama kategori label data pada diagram tertentu. True untuk menampilkan nama kategori pada label data di diagram. False untuk menyembunyikannya. Baca/tulis boolean.

--------------------
Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mendapatkan atau mengatur nilai default properti ShowCategoryName untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai tersebut ke properti ShowCategoryName untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" menyebabkan semua DataLabels.get_Item(i).getShowCategoryName() bernilai val).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Mengembalikan atau mengatur Boolean untuk menunjukkan perilaku tampilan nama seri pada label data di diagram. True untuk menampilkan nama seri. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mendapatkan atau mengatur nilai default properti ShowSeriesName untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai tersebut ke properti ShowSeriesName untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" menyebabkan semua DataLabels.get_Item(i).getShowSeriesName() bernilai val).

**Mengembalikan:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Mengembalikan atau mengatur Boolean untuk menunjukkan perilaku tampilan nama seri pada label data di diagram. True untuk menampilkan nama seri. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mendapatkan atau mengatur nilai default properti ShowSeriesName untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai tersebut ke properti ShowSeriesName untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" menyebabkan semua DataLabels.get_Item(i).getShowSeriesName() bernilai val).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Mewakili perilaku tampilan nilai persentase label data pada diagram tertentu. True menampilkan nilai persentase. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mendapatkan atau mengatur nilai default properti ShowPercentage untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai tersebut ke properti ShowPercentage untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" menyebabkan semua DataLabels.get_Item(i).getShowPercentage() bernilai val).

**Mengembalikan:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Mewakili perilaku tampilan nilai persentase label data pada diagram tertentu. True menampilkan nilai persentase. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mendapatkan atau mengatur nilai default properti ShowPercentage untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai tersebut ke properti ShowPercentage untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" menyebabkan semua DataLabels.get_Item(i).getShowPercentage() bernilai val).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Mewakili perilaku tampilan nilai ukuran gelembung label data pada diagram tertentu. True menampilkan nilai ukuran gelembung. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mendapatkan atau mengatur nilai default properti ShowBubbleSize untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai tersebut ke properti ShowBubbleSize untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" menyebabkan semua DataLabels.get_Item(i).getShowBubbleSize() bernilai val).

**Mengembalikan:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Mewakili perilaku tampilan nilai ukuran gelembung label data pada diagram tertentu. True menampilkan nilai ukuran gelembung. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mendapatkan atau mengatur nilai default properti ShowBubbleSize untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai tersebut ke properti ShowBubbleSize untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" menyebabkan semua DataLabels.get_Item(i).getShowBubbleSize() bernilai val).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Mewakili perilaku tampilan garis pemimpin label data pada diagram tertentu. True menampilkan garis pemimpin. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mendapatkan atau mengatur nilai default properti ShowLeaderLines untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai tersebut ke properti ShowLeaderLines untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" menyebabkan semua DataLabels.get_Item(i).getShowLeaderLines() bernilai val).

**Mengembalikan:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Mewakili perilaku tampilan garis pemimpin label data pada diagram tertentu. True menampilkan garis pemimpin. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mendapatkan atau mengatur nilai default properti ShowLeaderLines untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai tersebut ke properti ShowLeaderLines untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" menyebabkan semua DataLabels.get_Item(i).getShowLeaderLines() bernilai val).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Menentukan apakah label data pada diagram tertentu akan ditampilkan sebagai panggilan data atau sebagai label data.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mendapatkan atau mengatur nilai default properti ShowLabelAsDataCallout untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai tersebut ke properti ShowLabelAsDataCallout untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" menyebabkan semua DataLabels.get_Item(i).getShowLabelAsDataCallout() bernilai val).

**Mengembalikan:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Menentukan apakah label data pada diagram tertentu akan ditampilkan sebagai panggilan data atau sebagai label data.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mendapatkan atau mengatur nilai default properti ShowLabelAsDataCallout untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai tersebut ke properti ShowLabelAsDataCallout untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" menyebabkan semua DataLabels.get_Item(i).getShowLabelAsDataCallout() bernilai val).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Mewakili perilaku tampilan nilai sel label data pada diagram tertentu. True menampilkan nilai sel. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mendapatkan atau mengatur nilai default properti ShowLabelValueFromCell untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai tersebut ke properti ShowLabelValueFromCell untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" menyebabkan semua DataLabels.get_Item(i).getShowLabelValueFromCell() bernilai val).

**Mengembalikan:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Mewakili perilaku tampilan nilai sel label data pada diagram tertentu. True menampilkan nilai sel. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mendapatkan atau mengatur nilai default properti ShowLabelValueFromCell untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai tersebut ke properti ShowLabelValueFromCell untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" menyebabkan semua DataLabels.get_Item(i).getShowLabelValueFromCell() bernilai val).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Mengatur atau mengembalikan Variant yang mewakili pemisah yang digunakan untuk label data pada diagram. Baca/tulis String.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mendapatkan atau mengatur nilai default properti Separator untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai tersebut ke properti Separator untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" menyebabkan semua DataLabels.get_Item(i).getSeparator() bernilai val).

**Mengembalikan:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Mengatur atau mengembalikan Variant yang mewakili pemisah yang digunakan untuk label data pada diagram. Baca/tulis String.

--------------------

Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mendapatkan atau mengatur nilai default properti Separator untuk label data baru dalam koleksi DataLabelCollection. Mengatur properti ini dengan nilai juga mengatur nilai tersebut ke properti Separator untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" menyebabkan semua DataLabels.get_Item(i).getSeparator() bernilai val).
**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |