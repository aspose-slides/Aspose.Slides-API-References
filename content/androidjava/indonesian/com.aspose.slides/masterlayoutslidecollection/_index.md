---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili kumpulan semua slide tata letak dari master slide yang didefinisikan.
type: docs
url: /id/com.aspose.slides/masterlayoutslidecollection/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Mewakili kumpulan semua slide tata letak dari master slide yang didefinisikan. Memperluas kelas LayoutSlideCollection dengan metode untuk menambah/menyisipkan/menghapus/mengkloning/mengatur ulang slide tata letak dalam konteks koleksi individu slide tata letak master.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Menambahkan salinan slide tata letak tertentu ke akhir koleksi. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Menyisipkan salinan slide tata letak tertentu ke posisi yang ditentukan dalam koleksi. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Menambahkan slide tata letak baru ke akhir koleksi. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Menyisipkan slide tata letak baru ke posisi yang ditentukan dalam koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Memindahkan slide tata letak dari koleksi ke posisi yang ditentukan. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Menambahkan salinan slide tata letak tertentu ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide untuk digandakan. |

--------------------

1) Tata letak baru akan terhubung dengan master slide induk untuk koleksi slide tata letak ini. Jadi ini merupakan analogi salin/tempel dengan opsi "Use Destination Theme" di PowerPoint. 2) Analogi dari metode ini adalah metode [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) yang diakses melalui properti ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide yang ditambahkan.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Menyisipkan salinan slide tata letak tertentu ke posisi yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks slide baru. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide untuk digandakan. |

--------------------

Tata letak baru akan terhubung dengan master slide induk untuk koleksi slide tata letak ini. Jadi ini merupakan analogi salin/tempel dengan opsi "Use Destination Theme" di PowerPoint.

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide yang disisipkan.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Menambahkan slide tata letak baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layoutType | byte | Tipe tata letak untuk tata letak baru. Tipe tata letak yang didukung: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Tipe tata letak lain tidak didukung saat ini: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nama untuk tata letak baru. Jika nama yang diberikan sudah digunakan, ArgumentException akan dilemparkan. Jika parameter null diberikan, maka nama akan dihasilkan secara otomatis sesuai dengan tipe tata letak yang diberikan (misalnya "Title Slide" atau "1_Title Slide", "2_..", dll.). |

--------------------

1) Tata letak yang ditambahkan untuk nilai SlideLayoutType.Custom dari layoutType tidak berisi placeholder atau shape. 2) Analogi dari metode ini adalah metode [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) yang diakses melalui properti ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide yang ditambahkan.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Menyisipkan slide tata letak baru ke posisi yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks slide baru. |
| layoutType | byte | Tipe tata letak untuk tata letak baru. Tipe tata letak yang didukung: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Tipe tata letak lain tidak didukung saat ini: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nama untuk tata letak baru. Jika nama yang diberikan sudah digunakan, ArgumentException akan dilemparkan. Jika parameter null diberikan, maka nama akan dihasilkan secara otomatis sesuai dengan tipe tata letak yang diberikan (misalnya "Title Slide" atau "1_Title Slide", "2_..", dll.). |

--------------------

Tata letak yang disisipkan untuk nilai SlideLayoutType.Custom dari layoutType tidak berisi placeholder atau shape.

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide yang disisipkan.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus elemen pada indeks yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus. |

--------------------

1) Untuk menghindari lemparan PptxEditException, periksa properti HasDependingSlides pada tata letak terlebih dahulu. 2) Anda juga dapat menggunakan metode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) untuk menyederhanakan kode.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Memindahkan slide tata letak dari koleksi ke posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks target. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide yang akan dipindahkan. |