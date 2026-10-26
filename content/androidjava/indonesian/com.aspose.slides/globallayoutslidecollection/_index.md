---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili kumpulan semua slide tata letak dalam presentasi.
type: docs
url: /id/com.aspose.slides/globallayoutslidecollection/
---
**Warisan:**  
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Semua Antarmuka yang Diimplementasikan:**  
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)  
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Mewakili kumpulan semua slide tata letak dalam presentasi. Memperluas kelas LayoutSlideCollection dengan metode untuk menambahkan/mengkloning slide tata letak dalam konteks penggabungan koleksi individual slide tata letak master.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Menambahkan salinan slide tata letak yang ditentukan ke presentasi. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Menambahkan salinan slide tata letak yang ditentukan ke presentasi. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Menambahkan slide tata letak baru ke presentasi. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Menambahkan salinan slide tata letak yang ditentukan ke presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide yang akan dikloning. |

--------------------

Saat mengkloning tata letak antara presentasi yang berbeda, master tata letak dapat dikloning juga untuk mempertahankan format sumber. Registri internal digunakan untuk melacak master yang dikloning secara otomatis agar tidak membuat beberapa klon dari slide master yang sama. Pengklonan manual slide master tidak akan dicegah maupun terdaftar.

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide yang ditambahkan.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Menambahkan salinan slide tata letak yang ditentukan ke presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide yang akan dikloning. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide master untuk tata letak baru. |

--------------------

1) Tata letak baru akan terhubung dengan master yang ditentukan pada presentasi tujuan. Jadi ini merupakan analog dari salin/tempel dengan opsi “Use Destination Theme” di PowerPoint. 2) Analogi metode ini adalah metode [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) yang diakses dengan properti ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).  

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide yang ditambahkan.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Menambahkan slide tata letak baru ke presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide master untuk tata letak baru. |
| layoutType | byte | Jenis tata letak untuk tata letak baru. Jenis tata letak yang didukung: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Jenis tata letak lain tidak didukung saat ini: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nama untuk tata letak baru. Jika nama yang diberikan sudah digunakan, ArgumentException akan dilemparkan. Jika parameter null diberikan, nama akan dihasilkan secara otomatis sesuai dengan jenis tata letak yang diberikan (misalnya “Title Slide” atau “1_Title Slide”, “2_..”, dll.). |

--------------------

1) Tata letak yang ditambahkan untuk nilai SlideLayoutType.Custom pada layoutType tidak berisi placeholder maupun shape. 2) Analogi metode ini adalah metode [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) yang diakses dengan properti ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).  

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide yang ditambahkan.