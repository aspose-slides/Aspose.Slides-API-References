---
title: SlideCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili kumpulan slide.
type: docs
url: /id/com.aspose.slides/slidecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Mewakili koleksi slide.
## Metode

| Method | Description |
| --- | --- |
| [size()](#size--) | Mengambil jumlah elemen yang sebenarnya terkandung dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mengambil elemen pada indeks yang ditentukan. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Menambahkan salinan slide yang ditentukan ke akhir koleksi. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Menambahkan salinan slide yang ditentukan ke akhir bagian yang ditentukan. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Menambahkan slide kosong baru ke akhir koleksi. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Menambahkan salinan slide yang ditentukan ke akhir koleksi. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Menambahkan salinan slide sumber yang ditentukan ke akhir koleksi. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Menyisipkan salinan slide sumber yang ditentukan ke posisi yang ditentukan dalam koleksi. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Menghapus kemunculan pertama objek tertentu dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [toArray()](#toArray--) | Membuat dan mengembalikan array dengan semua slide di dalamnya. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Membuat dan mengembalikan array dengan semua slide dari rentang yang ditentukan. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Memindahkan slide dari koleksi ke posisi yang ditentukan. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Moves slides from the collection to the specified position. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Mengembalikan indeks slide yang ditentukan dalam koleksi. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi dengan mempertimbangkan opsi impor PDF. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
### size() {#size--}
```
public final int size()
```

Mengambil jumlah elemen yang sebenarnya terkandung dalam koleksi. Baca-saja int.

**Mengembalikan:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Mengambil elemen pada indeks yang ditentukan. Baca-saja [Slide](../../com.aspose.slides/slide).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide)
### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

Menambahkan salinan slide yang ditentukan ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide yang akan diklon.

--------------------

Saat menyalin (clone) slide antara presentasi yang berbeda, master slide dapat juga disalin. Registri internal digunakan untuk melacak master yang disalin secara otomatis guna mencegah pembuatan beberapa salinan master slide yang sama. Penyalinan manual master slide tidak akan dicegah maupun didaftarkan. Jika Anda memerlukan kontrol lebih besar atas proses penyalinan, gunakan \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) atau \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) untuk menyalin slide, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) atau [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) untuk menyalin tata letak dan [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) untuk menyalin master. 

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Slide baru.
### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

Menambahkan salinan slide yang ditentukan ke akhir bagian yang ditentukan.

--------------------

