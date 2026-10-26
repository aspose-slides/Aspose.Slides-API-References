---
title: IMasterSlideHeaderFooterManager
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili manajer yang memegang perilaku placeholder footer slide master, tanggal-waktu, nomor halaman, dan semua placeholder anak.
type: docs
url: /id/com.aspose.slides/imasterslideheaderfootermanager/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Mewakili manajer yang memegang perilaku placeholder footer slide master, placeholder tanggal-waktu, placeholder nomor halaman, dan semua placeholder anak. Placeholder anak berarti placeholder yang terdapat pada slide tata letak bergantung dan slide bergantung. Slide tata letak bergantung dan slide bergantung menggunakan dan bergantung pada slide master.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Changes master slide footer placeholder and all child footer placeholders visibility. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Changes master slide page number placeholder and all child page number placeholders visibility. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Changes master slide date-time placeholder and all child date-time placeholders visibility. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Sets text to master slide footer placeholder and all child footer placeholders. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Sets text to master slide date-time placeholder and all child date-time placeholders. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Mengubah visibilitas placeholder footer slide master dan semua placeholder footer anak. Placeholder anak berarti placeholder yang terdapat pada slide tata letak bergantung dan slide bergantung. Slide tata letak bergantung dan slide bergantung menggunakan dan bergantung pada slide master.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder footer terlihat, jika tidak - menyembunyikannya. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Mengubah visibilitas placeholder nomor halaman slide master dan semua placeholder nomor halaman anak. Placeholder anak berarti placeholder yang terdapat pada slide tata letak bergantung dan slide bergantung. Slide tata letak bergantung dan slide bergantung menggunakan dan bergantung pada slide master.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder nomor halaman terlihat, jika tidak - menyembunyikannya. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Mengubah visibilitas placeholder tanggal-waktu slide master dan semua placeholder tanggal-waktu anak. Placeholder anak berarti placeholder yang terdapat pada slide tata letak bergantung dan slide bergantung. Slide tata letak bergantung dan slide bergantung menggunakan dan bergantung pada slide master.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder tanggal-waktu terlihat, jika tidak - menyembunyikannya. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Menetapkan teks ke placeholder footer slide master dan semua placeholder footer anak. Placeholder anak berarti placeholder yang terdapat pada slide tata letak bergantung dan slide bergantung. Slide tata letak bergantung dan slide bergantung menggunakan dan bergantung pada slide master.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan disetel. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Menetapkan teks ke placeholder tanggal-waktu slide master dan semua placeholder tanggal-waktu anak. Placeholder anak berarti placeholder yang terdapat pada slide tata letak bergantung dan slide bergantung. Slide tata letak bergantung dan slide bergantung menggunakan dan bergantung pada slide master.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan disetel. |