---
title: IPresentationHeaderFooterManager
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili manajer yang menampung perilaku semua placeholder footer, tanggal-waktu, dan nomor halaman pada presentasi.
type: docs
url: /id/com.aspose.slides/ipresentationheaderfootermanager/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Mewakili manajer yang menampung perilaku semua placeholder footer, tanggal-waktu, dan nomor halaman pada presentasi.

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
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Mengubah visibilitas placeholder footer, tanggal-waktu, dan nomor halaman untuk semua slide judul dan untuk slide tata letak pertama. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Mengubah visibilitas semua placeholder header, termasuk master catatan, slide catatan, dan master handout.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder header terlihat, sebaliknya - menyembunyikannya. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Mengubah visibilitas semua placeholder footer, termasuk slide master, slide tata letak, dan slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder footer terlihat, sebaliknya - menyembunyikannya. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Mengubah visibilitas semua placeholder nomor halaman, termasuk slide master, slide tata letak, dan slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder nomor halaman terlihat, sebaliknya - menyembunyikannya. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Mengubah visibilitas semua placeholder tanggal-waktu, termasuk slide master, slide tata letak, dan slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder tanggal-waktu terlihat, sebaliknya - menyembunyikannya. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Menetapkan teks ke semua placeholder header, termasuk master catatan, slide catatan, dan master handout.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan diatur. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Menetapkan teks ke semua placeholder footer, termasuk slide master, slide tata letak, dan slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan diatur. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Menetapkan teks ke semua placeholder tanggal-waktu, termasuk slide master, slide tata letak, dan slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan diatur. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Mengubah visibilitas placeholder footer, tanggal-waktu, dan nomor halaman untuk semua slide judul dan untuk slide tata letak pertama. Slide judul \\u2013 slide yang berbasis pada slide tata letak pertama (tanpa memandang jenis tata letak pertama ini).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder terlihat, sebaliknya - menyembunyikannya. |