> ```
> IPresentation presentation = new Presentation();
>  try
>  {
>      presentation.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
>      presentation.getSections().addSection("Section 1", presentation.getSlides().get_Item(0));
>      
>      ISection section2 = presentation.getSections().appendEmptySection("Section 2");
>      presentation.getSlides().addClone(presentation.getSlides().get_Item(0), section2);
>      
>      // Sekarang bagian kedua berisi salinan slide pertama.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide yang akan diklon. |
| section | [ISection](../../com.aspose.slides/isection) | Bagian untuk slide baru. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Slide baru.
### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Instansiasi kelas Presentation yang mewakili file presentasi
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Klon slide yang diinginkan ke akhir koleksi slide dalam presentasi yang sama
>      ISlideCollection slds = pres.getSlides();
>      // Klon slide yang diinginkan ke indeks yang ditentukan dalam presentasi yang sama
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Tuliskan presentasi yang dimodifikasi ke disk
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Instansiasi kelas Presentation untuk memuat file presentasi sumber
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Instansiasi kelas Presentation untuk PPTX tujuan (di mana slide akan diklon)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Tuliskan presentasi tujuan ke disk
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks slide baru. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide yang akan diklon.

--------------------

Saat menyalin (clone) slide antara presentasi yang berbeda, master slide dapat juga disalin. Registri internal digunakan untuk melacak master yang disalin secara otomatis guna mencegah pembuatan beberapa salinan master slide yang sama. Penyalinan manual master slide tidak akan dicegah maupun didaftarkan. Jika Anda memerlukan kontrol lebih besar atas proses penyalinan, gunakan \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) atau \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) untuk menyalin slide dan [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) untuk menyalin master. 

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Slide yang disisipkan.
### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

Menambahkan slide kosong baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Tata letak untuk slide. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Slide yang ditambahkan.
### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks slide baru. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Tata letak untuk slide. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Slide yang disisipkan.
### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Menambahkan salinan slide yang ditentukan ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide yang akan diklon. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Tata letak slide untuk slide baru. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Slide baru.
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks slide baru. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide yang akan diklon. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Tata letak slide untuk slide baru. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Slide yang disisipkan.
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Menambahkan salinan slide sumber yang ditentukan ke akhir koleksi. Tata letak yang sesuai akan dipilih secara otomatis dari master yang ditentukan (tata letak yang sesuai adalah tata letak dengan Type atau Name yang sama dengan tata letak slide sumber). Jika tidak ada tata letak yang sesuai, tata letak slide sumber akan disalin (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide yang akan diklon. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide untuk slide baru. |
| allowCloneMissingLayout | boolean | Jika tidak ada tata letak yang sesuai dalam master yang ditentukan, maka tata letak slide sumber akan disalin (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false). |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Slide baru.
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Menyisipkan salinan slide sumber yang ditentukan ke posisi yang ditentukan dalam koleksi. Tata letak yang sesuai akan dipilih secara otomatis dari master yang ditentukan (tata letak yang sesuai adalah tata letak dengan Type atau Name yang sama dengan tata letak slide sumber). Jika tidak ada tata letak yang sesuai, tata letak slide sumber akan disalin (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks slide baru. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide yang akan diklon. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide untuk slide baru. |
| allowCloneMissingLayout | boolean | Jika tidak ada tata letak yang sesuai dalam master yang ditentukan, maka tata letak slide sumber akan disalin (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false). |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Slide yang disisipkan.
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Menghapus kemunculan pertama objek tertentu dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Slide yang akan dihapus dari koleksi. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus elemen pada indeks yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Sebuah java.util.Iterator untuk seluruh koleksi.
### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Membuat dan mengembalikan array dengan semua slide di dalamnya.

**Mengembalikan:**
com.aspose.slides.ISlide[] - Array dari [Slide](../../com.aspose.slides/slide)
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Membuat dan mengembalikan array dengan semua slide dari rentang yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | int | Indeks slide pertama yang akan ditambahkan. |
| count | int | Jumlah slide yang akan ditambahkan. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Array dari [Slide](../../com.aspose.slides/slide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

Memindahkan slide dari koleksi ke posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks target. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide yang akan dipindahkan. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Memindahkan slide dari koleksi ke posisi yang ditentukan. Slide akan ditempatkan mulai dari indeks dalam urutan mereka muncul dalam daftar.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks target. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Slide yang akan dipindahkan. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

Mengembalikan indeks slide yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide yang akan dicari. |

**Mengembalikan:**
int - Indeks slide atau -1 jika slide bukan dari koleksi ini.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getSlides().addFromPdf("document.pdf");
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | java.lang.String | Jalur ke dokumen PDF |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Slide yang ditambahkan

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi dengan mempertimbangkan opsi impor PDF.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
>      pres.getSlides().addFromPdf("document.pdf", pdfImportOptions);
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | java.lang.String | Jalur ke dokumen PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opsi untuk impor PDF |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Slide yang ditambahkan

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Aliran yang akan digunakan sebagai sumber dokumen PDF |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Slide yang ditambahkan

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream, pdfImportOptions);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Aliran yang akan digunakan sebagai sumber dokumen PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opsi untuk impor PDF |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Slide yang ditambahkan

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlText | java.lang.String | HTML yang akan ditambahkan. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null, semua objek eksternal akan diabaikan. |
| uri | java.lang.String | URI HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Slide yang ditambahkan.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlText | java.lang.String | HTML yang akan ditambahkan. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Slide yang ditambahkan

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null, semua objek eksternal akan diabaikan. |
| uri | java.lang.String | URI HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Slide yang ditambahkan.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

--------------------

> ```
> // Buat sebuah instance dari kelas Presentation.
>  Presentation pres = new Presentation();
>  try {
>      String html = new String(Files.readAllBytes(Paths.get("file.html")));
>      // Panggil metode AddFromHtml dan berikan file HTML.
>      pres.getSlides().addFromHtml(html);
>      // Gunakan metode Save untuk menyimpan file sebagai dokumen PowerPoint.
>      pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Objek Stream yang akan digunakan sebagai sumber file HTML. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Slide yang ditambahkan

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Membuat slide dari teks HTML dan memasukkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk disisipkan. |
| htmlText | java.lang.String | HTML yang akan ditambahkan. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null, semua objek eksternal akan diabaikan. |
| uri | java.lang.String | URI HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

**Mengembalikan:**
com.aspose.slides.ISSlide[] - Slide yang ditambahkan.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Membuat slide dari teks HTML dan memasukkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk disisipkan. |
| htmlText | java.lang.String | HTML yang akan ditambahkan. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null, semua objek eksternal akan diabaikan. |
| uri | java.lang.String | URI HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |
| useSlideWithIndexAsStart | boolean | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks tersebut. Jika **false**, data akan ditambahkan ke slide yang dibuat. |

**Mengembalikan:**
com.aspose.slides.ISSlide[] - Slide yang ditambahkan.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

Membuat slide dari teks HTML dan memasukkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk disisipkan. |
| htmlText | java.lang.String | HTML yang akan ditambahkan. |

**Mengembalikan:**
com.aspose.slides.ISSlide[] - Slide yang ditambahkan

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Membuat slide dari teks HTML dan memasukkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk disisipkan. |
| htmlText | java.lang.String | HTML yang akan ditambahkan. |
| useSlideWithIndexAsStart | boolean | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks tersebut. Jika **false**, data akan ditambahkan ke slide yang dibuat. |

**Mengembalikan:**
com.aspose.slides.ISSlide[] - Slide yang ditambahkan

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Membuat slide dari teks HTML dan memasukkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk disisipkan. |
| htmlStream | java.io.InputStream | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null, semua objek eksternal akan diabaikan. |
| uri | java.lang.String | URI HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

**Mengembalikan:**
com.aspose.slides.ISSlide[] - Slide yang ditambahkan.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Membuat slide dari teks HTML dan memasukkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk disisipkan. |
| htmlStream | java.io.InputStream | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null, semua objek eksternal akan diabaikan. |
| uri | java.lang.String | URI HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |
| useSlideWithIndexAsStart | boolean | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks tersebut. Jika **false**, data akan ditambahkan ke slide yang dibuat. |

**Mengembalikan:**
com.aspose.slides.ISSlide[] - Slide yang ditambahkan.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Membuat slide dari teks HTML dan memasukkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk disisipkan. |
| htmlStream | java.io.InputStream | Objek Stream yang akan digunakan sebagai sumber file HTML. |

**Mengembalikan:**
com.aspose.slides.ISSlide[] - Slide yang ditambahkan

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Membuat slide dari teks HTML dan memasukkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk disisipkan. |
| htmlStream | java.io.InputStream | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| useSlideWithIndexAsStart | boolean | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks tersebut. Jika **false**, data akan ditambahkan ke slide yang dibuat. |

**Mengembalikan:**
com.aspose.slides.ISSlide[] - Slide yang ditambahkan

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks mulai dalam array target. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). Boolean read-only.

**Mengembalikan:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Object read-only.

**Mengembalikan:**
java.lang.Object