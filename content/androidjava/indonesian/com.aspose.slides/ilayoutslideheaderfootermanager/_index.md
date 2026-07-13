---
title: ILayoutSlideHeaderFooterManager
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili manajer yang menyimpan perilaku placeholder footer slide tata letak, tanggal-waktu, nomor halaman, dan semua placeholder anak.
type: docs
url: /id/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Mewakili manajer yang menyimpan perilaku placeholder footer slide tata letak, placeholder tanggal-waktu, placeholder nomor halaman, dan semua placeholder anak. Placeholder anak berarti placeholder yang berada pada slide yang bergantung. Slide yang bergantung menggunakan dan bergantung pada slide tata letak.
## Metode

| Method | Description |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Mengubah visibilitas placeholder footer slide tata letak dan semua placeholder footer anak. Placeholder anak berarti placeholder yang berada pada slide yang bergantung. Slide yang bergantung menggunakan dan bergantung pada slide master. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Mengubah visibilitas placeholder nomor halaman slide tata letak dan semua placeholder nomor halaman anak. Placeholder anak berarti placeholder yang berada pada slide yang bergantung. Slide yang bergantung menggunakan dan bergantung pada slide tata letak. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Mengubah visibilitas placeholder tanggal-waktu slide tata letak dan semua placeholder tanggal-waktu anak. Placeholder anak berarti placeholder yang berada pada slide yang bergantung. Slide yang bergantung menggunakan dan bergantung pada slide tata letak. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Menetapkan teks ke placeholder footer slide tata letak dan semua placeholder footer anak. Placeholder anak berarti placeholder yang berada pada slide yang bergantung. Slide yang bergantung menggunakan dan bergantung pada slide tata letak. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Menetapkan teks ke placeholder tanggal-waktu slide tata letak dan semua placeholder tanggal-waktu anak. Placeholder anak berarti placeholder yang berada pada slide yang bergantung. Slide yang bergantung menggunakan dan bergantung pada slide tata letak. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Mengubah visibilitas placeholder footer slide tata letak dan semua placeholder footer anak. Placeholder anak berarti placeholder yang berada pada slide yang bergantung. Slide yang bergantung menggunakan dan bergantung pada slide master.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder footer terlihat, jika tidak - menyembunyikannya. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Mengubah visibilitas placeholder nomor halaman slide tata letak dan semua placeholder nomor halaman anak. Placeholder anak berarti placeholder yang berada pada slide yang bergantung. Slide yang bergantung menggunakan dan bergantung pada slide tata letak.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder nomor halaman terlihat, jika tidak - menyembunyikannya. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Mengubah visibilitas placeholder tanggal-waktu slide tata letak dan semua placeholder tanggal-waktu anak. Placeholder anak berarti placeholder yang berada pada slide yang bergantung. Slide yang bergantung menggunakan dan bergantung pada slide tata letak.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder tanggal-waktu terlihat, jika tidak - menyembunyikannya. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Menetapkan teks ke placeholder footer slide tata letak dan semua placeholder footer anak. Placeholder anak berarti placeholder yang berada pada slide yang bergantung. Slide yang bergantung menggunakan dan bergantung pada slide tata letak.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan ditetapkan. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Menetapkan teks ke placeholder tanggal-waktu slide tata letak dan semua placeholder tanggal-waktu anak. Placeholder anak berarti placeholder yang berada pada slide yang bergantung. Slide yang bergantung menggunakan dan bergantung pada slide tata letak.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan ditetapkan. |