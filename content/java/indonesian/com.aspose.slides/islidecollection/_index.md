---
title: ISlideCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili kumpulan slide.
type: docs
url: /id/com.aspose.slides/islidecollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

Mewakili koleksi slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Menambahkan salinan slide yang ditentukan ke akhir koleksi. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Menambahkan salinan slide yang ditentukan ke akhir bagian yang ditentukan. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Menambahkan slide kosong baru ke akhir koleksi. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Menambahkan salinan slide yang ditentukan ke akhir koleksi. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Menambahkan salinan slide sumber yang ditentukan ke akhir koleksi. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Menyisipkan salinan slide sumber yang ditentukan ke posisi yang ditentukan dalam koleksi. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Menghapus kejadian pertama dari objek tertentu dalam koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [toArray()](#toArray--) | Membuat dan mengembalikan array dengan semua slide di dalamnya. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Membuat dan mengembalikan array dengan semua slide dari rentang yang ditentukan. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Memindahkan slide dari koleksi ke posisi yang ditentukan. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Memindahkan slide dari koleksi ke posisi yang ditentukan. Slide akan ditempatkan mulai dari indeks dalam urutan mereka muncul dalam daftar. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Mengembalikan indeks slide yang ditentukan dalam koleksi. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi dengan mempertimbangkan opsi impor PDF. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) : | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

Mendapatkan elemen pada indeks yang ditentukan. Hanya-baca [ISlide](../../com.aspose.slides/islide).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide)
### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

Menambahkan salinan slide yang ditentukan ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide untuk digandakan.

--------------------

When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) or \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) for cloning slides, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) or [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) for cloning layouts and [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) for cloning masters. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Slide baru.
### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
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
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide untuk digandakan. |
| section | [ISection](../../com.aspose.slides/isection) | Bagian untuk slide baru. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Slide baru.
### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks slide baru. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide untuk digandakan.

--------------------

When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) or \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) for cloning slides and [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) for cloning masters. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Slide yang disisipkan.
### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
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
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
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
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Menambahkan salinan slide yang ditentukan ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide untuk digandakan. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide tata letak untuk slide baru. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Slide baru.
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks slide baru. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide untuk digandakan. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide tata letak untuk slide baru. |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Slide yang disisipkan.
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Menambahkan salinan slide sumber yang ditentukan ke akhir koleksi. Tata letak yang sesuai akan dipilih secara otomatis dari master yang ditentukan (tata letak yang sesuai adalah tata letak dengan Type atau Name yang sama dengan tata letak slide sumber). Jika tidak ada tata letak yang sesuai maka tata letak slide sumber akan digandakan (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide untuk digandakan. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide untuk slide baru. |
| allowCloneMissingLayout | boolean | Jika tidak ada tata letak yang sesuai di master yang ditentukan maka tata letak slide sumber akan digandakan (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false). |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Slide baru.
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Menyisipkan salinan slide sumber yang ditentukan ke posisi yang ditentukan dalam koleksi. Tata letak yang sesuai akan dipilih secara otomatis dari master yang ditentukan (tata letak yang sesuai adalah tata letak dengan Type atau Name yang sama dengan tata letak slide sumber). Jika tidak ada tata letak yang sesuai maka tata letak slide sumber akan digandakan (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks slide baru. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide untuk digandakan. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide untuk slide baru. |
| allowCloneMissingLayout | boolean | Jika tidak ada tata letak yang sesuai di master yang ditentukan maka tata letak slide sumber akan digandakan (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false). |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide) - Slide yang disisipkan.
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

Menghapus kejadian pertama dari objek tertentu dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Slide yang akan dihapus dari koleksi. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus elemen pada indeks yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

Membuat dan mengembalikan array dengan semua slide di dalamnya.

**Mengembalikan:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

Membuat dan mengembalikan array dengan semua slide dari rentang yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | int | Indeks slide pertama yang akan ditambahkan. |
| count | int | Jumlah slide yang akan ditambahkan. |

**Mengembalikan:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

Memindahkan slide dari koleksi ke posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks target. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide yang akan dipindahkan. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

Memindahkan slide dari koleksi ke posisi yang ditentukan. Slide akan ditempatkan mulai dari indeks dalam urutan mereka muncul dalam daftar.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks target. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Slide yang akan dipindahkan. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

Mengembalikan indeks slide yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide yang dicari. |

**Mengembalikan:**
int - Indeks slide atau -1 jika slide bukan bagian dari koleksi ini.
### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
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
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
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
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
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
| pdfStream | java.io.InputStream | Stream yang akan digunakan sebagai sumber dokumen PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opsi untuk impor PDF |

**Mengembalikan:**  
com.aspose.slides.ISlide[] - Slide yang ditambahkan
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
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
| pdfStream | java.io.InputStream | Stream yang akan digunakan sebagai sumber dokumen PDF |

**Mengembalikan:**  
com.aspose.slides.ISlide[] - Slide yang ditambahkan
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlText | java.lang.String | HTML yang akan ditambahkan. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | java.lang.String | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

**Mengembalikan:**  
com.aspose.slides.ISlide[] - Slide yang ditambahkan.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
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
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | java.lang.String | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

**Mengembalikan:**  
com.aspose.slides.ISlide[] - Slide yang ditambahkan.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Objek Stream yang akan digunakan sebagai sumber file HTML. |

**Mengembalikan:**  
com.aspose.slides.ISlide[] - Slide yang ditambahkan
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk disisipkan. |
| htmlText | java.lang.String | HTML yang akan ditambahkan. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | java.lang.String | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

**Mengembalikan:**  
com.aspose.slides.ISlide[] - Slide yang ditambahkan.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk disisipkan. |
| htmlText | java.lang.String | HTML yang akan ditambahkan. |

**Mengembalikan:**  
com.aspose.slides.ISlide[] - Slide yang ditambahkan
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk disisipkan. |
| htmlStream | java.io.InputStream | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | java.lang.String | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

**Mengembalikan:**  
com.aspose.slides.ISSlide[] - Slide yang ditambahkan.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk disisipkan. |
| htmlStream | java.io.InputStream | Objek Stream yang akan digunakan sebagai sumber file HTML. |

**Mengembalikan:**  
com.aspose.slides.ISSlide[] - Slide yang ditambahkan
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk disisipkan. |
| htmlText | java.lang.String | HTML yang akan ditambahkan. |
| useSlideWithIndexAsStart | boolean | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks tersebut. Jika **false**, data akan ditambahkan ke slide yang dibuat. |

**Mengembalikan:**  
com.aspose.slides.ISSlide[] - Slide yang ditambahkan
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk disisipkan. |
| htmlText | java.lang.String | HTML yang akan ditambahkan. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | java.lang.String | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |
| useSlideWithIndexAsStart | boolean | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks tersebut. Jika **false**, data akan ditambahkan ke slide yang dibuat. |

**Mengembalikan:**  
com.aspose.slides.ISSlide[] - Slide yang ditambahkan.
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk disisipkan. |
| htmlStream | java.io.InputStream | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| useSlideWithIndexAsStart | boolean | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks tersebut. Jika **false**, data akan ditambahkan ke slide yang dibuat. |

**Mengembalikan:**  
com.aspose.slides.ISSlide[] - Slide yang ditambahkan
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk disisipkan. |
| htmlStream | java.io.InputStream | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | java.lang.String | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |
| useSlideWithIndexAsStart | boolean | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks tersebut. Jika **false**, data akan ditambahkan ke slide yang dibuat. |

**Mengembalikan:**  
com.aspose.slides.ISSlide[] - Slide yang ditambahkan.