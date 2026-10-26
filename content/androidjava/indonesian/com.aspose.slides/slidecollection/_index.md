---
title: SlideCollection
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili koleksi slide.
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

Mewakili kumpulan slide.

## Metode

| Metode | Deskripsi |
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
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Menghapus kemunculan pertama dari objek tertentu dalam koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [toArray()](#toArray--) | Membuat dan mengembalikan array yang berisi semua slide. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Membuat dan mengembalikan array yang berisi semua slide dari rentang yang ditentukan. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Memindahkan slide dari koleksi ke posisi yang ditentukan. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Memindahkan slide dari koleksi ke posisi yang ditentukan. Slide akan ditempatkan mulai dari indeks dalam urutan mereka muncul dalam daftar. |
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

Mengambil jumlah elemen yang sebenarnya terkandung dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Mengambil elemen pada indeks yang ditentukan. Hanya-baca [Slide](../../com.aspose.slides/slide).

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
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone.

--------------------

When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) or \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) for cloning slides, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) or [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) for cloning layouts and [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) for cloning masters. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - New slide.

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
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone. |
| section | [ISection](../../com.aspose.slides/isection) | Section for a new slide. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - New slide.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Membuat instance kelas Presentation yang mewakili file presentasi
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Menggandakan slide yang diinginkan ke akhir koleksi slide dalam presentasi yang sama
>      ISlideCollection slds = pres.getSlides();
>      // Menggandakan slide yang diinginkan ke indeks yang ditentukan dalam presentasi yang sama
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Menulis presentasi yang dimodifikasi ke disk
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Membuat instance kelas Presentation untuk memuat file presentasi sumber
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Membuat instance kelas Presentation untuk PPTX tujuan (tempat slide akan digandakan)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Menulis presentasi tujuan ke disk
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
| index | int | Index of new slide. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone.

--------------------

When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) or \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) for cloning slides and [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) for cloning masters. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

Menambahkan slide kosong baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout for a slide. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Added slide.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Index of a new slide. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout for a slide. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Menambahkan salinan slide yang ditentukan ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout slide for a new slide. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - New slide.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout slide for a new slide. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Menambahkan salinan slide sumber yang ditentukan ke akhir koleksi. Layout yang sesuai akan dipilih secara otomatis dari master yang ditentukan (layout yang sesuai adalah layout dengan Type atau Name yang sama dengan layout slide sumber). Jika tidak ada layout yang sesuai maka layout slide sumber akan disalin (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide for a new slide. |
| allowCloneMissingLayout | boolean | Jika tidak ada layout yang sesuai di master yang ditentukan maka layout slide sumber akan disalin (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false). |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - New slide.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Menyisipkan salinan slide sumber yang ditentukan ke posisi yang ditentukan dalam koleksi. Layout yang sesuai akan dipilih secara otomatis dari master yang ditentukan (layout yang sesuai adalah layout dengan Type atau Name yang sama dengan layout slide sumber). Jika tidak ada layout yang sesuai maka layout slide sumber akan disalin (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide for a new slide. |
| allowCloneMissingLayout | boolean | Jika tidak ada layout yang sesuai di master yang ditentukan maka layout slide sumber akan disalin (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false). |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Menghapus kemunculan pertama dari objek tertentu dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | The slide to remove from the collection. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus elemen pada indeks yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - An java.util.Iterator for the entire collection.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Membuat dan mengembalikan array yang berisi semua slide.

**Mengembalikan:**
com.aspose.slides.ISlide[] - Array of [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Membuat dan mengembalikan array yang berisi semua slide dari rentang yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | int | An index of a first slide to add. |
| count | int | A number of slides to add. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Array of [Slide](../../com.aspose.slides/slide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

Memindahkan slide dari koleksi ke posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Target index. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide to move. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Memindahkan slide dari koleksi ke posisi yang ditentukan. Slide akan ditempatkan mulai dari indeks dalam urutan mereka muncul dalam daftar.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Target index. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Slides to move. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

Mengembalikan indeks slide yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide to find. |

**Mengembalikan:**
int - Index of a slide or -1 if slide not from this collection.

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
| path | java.lang.String | A path to the PDF document |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Added slides

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
| path | java.lang.String | A path to the PDF document |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Options for pdf import |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Added slides

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi.

--------------------

> ```
> Contoh:
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
| pdfStream | java.io.InputStream | A stream which will be used as a source of the PDF document |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Added slides

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
| pdfStream | java.io.InputStream | A stream which will be used as a source of the PDF document |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Options for pdf import |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Added slides

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlText | java.lang.String | Html to add. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | java.lang.String | An URI of the specified HTML. Used to resolve relative links. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Added slides.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlText | java.lang.String | Html to add. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Added slides

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlStream | java.io.InputStream | A Stream object which will be used as a source of a HTML file. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | java.lang.String | An URI of the specified HTML. Used to resolve relative links. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Added slides.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

--------------------

> ```
> // Membuat sebuah instance dari kelas Presentation.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // Panggil metode AddFromHtml dan lewati file HTML.
>          pres.getSlides().addFromHtml(fos);
>          // Gunakan metode Save untuk menyimpan file sebagai dokumen PowerPoint.
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlStream | java.io.InputStream | A Stream object which will be used as a source of a HTML file. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | java.lang.String | Html to add. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | java.lang.String | An URI of the specified HTML. Used to resolve relative links. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Added slides.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | java.lang.String | Html to add. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | java.lang.String | An URI of the specified HTML. Used to resolve relative links. |
| useSlideWithIndexAsStart | boolean | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan. Jika **false**, data akan ditambahkan ke slide yang dibuat. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Added slides.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | java.lang.String | Html to add. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | java.lang.String | Html to add. |
| useSlideWithIndexAsStart | boolean | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan. Jika **false**, data akan ditambahkan ke slide yang dibuat. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlStream | java.io.InputStream | A Stream object which will be used as a source of a HTML file. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | java.lang.String | An URI of the specified HTML. Used to resolve relative links. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Added slides.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlStream | java.io.InputStream | A Stream object which will be used as a source of a HTML file. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | java.lang.String | An URI of the specified HTML. Used to resolve relative links. |
| useSlideWithIndexAsStart | boolean | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan. Jika **false**, data akan ditambahkan ke slide yang dibuat. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Added slides.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlStream | java.io.InputStream | A Stream object which will be used as a source of a HTML file. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlStream | java.io.InputStream | A Stream object which will be used as a source of a HTML file. |
| useSlideWithIndexAsStart | boolean | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan. Jika **false**, data akan ditambahkan ke slide yang dibuat. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Added slides

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). Hanya-baca boolean.

**Mengembalikan:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Hanya-baca Object.

**Mengembalikan:**
java.lang.Object