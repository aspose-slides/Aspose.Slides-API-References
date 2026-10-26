---
title: Presentation
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili sebuah presentasi Microsoft PowerPoint.
type: docs
url: /id/com.aspose.slides/presentation/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Mewakili presentasi Microsoft PowerPoint.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Membuat objek Presentation yang mewakili file presentasi
>  Presentation pres = new Presentation();
>  try {
>      // Dapatkan slide pertama
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Tambahkan autoshape tipe garis
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Simpan file presentasi.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Memuat file yang didukung dalam Presentation, misalnya ppt, pptx, odp dll.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Simpan file presentasi.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Presentation()](#Presentation--) | Konstruktor ini membuat presentasi baru dari awal. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Konstruktor ini membuat presentasi baru dari awal. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Konstruktor ini merupakan mekanisme utama untuk membaca Presentasi yang ada. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Konstruktor ini merupakan mekanisme utama untuk membaca Presentasi yang ada. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Konstruktor ini mendapatkan jalur file sumber dari mana isi Presentasi dibaca. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Konstruktor ini mendapatkan jalur file sumber dari mana isi Presentasi dibaca. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Mengembalikan atau mengatur tanggal dan waktu yang akan menggantikan konten bidang datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Mengembalikan atau mengatur tanggal dan waktu yang akan menggantikan konten bidang datetime. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Mengembalikan manajer HeaderFooter yang sebenarnya. |
| [getProtectionManager()](#getProtectionManager--) | Mendapatkan manajer izin untuk presentasi ini. |
| [getSlides()](#getSlides--) | Mengembalikan daftar semua slide yang didefinisikan dalam presentasi. |
| [getSections()](#getSections--) | Mengembalikan daftar semua bagian slide yang didefinisikan dalam presentasi. |
| [getSlideSize()](#getSlideSize--) | Mengembalikan objek ukuran slide. |
| [getNotesSize()](#getNotesSize--) | Mengembalikan objek ukuran slide catatan. |
| [getLayoutSlides()](#getLayoutSlides--) | Mengembalikan daftar semua slide tata letak yang didefinisikan dalam presentasi. |
| [getMasters()](#getMasters--) | Mengembalikan daftar semua slide master yang didefinisikan dalam presentasi. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Mengembalikan manajer master catatan. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Mengembalikan manajer master handout. |
| [getFontsManager()](#getFontsManager--) | Mengembalikan manajer font. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Mengembalikan gaya teks default untuk shape. |
| [getCommentAuthors()](#getCommentAuthors--) | Mengembalikan koleksi penulis komentar. |
| [getDocumentProperties()](#getDocumentProperties--) | Mengembalikan objek DocumentProperties yang berisi properti dokumen standar dan khusus. |
| [getImages()](#getImages--) | Mengembalikan koleksi semua gambar dalam presentasi. |
| [getAudios()](#getAudios--) | Mengembalikan koleksi semua file audio tersemat dalam presentasi. |
| [getVideos()](#getVideos--) | Mengembalikan koleksi semua file video tersemat dalam presentasi. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Mengembalikan pengaturan slide show untuk presentasi. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Mengembalikan koleksi tanda tangan yang digunakan untuk menandatangani presentasi. |
| [getCustomData()](#getCustomData--) | Mengembalikan data khusus presentasi. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Mengembalikan semua bagian data khusus dalam presentasi. |
| [getVbaProject()](#getVbaProject--) | Mendapatkan atau mengatur proyek VBA dengan makro presentasi. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Mendapatkan atau mengatur proyek VBA dengan makro presentasi. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Memberikan akses mudah ke semua hyperlink yang terdapat dalam semua slide presentasi (tidak termasuk master, layout, slide catatan). |
| [getViewProperties()](#getViewProperties--) | Mendapatkan properti tampilan luas presentasi. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Mewakili nomor slide pertama dalam presentasi |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Mewakili nomor slide pertama dalam presentasi |
| [getSensitivityLabels()](#getSensitivityLabels--) | Mengembalikan koleksi label sensitivitas yang diterapkan pada dokumen presentasi. |
| [getSlideById(long id)](#getSlideById-long-) | Mengembalikan Slide, MasterSlide, atau LayoutSlide berdasarkan Id. |
| [getSourceFormat()](#getSourceFormat--) | Mengembalikan informasi tentang format mana presentasi dimuat. |
| [getMasterTheme()](#getMasterTheme--) | Mengembalikan tema master. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Menyimpan semua slide presentasi ke file dengan format yang ditentukan. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Menyimpan semua slide presentasi ke aliran dalam format yang ditentukan. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Menyimpan semua slide presentasi ke file dengan format yang ditentukan dan opsi tambahan. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Menyimpan semua slide presentasi ke aliran dengan format yang ditentukan dan opsi tambahan. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Menyimpan semua slide presentasi ke serangkaian file yang mewakili markup XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Mengembalikan objek Image untuk semua slide presentasi. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Mengembalikan objek Thumbnail Image untuk slide tertentu dalam presentasi. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Mengembalikan objek Thumbnail Image untuk semua slide presentasi dengan skala khusus. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Mengembalikan objek Thumbnail Image untuk slide tertentu dalam presentasi dengan skala khusus. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Mengembalikan objek Thumbnail Image untuk semua slide presentasi dengan ukuran yang ditentukan. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Mengembalikan objek Thumbnail Image untuk slide tertentu dalam presentasi dengan ukuran yang ditentukan. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Menyimpan slide tertentu dalam presentasi ke file dengan format yang ditentukan sambil mempertahankan nomor halaman. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Menyimpan slide tertentu dalam presentasi ke file dengan format yang ditentukan sambil mempertahankan nomor halaman. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Menyimpan slide tertentu dalam presentasi ke aliran dengan format yang ditentukan sambil mempertahankan nomor halaman. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Menyimpan slide tertentu dalam presentasi ke aliran dengan format yang ditentukan sambil mempertahankan nomor halaman. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Menggabungkan run dengan pemformatan yang sama di semua paragraf dalam semua shape yang dapat diterima di semua slide. |
| [dispose()](#dispose--) | Melepaskan semua sumber daya yang digunakan oleh objek Presentation ini. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari teks. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Menyorot semua kecocokan ekspresi reguler dengan warna yang ditentukan. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Mengganti semua kemunculan teks yang ditentukan dengan teks lain yang ditentukan. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan. |
### Presentation() {#Presentation--}
```
public Presentation()
```

Konstruktor ini membuat presentasi baru dari awal. Presentasi yang dibuat memiliki satu slide kosong.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Konstruktor ini membuat presentasi baru dari awal. Presentasi yang dibuat memiliki satu slide kosong.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Opsi pemuatan tambahan. |
### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Konstruktor ini merupakan mekanisme utama untuk membaca Presentasi yang ada.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran masukan. |
### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Konstruktor ini merupakan mekanisme utama untuk membaca Presentasi yang ada.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran masukan. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Opsi pemuatan tambahan. |
### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Konstruktor ini mendapatkan jalur file sumber dari mana isi Presentasi dibaca.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.lang.String | File masukan. |
### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Konstruktor ini mendapatkan jalur file sumber dari mana isi Presentasi dibaca.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.lang.String | File masukan. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Opsi pemuatan tambahan. |
### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Mengembalikan atau mengatur tanggal dan waktu yang akan menggantikan konten bidang datetime. Waktu pembuatan objek Presentation ini secara default. **Baca/tulis** java.util.Date.

**Mengembalikan:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Mengembalikan atau mengatur tanggal dan waktu yang akan menggantikan konten bidang datetime. Waktu pembuatan objek Presentation ini secara default. **Baca/tulis** java.util.Date.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.Date |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. **Hanya-baca** IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Mengembalikan manajer HeaderFooter yang sebenarnya. **Hanya-baca** [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Properti IsFooterVisible digunakan untuk menunjukkan bahwa placeholder footer slide tidak ada.
>      {
>          headerFooterManager.setFooterVisibility(true); // Metode SetFooterVisibility digunakan untuk membuat placeholder footer slide terlihat.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Properti IsSlideNumberVisible digunakan untuk menunjukkan bahwa placeholder nomor halaman slide tidak ada.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Metode SetSlideNumberVisibility digunakan untuk membuat placeholder nomor halaman slide terlihat.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Properti IsDateTimeVisible digunakan untuk menunjukkan bahwa placeholder tanggal-waktu slide tidak ada.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Metode SetFooterVisibility digunakan untuk membuat placeholder tanggal-waktu slide terlihat.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Metode SetFooterText digunakan untuk mengatur teks pada placeholder footer slide.
>      headerFooterManager.setDateTimeText("Date and time text"); // Metode SetDateTimeText digunakan untuk mengatur teks pada placeholder tanggal-waktu slide.
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Metode SetFooterAndChildFootersVisibility digunakan untuk membuat master slide dan semua placeholder footer anak terlihat.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Metode SetSlideNumberAndChildSlideNumbersVisibility digunakan untuk membuat master slide dan semua placeholder nomor halaman anak terlihat.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Metode SetDateTimeAndChildDateTimesVisibility digunakan untuk membuat master slide dan semua placeholder tanggal-waktu anak terlihat.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Metode SetFooterAndChildFootersText digunakan untuk mengatur teks pada master slide dan semua placeholder footer anak.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Metode SetDateTimeAndChildDateTimesText digunakan untuk mengatur teks pada master slide dan semua placeholder tanggal-waktu anak.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Mendapatkan manajer izin untuk presentasi ini. **Hanya-baca** [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Mengembalikan:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Mengembalikan daftar semua slide yang didefinisikan dalam presentasi. **Hanya-baca** [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Membuat instance kelas Presentation yang mewakili file presentasi
>  Presentation pres = new Presentation();
>  try
>  {
>      // Mengatur warna latar slide pertama (ISlide) menjadi Biru
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // Membuat instance kelas Presentation yang mewakili file presentasi
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Mengatur latar dengan Gambar
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Mengatur gambar
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("Tulips.jpg");
>          // Menambahkan gambar ke koleksi gambar presentasi
>          IPPImage imgx = pres.getImages().addImage(fos);
>          pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      // Menulis presentasi ke disk
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Membuat instance kelas Presentation untuk memuat file presentasi sumber
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Menerapkan transisi tipe lingkaran pada slide 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Menerapkan transisi tipe sisir pada slide 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Menulis presentasi ke disk
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Membuat instance kelas Presentation yang mewakili file presentasi
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Menerapkan transisi tipe lingkaran pada slide 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Mengatur waktu transisi selama 3 detik
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Menerapkan transisi tipe sisir pada slide 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Mengatur waktu transisi selama 5 detik
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Menerapkan transisi tipe zoom pada slide 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Mengatur waktu transisi selama 7 detik
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Menulis presentasi ke disk
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Mengembalikan daftar semua bagian slide yang didefinisikan dalam presentasi. **Hanya-baca** [ISectionCollection](../../com.aspose.slides/isectioncollection).

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // section1 akan berakhir pada newSlide2 dan setelahnya section2 akan dimulai
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Mengembalikan objek ukuran slide. **Hanya-baca** [ISlideSize](../../com.aspose.slides/islidesize).

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // Membuat instance objek Presentation yang mewakili file presentasi
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Mengatur ukuran slide presentasi yang dihasilkan agar sama dengan sumber
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Metode SetSize digunakan untuk mengatur ukuran slide dengan men-skala konten agar sesuai
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Metode SetSize digunakan untuk mengatur ukuran slide dengan memaksimalkan ukuran konten
>          // Simpan Presentasi ke disk
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // Ukuran kertas A4
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Mengembalikan objek ukuran slide catatan. **Hanya-baca** [INotesSize](../../com.aspose.slides/inotessize).

**Mengembalikan:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Mengembalikan daftar semua slide tata letak yang didefinisikan dalam presentasi. **Hanya-baca** [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Anda dapat mengakses API alternatif untuk menambah/menyisipkan/menghapus/menkloning slide tata letak dengan menggunakan properti IMasterSlide.LayoutSlides.

**Mengembalikan:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Mengembalikan daftar semua slide master yang didefinisikan dalam presentasi. **Hanya-baca** [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Membuat instance kelas Presentation yang mewakili file presentasi
>  Presentation pres = new Presentation();
>  try
>  {
>      // Mengatur warna latar Master ISlide menjadi Hijau Hutan
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Menulis presentasi ke disk
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Membuat instance kelas Presentation yang mewakili file presentasi
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Mencoba mencari berdasarkan tipe slide tata letak
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // Situasi ketika sebuah presentasi tidak mengandung beberapa tipe tata letak.
>          // File presentasi hanya berisi tipe tata letak Blank dan Custom.
>          // Namun slide tata letak dengan tipe Custom memiliki nama slide yang berbeda,
>          // seperti "Title", "Title and Content", dll. Dan memungkinkan menggunakan nama-nama ini
>          // untuk pemilihan slide tata letak.
>          // Juga memungkinkan menggunakan sekumpulan tipe shape placeholder. Misalnya,
>          // slide Title seharusnya hanya memiliki placeholder tipe Title, dll.
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // Menambahkan slide kosong dengan slide tata letak yang ditambahkan
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Simpan presentasi
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Mengembalikan:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Mengembalikan manajer master catatan. **Hanya-baca** [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Mengembalikan:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Mengembalikan manajer master handout. **Hanya-baca** [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Mengembalikan:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Mengembalikan manajer font. **Hanya-baca** [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Memuat presentasi
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Memuat font sumber yang akan diganti
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Simpan presentasi
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Mengembalikan gaya teks default untuk shape. **Hanya-baca** [ITextStyle](../../com.aspose.slides/itextstyle).

**Mengembalikan:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Mengembalikan koleksi penulis komentar. **Hanya-baca** [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Mengembalikan:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Mengembalikan objek DocumentProperties yang berisi properti dokumen standar dan khusus. **Hanya-baca** [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Mengembalikan:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Mengembalikan koleksi semua gambar dalam presentasi. **Hanya-baca** [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // membuat presentasi baru yang akan ditambahkan gambar.
>  Presentation pres = new Presentation();
>  try
>  {
>      // mengasumsikan kita memiliki file gambar besar yang ingin dimasukkan ke dalam presentasi
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Tambahkan gambar ke presentasi - kami memilih perilaku KeepLocked karena kami
>          // TIDAK bermaksud mengakses file "largeImage.png" file.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Menyimpan presentasi. Meskipun presentasi besar dihasilkan, konsumsi memori
>          // tetap rendah selama siklus hidup objek pres
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          // Menambahkan gambar ke presentasi
>          IPPImage image = pres.getImages().addImage(fos);
>          // Membuat bingkai gambar pada slide 1 berdasarkan gambar yang telah ditambahkan sebelumnya
>          IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>          pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

Mengembalikan koleksi semua file audio tersemat dalam presentasi. **Hanya-baca** [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("audio.mp3");
>          IAudio audio = pres.getAudios().addAudio(fos);
>          IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>          audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```

Mengembalikan koleksi semua file video tersemat dalam presentasi. **Hanya-baca** [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // Membuat instance kelas Presentation yang mewakili PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Dapatkan slide pertama
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Menyisipkan video ke dalam presentasi
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Tambahkan Video Frame
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Atur video ke Video Frame
>      vf.setEmbeddedVideo(vid);
>      // Atur mode pemutaran dan volume video
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // Tulis file PPTX ke disk
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // Membuat presentasi baru yang akan ditambahkan video
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Mari tambahkan video ke presentasi - kami memilih perilaku KeepLocked karena kami
>          // tidak berniat mengakses file "veryLargeVideo.avi".
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Simpan presentasi. Saat presentasi besar dihasilkan, konsumsi memori
>          // tetap rendah selama siklus hidup objek pres
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // Mengunci file sumber dan TIDAK memuatnya ke memori
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Membuat instance Presentation, mengunci file "hugePresentationWithAudiosAndVideos.pptx".
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Mari simpan setiap video ke file. Untuk menghindari penggunaan memori tinggi, kami membutuhkan buffer yang akan digunakan
>      // untuk mentransfer data dari aliran video presentasi ke aliran untuk file video yang baru dibuat.
>      byte[] buffer = new byte[81024];
>      // Mengiterasi video-video
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Membuka aliran video presentasi. Harap dicatat bahwa kami secara sengaja menghindari mengakses properti
>          // seperti video.BinaryData - karena properti ini mengembalikan array byte yang berisi video lengkap, yang kemudian
>          // menyebabkan byte dimuat ke memori. Kami menggunakan video.GetStream, yang akan mengembalikan Stream - dan tidak
>          //  memerlukan kami memuat seluruh video ke memori.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // Konsumsi memori akan tetap rendah terlepas dari ukuran video atau presentasi,
>      }
>          // Jika diperlukan, Anda dapat menerapkan langkah yang sama untuk file audio.
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      // tambahkan videoFrame
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      // muat thumbnail
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // Membuat instance objek Presentation yang mewakili file presentasi
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Mengembalikan:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

Mengembalikan pengaturan slide show untuk presentasi.

**Mengembalikan:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

Mengembalikan koleksi tanda tangan yang digunakan untuk menandatangani presentasi. **Hanya-baca** [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Mengembalikan data khusus presentasi. **Hanya-baca** [ICustomData](../../com.aspose.slides/icustomdata).

**Mengembalikan:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

Mengembalikan semua bagian data khusus dalam presentasi. **Hanya-baca** ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Iterasi semua bagian XML khusus
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

Mendapatkan atau mengatur proyek VBA dengan makro presentasi. **Baca/tulis** [IVbaProject](../../com.aspose.slides/ivbaproject).

**Mengembalikan:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

Mendapatkan atau mengatur proyek VBA dengan makro presentasi. **Baca/tulis** [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Memberikan akses mudah ke semua hyperlink yang terdapat dalam semua slide presentasi (tidak termasuk master, layout, slide catatan). **Hanya-baca** [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Mengembalikan:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

Mendapatkan properti tampilan luas presentasi. **Hanya-baca** [IViewProperties](../../com.aspose.slides/iviewproperties).

**Mengembalikan:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

Mewakili nomor slide pertama dalam presentasi

**Mengembalikan:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

Mewakili nomor slide pertama dalam presentasi

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

Mengembalikan koleksi label sensitivitas yang diterapkan pada dokumen presentasi. **Hanya-baca** [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Cetak label yang diterapkan
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Tambahkan label baru
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Dapatkan Id label sensitivitas dari kebijakan
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Dapatkan pengidentifikasi situs Azure AD dari kebijakan
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

Mengembalikan Slide, MasterSlide, atau LayoutSlide berdasarkan Id.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | long | Id slide. |

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

Mengembalikan informasi tentang format mana presentasi dimuat. **Hanya-baca** [SourceFormat](../../com.aspose.slides/sourceformat).

**Mengembalikan:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

Mengembalikan tema master. **Hanya-baca** [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //Membuat instance objek Presentation yang mewakili file presentasi
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

Menyimpan semua slide presentasi ke file dengan format yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | java.lang.String | Jalur ke file yang dibuat. |
| format | int | Format data yang diekspor. |
### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

Menyimpan semua slide presentasi ke aliran dalam format yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran keluaran. |
| format | int | Format data yang diekspor. |
### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

Menyimpan semua slide presentasi ke file dengan format yang ditentukan dan opsi tambahan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | java.lang.String | Jalur ke file yang dibuat. |
| format | int | Format data yang diekspor. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opsi format tambahan. |
### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

Menyimpan semua slide presentasi ke aliran dalam format yang ditentukan dan opsi tambahan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran keluaran. |
| format | int | Format data yang diekspor. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opsi format tambahan. |
### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

Menyimpan semua slide presentasi ke serangkaian file yang mewakili markup XAML.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Opsi format XAML. |
### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

Mengembalikan objek Image untuk semua slide presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi Tiff. |

**Mengembalikan:**
com.aspose.slides.IImage[] - objek Image.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

Mengembalikan objek Thumbnail Image untuk slide tertentu dalam presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi Tiff. |
| slides | int[] | Array posisi slide, mulai dari 1. |

**Mengembalikan:**
com.aspose.slides.IImage[] - objek Image.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Mengembalikan objek Thumbnail Image untuk semua slide presentasi dengan skala khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi Tiff. |
| scaleX | float | Nilai skala pada sumbu x. |
| scaleY | float | Nilai skala pada sumbu y. |

**Mengembalikan:**
com.aspose.slides.IImage[] - objek Image.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Mengembalikan objek Thumbnail Image untuk slide tertentu dalam presentasi dengan skala khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi Tiff. |
| slides | int[] | Array posisi slide, mulai dari 1. |
| scaleX | float | Nilai skala pada sumbu x. |
| scaleY | float | Nilai skala pada sumbu y. |

**Mengembalikan:**
com.aspose.slides.IImage[] - objek Image.
### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Mengembalikan objek Thumbnail Image untuk semua slide presentasi dengan ukuran yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi Tiff. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Ukuran gambar yang akan dibuat. |

**Mengembalikan:**
com.aspose.slides.IImage[] - objek Image.
### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Mengembalikan objek Thumbnail Image untuk slide tertentu dalam presentasi dengan ukuran yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi Tiff. |
| slides | int[] | Array posisi slide, mulai dari 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Ukuran gambar yang akan dibuat. |

**Mengembalikan:**
com.aspose.slides.IImage[] - objek Image.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

Menyimpan slide tertentu dalam presentasi ke file dengan format yang ditentukan sambil mempertahankan nomor halaman.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | java.lang.String | Jalur ke file yang dibuat. |
| slides | int[] | Array posisi slide, mulai dari 1. |
| format | int | Format data yang diekspor. |
### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

Menyimpan slide tertentu dalam presentasi ke file dengan format yang ditentukan sambil mempertahankan nomor halaman.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | java.lang.String | Jalur ke file yang dibuat. |
| slides | int[] | Array posisi slide, mulai dari 1. |
| format | int | Format data yang diekspor. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opsi format tambahan. |
### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

Menyimpan slide tertentu dalam presentasi ke aliran dengan format yang ditentukan sambil mempertahankan nomor halaman.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran keluaran. |
| slides | int[] | Array posisi slide, mulai dari 1. |
| format | int | Format data yang diekspor. |
### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Menyimpan slide tertentu dalam presentasi ke aliran dengan format yang ditentukan sambil mempertahankan nomor halaman.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(scaleX, scaleY).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom size.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      com.aspose.slides.android.Size size = new com.aspose.slides.android.Size(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(size).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran keluaran. |
| slides | int[] | Array posisi slide, mulai dari 1. |
| format | int | Format data yang diekspor. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opsi format tambahan. |
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Menggabungkan run dengan pemformatan yang sama di semua paragraf dalam semua shape yang dapat diterima di semua slide.

### dispose() {#dispose--}
```
public final void dispose()
```

Melepaskan semua sumber daya yang digunakan oleh objek Presentation ini.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk dari teks. **Hanya-baca** [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // menyorot semua kemunculan terpisah 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan disorot. |
| highlightColor | java.lang.Integer | Warna untuk menyorot teks. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // menyorot semua kemunculan terpisah 'the'
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan disorot. |
| highlightColor | java.lang.Integer | Warna untuk menyorot teks. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opsi pencarian teks [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objek panggilan balik untuk menerima hasil pencarian [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Menyorot semua kecocokan ekspresi reguler dengan warna yang ditentukan.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // menyorot semua kata dengan 10 simbol atau lebih
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Ekspresi reguler java.util.regex.Pattern untuk mendapatkan string yang akan disorot. |
| highlightColor | java.lang.Integer | Warna untuk menyorot teks. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objek panggilan balik untuk menerima hasil pencarian [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Mengganti semua kemunculan teks yang ditentukan dengan teks lain yang ditentukan.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Ganti semua kemunculan terpisah 'the' dengan '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| oldText | java.lang.String | String yang akan diganti. |
| newText | java.lang.String | String untuk mengganti semua kemunculan oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opsi pencarian teks [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objek panggilan balik untuk menerima hasil pencarian [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Ganti semua kata dengan 10 simbol atau lebih dengan '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Ekspresi reguler java.util.regex.Pattern untuk mendapatkan string yang akan diganti. |
| newText | java.lang.String | String untuk mengganti semua kemunculan string yang akan diganti. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objek panggilan balik untuk menerima hasil pencarian [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |