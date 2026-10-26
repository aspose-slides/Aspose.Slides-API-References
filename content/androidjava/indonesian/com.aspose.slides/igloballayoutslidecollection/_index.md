---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi semua slide tata letak dalam presentasi.
type: docs
url: /id/com.aspose.slides/igloballayoutslidecollection/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Mewakili koleksi semua slide tata letak dalam presentasi. Memperluas antarmuka ILayoutSlideCollection dengan metode untuk menambahkan/menggandakan slide tata letak dalam konteks penggabungan koleksi individu slide tata letak master.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Menambahkan salinan slide tata letak tertentu ke presentasi. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Menambahkan salinan slide tata letak tertentu ke presentasi. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Menambahkan slide tata letak baru ke presentasi. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Menambahkan salinan slide tata letak tertentu ke presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide untuk digandakan. |

--------------------

Saat menggandakan tata letak antara presentasi yang berbeda, master tata letak juga dapat digandakan untuk mempertahankan format sumber. Registri internal digunakan untuk melacak master yang digandakan secara otomatis guna mencegah pembuatan duplikat master slide yang sama. Penggandaan manual master slide tidak akan dicegah maupun terdaftar.

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide yang ditambahkan.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Menambahkan salinan slide tata letak tertentu ke presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide untuk digandakan. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide untuk tata letak baru. |

--------------------

Tata letak baru akan terhubung dengan master yang ditentukan dalam presentasi tujuan. Jadi ini merupakan analogi copy/paste dengan opsi “Use Destination Theme” di PowerPoint.

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide yang ditambahkan.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Menambahkan slide tata letak baru ke presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide untuk tata letak baru. |
| layoutType | byte | Tipe tata letak untuk tata letak baru. Tipe tata letak yang didukung: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Tipe tata letak lain tidak didukung saat ini: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nama untuk tata letak baru. Jika nama yang diberikan sudah digunakan, ArgumentException akan dilemparkan. Jika parameter null diberikan, nama akan dihasilkan secara otomatis berdasarkan tipe tata letak yang diberikan (misalnya “Title Slide” atau “1_Title Slide”, “2_..”, dll.). |

--------------------

1) Tata letak ditambahkan untuk nilai SlideLayoutType.Custom dari layoutType yang tidak mengandung placeholder maupun bentuk. 2) Analogi metode ini adalah metode [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) yang diakses dengan properti ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide yang ditambahkan.