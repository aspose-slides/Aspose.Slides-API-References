---
title: ILayoutSlideHeaderFooterManager
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili manajer yang menangani perilaku placeholder footer, tanggal-waktu, nomor halaman slide tata letak serta semua placeholder anak.
type: docs
url: /id/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Mewakili manajer yang menangani perilaku footer slide tata letak, placeholder tanggal-waktu, nomor halaman, dan semua placeholder anak. Placeholder anak berarti placeholder yang terdapat pada slide yang bergantung. Slide yang bergantung menggunakan dan tergantung pada slide tata letak.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Mengubah visibilitas placeholder footer slide tata letak dan semua placeholder footer anak. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Mengubah visibilitas placeholder nomor halaman slide tata letak dan semua placeholder nomor halaman anak. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Mengubah visibilitas placeholder tanggal-waktu slide tata letak dan semua placeholder tanggal-waktu anak. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Menetapkan teks ke placeholder footer slide tata letak dan semua placeholder footer anak. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Menetapkan teks ke placeholder tanggal-waktu slide tata letak dan semua placeholder tanggal-waktu anak. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Mengubah visibilitas placeholder footer slide tata letak dan semua placeholder footer anak. Placeholder anak berarti placeholder yang terdapat pada slide yang bergantung. Slide yang bergantung menggunakan dan tergantung pada slide master.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder footer terlihat, jika tidak - menyembunyikannya. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Mengubah visibilitas placeholder nomor halaman slide tata letak dan semua placeholder nomor halaman anak. Placeholder anak berarti placeholder yang terdapat pada slide yang bergantung. Slide yang bergantung menggunakan dan tergantung pada slide tata letak.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder nomor halaman terlihat, jika tidak - menyembunyikannya. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Mengubah visibilitas placeholder tanggal-waktu slide tata letak dan semua placeholder tanggal-waktu anak. Placeholder anak berarti placeholder yang terdapat pada slide yang bergantung. Slide yang bergantung menggunakan dan tergantung pada slide tata letak.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder tanggal-waktu terlihat, jika tidak - menyembunyikannya. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Menetapkan teks ke placeholder footer slide tata letak dan semua placeholder footer anak. Placeholder anak berarti placeholder yang terdapat pada slide yang bergantung. Slide yang bergantung menggunakan dan tergantung pada slide tata letak.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan ditetapkan. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Menetapkan teks ke placeholder tanggal-waktu slide tata letak dan semua placeholder tanggal-waktu anak. Placeholder anak berarti placeholder yang terdapat pada slide yang bergantung. Slide yang bergantung menggunakan dan tergantung pada slide tata letak.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan ditetapkan. |