---
title: IDataLabelFormat
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili opsi pemformatan untuk DataLabel.
type: docs
url: /id/com.aspose.slides/idatalabelformat/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

Mewakili opsi pemformatan untuk DataLabel.
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
| [getShowLegendKey()](#getShowLegendKey--) | Mewakili perilaku tampilan kunci legenda label data pada diagram yang ditentukan. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Mewakili perilaku tampilan kunci legenda label data pada diagram yang ditentukan. |
| [getShowValue()](#getShowValue--) | Mewakili perilaku tampilan nilai persentase label data pada diagram yang ditentukan. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Mewakili perilaku tampilan nilai persentase label data pada diagram yang ditentukan. |
| [getShowCategoryName()](#getShowCategoryName--) | Mewakili perilaku tampilan nama kategori label data pada diagram yang ditentukan. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Mewakili perilaku tampilan nama kategori label data pada diagram yang ditentukan. |
| [getShowSeriesName()](#getShowSeriesName--) | Mengembalikan atau menetapkan Boolean untuk menunjukkan perilaku tampilan nama seri pada label data di sebuah diagram. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Mengembalikan atau menetapkan Boolean untuk menunjukkan perilaku tampilan nama seri pada label data di sebuah diagram. |
| [getShowPercentage()](#getShowPercentage--) | Mewakili perilaku tampilan nilai persentase label data pada diagram yang ditentukan. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Mewakili perilaku tampilan nilai persentase label data pada diagram yang ditentukan. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Mewakili perilaku tampilan nilai ukuran gelembung label data pada diagram yang ditentukan. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Mewakili perilaku tampilan nilai ukuran gelembung label data pada diagram yang ditentukan. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Mewakili perilaku tampilan garis pemimpin label data pada diagram yang ditentukan. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Mewakili perilaku tampilan garis pemimpin label data pada diagram yang ditentukan. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Menentukan apakah label data pada diagram yang ditentukan akan ditampilkan sebagai penjelasan data atau sebagai label data. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Menentukan apakah label data pada diagram yang ditentukan akan ditampilkan sebagai penjelasan data atau sebagai label data. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Mewakili perilaku tampilan nilai sel label data pada diagram yang ditentukan. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Mewakili perilaku tampilan nilai sel label data pada diagram yang ditentukan. |
| [getSeparator()](#getSeparator--) | Menetapkan atau mengembalikan Variant yang mewakili pemisah yang digunakan untuk label data pada sebuah diagram. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Menetapkan atau mengembalikan Variant yang mewakili pemisah yang digunakan untuk label data pada sebuah diagram. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```


Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau menetapkan nilai default properti IsNumberFormatLinkedToSource untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti IsNumberFormatLinkedToSource untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" menyebabkan semua DataLabels.get_Item(i).isNumberFormatLinkedToSource() menjadi sama dengan val).

**Mengembalikan:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```


Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau menetapkan nilai default properti IsNumberFormatLinkedToSource untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti IsNumberFormatLinkedToSource untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" menyebabkan semua DataLabels.get_Item(i).isNumberFormatLinkedToSource() menjadi sama dengan val).

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

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau menetapkan nilai default properti NumberFormat untuk label data baru dalam koleksi DataLabelCollection. Ketika properti ini diatur dengan nilai, nilai tersebut juga diatur untuk properti NumberFormat semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" menyebabkan semua DataLabels.get_Item(i).getNumberFormat() menjadi sama dengan val).

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

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data, maka properti ini mengambil atau menetapkan nilai default properti NumberFormat untuk label data baru dalam koleksi DataLabelCollection. Ketika properti ini diatur dengan nilai, nilai tersebut juga diatur untuk properti NumberFormat semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" menyebabkan semua DataLabels.get_Item(i).getNumberFormat() menjadi sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Mewakili format label data. Hanya-baca [IFormat](../../com.aspose.slides/iformat).

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mewakili format default untuk label data baru dalam koleksi DataLabelCollection.

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Mewakili posisi label data. Baca/tulis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti Position untuk label data baru dalam koleksi DataLabelCollection. Mewakili posisi untuk objek DataLabel. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti Position untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setPosition(val)" menyebabkan semua DataLabels.get_Item(i).getPosition() menjadi sama dengan val).

**Mengembalikan:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Mewakili posisi label data. Baca/tulis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti Position untuk label data baru dalam koleksi DataLabelCollection. Mewakili posisi untuk objek DataLabel. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti Position untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setPosition(val)" menyebabkan semua DataLabels.get_Item(i).getPosition() menjadi sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```


Mewakili perilaku tampilan kunci legenda label data pada diagram yang ditentukan. True jika kunci legenda label data terlihat. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowLegendKey untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowLegendKey untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" menyebabkan semua DataLabels.get_Item(i).getShowLegendKey() menjadi sama dengan val).

**Mengembalikan:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```


Mewakili perilaku tampilan kunci legenda label data pada diagram yang ditentukan. True jika kunci legenda label data terlihat. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowLegendKey untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowLegendKey untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" menyebabkan semua DataLabels.get_Item(i).getShowLegendKey() menjadi sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```


Mewakili perilaku tampilan nilai persentase label data pada diagram yang ditentukan. True menampilkan nilai persentase. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowValue untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowValue untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" menyebabkan semua DataLabels.get_Item(i).getShowValue() menjadi sama dengan val).

**Mengembalikan:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```


Mewakili perilaku tampilan nilai persentase label data pada diagram yang ditentukan. True menampilkan nilai persentase. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowValue untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowValue untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" menyebabkan semua DataLabels.get_Item(i).getShowValue() menjadi sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```


Mewakili perilaku tampilan nama kategori label data pada diagram yang ditentukan. True untuk menampilkan nama kategori pada label data di sebuah diagram. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowCategoryName untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowCategoryName untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" menyebabkan semua DataLabels.get_Item(i).getShowCategoryName() menjadi sama dengan val).

**Mengembalikan:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```


Mewakili perilaku tampilan nama kategori label data pada diagram yang ditentukan. True untuk menampilkan nama kategori pada label data di sebuah diagram. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowCategoryName untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowCategoryName untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" menyebabkan semua DataLabels.get_Item(i).getShowCategoryName() menjadi sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```


Mengembalikan atau menetapkan Boolean untuk menunjukkan perilaku tampilan nama seri pada label data di sebuah diagram. True untuk menampilkan nama seri. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowSeriesName untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowSeriesName untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" menyebabkan semua DataLabels.get_Item(i).getShowSeriesName() menjadi sama dengan val).

**Mengembalikan:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```


Mengembalikan atau menetapkan Boolean untuk menunjukkan perilaku tampilan nama seri pada label data di sebuah diagram. True untuk menampilkan nama seri. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowSeriesName untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowSeriesName untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" menyebabkan semua DataLabels.get_Item(i).getShowSeriesName() menjadi sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```


Mewakili perilaku tampilan nilai persentase label data pada diagram yang ditentukan. True menampilkan nilai persentase. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowPercentage untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowPercentage untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" menyebabkan semua DataLabels.get_Item(i).getShowPercentage() menjadi sama dengan val).

**Mengembalikan:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```


Mewakili perilaku tampilan nilai persentase label data pada diagram yang ditentukan. True menampilkan nilai persentase. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowPercentage untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowPercentage untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" menyebabkan semua DataLabels.get_Item(i).getShowPercentage() menjadi sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```


Mewakili perilaku tampilan nilai ukuran gelembung label data pada diagram yang ditentukan. True menampilkan nilai ukuran gelembung. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowBubbleSize untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowBubbleSize untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" menyebabkan semua DataLabels.get_Item(i).getShowBubbleSize() menjadi sama dengan val).

**Mengembalikan:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```


Mewakili perilaku tampilan nilai ukuran gelembung label data pada diagram yang ditentukan. True menampilkan nilai ukuran gelembung. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowBubbleSize untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowBubbleSize untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" menyebabkan semua DataLabels.get_Item(i).getShowBubbleSize() menjadi sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```


Mewakili perilaku tampilan garis pemimpin label data pada diagram yang ditentukan. True menampilkan garis pemimpin. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowLeaderLines untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowLeaderLines untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" menyebabkan semua DataLabels.get_Item(i).getShowLeaderLines() menjadi sama dengan val).

**Mengembalikan:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```


Mewakili perilaku tampilan garis pemimpin label data pada diagram yang ditentukan. True menampilkan garis pemimpin. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowLeaderLines untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowLeaderLines untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" menyebabkan semua DataLabels.get_Item(i).getShowLeaderLines() menjadi sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```


Menentukan apakah label data pada diagram yang ditentukan akan ditampilkan sebagai penjelasan data atau sebagai label data.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowLabelAsDataCallout untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowLabelAsDataCallout untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" menyebabkan semua DataLabels.get_Item(i).getShowLabelAsDataCallout() menjadi sama dengan val).

**Mengembalikan:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```


Menentukan apakah label data pada diagram yang ditentukan akan ditampilkan sebagai penjelasan data atau sebagai label data.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowLabelAsDataCallout untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowLabelAsDataCallout untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" menyebabkan semua DataLabels.get_Item(i).getShowLabelAsDataCallout() menjadi sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```


Mewakili perilaku tampilan nilai sel label data pada diagram yang ditentukan. True menampilkan nilai sel. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowLabelValueFromCell untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowLabelValueFromCell untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" menyebabkan semua DataLabels.get_Item(i).getShowLabelValueFromCell() menjadi sama dengan val).

**Mengembalikan:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```


Mewakili perilaku tampilan nilai sel label data pada diagram yang ditentukan. True menampilkan nilai sel. False untuk menyembunyikan. Baca/tulis boolean.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti ShowLabelValueFromCell untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti ShowLabelValueFromCell untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" menyebabkan semua DataLabels.get_Item(i).getShowLabelValueFromCell() menjadi sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```


Menetapkan atau mengembalikan Variant yang mewakili pemisah yang digunakan untuk label data pada sebuah diagram. Baca/tulis String.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti Separator untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti Separator untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" menyebabkan semua DataLabels.get_Item(i).getSeparator() menjadi sama dengan val).

**Mengembalikan:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```


Menetapkan atau mengembalikan Variant yang mewakili pemisah yang digunakan untuk label data pada sebuah diagram. Baca/tulis String.

--------------------

Jika induk objek DataLabelFormat ini adalah koleksi DataLabelCollection berisi label data maka properti ini mengambil atau menetapkan nilai default properti Separator untuk label data baru dalam koleksi DataLabelCollection. Menetapkan properti ini dengan nilai juga menetapkan nilai ini ke properti Separator untuk semua label data dalam koleksi DataLabelCollection (misalnya "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" menyebabkan semua DataLabels.get_Item(i).getSeparator() menjadi sama dengan val).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |