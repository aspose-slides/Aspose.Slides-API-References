---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili manajer yang menyimpan perilaku semua placeholder footer, tanggal-waktu, dan nomor halaman pada presentasi.
type: docs
url: /id/com.aspose.slides/ipresentationheaderfootermanager/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Mewakili manajer yang menyimpan perilaku semua placeholder footer, tanggal-waktu, dan nomor halaman pada presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Mengubah visibilitas semua placeholder header, termasuk master catatan, slide catatan, dan master handout. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Mengubah visibilitas semua placeholder footer, termasuk slide master, slide tata letak, dan slide. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Mengubah visibilitas semua placeholder nomor halaman, termasuk slide master, slide tata letak, dan slide. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Mengubah visibilitas semua placeholder tanggal-waktu, termasuk slide master, slide tata letak, dan slide. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Menetapkan teks ke semua placeholder header, termasuk master catatan, slide catatan, dan master handout. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Menetapkan teks ke semua placeholder footer, termasuk slide master, slide tata letak, dan slide. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Menetapkan teks ke semua placeholder tanggal-waktu, termasuk slide master, slide tata letak, dan slide. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Mengubah visibilitas placeholder footer, tanggal-waktu, dan nomor halaman untuk semua slide judul dan slide tata letak pertama. |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Mengubah visibilitas semua placeholder header, termasuk master catatan, slide catatan, dan master handout.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder header menjadi terlihat, jika tidak - menyembunyikannya. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Mengubah visibilitas semua placeholder footer, termasuk slide master, slide tata letak, dan slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder footer menjadi terlihat, jika tidak - menyembunyikannya. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Mengubah visibilitas semua placeholder nomor halaman, termasuk slide master, slide tata letak, dan slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder nomor halaman menjadi terlihat, jika tidak - menyembunyikannya. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Mengubah visibilitas semua placeholder tanggal-waktu, termasuk slide master, slide tata letak, dan slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder tanggal-waktu menjadi terlihat, jika tidak - menyembunyikannya. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Menetapkan teks ke semua placeholder header, termasuk master catatan, slide catatan, dan master handout.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan ditetapkan. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Menetapkan teks ke semua placeholder footer, termasuk slide master, slide tata letak, dan slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan ditetapkan. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Menetapkan teks ke semua placeholder tanggal-waktu, termasuk slide master, slide tata letak, dan slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan ditetapkan. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Mengubah visibilitas placeholder footer, tanggal-waktu, dan nomor halaman untuk semua slide judul dan slide tata letak pertama. Slide judul – slide yang berbasiskan slide tata letak pertama (tidak tergantung pada tipe tata letak pertama).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder menjadi terlihat, jika tidak - menyembunyikannya. |