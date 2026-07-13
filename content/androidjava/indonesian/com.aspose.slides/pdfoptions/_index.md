---
title: PdfOptions
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format Pdf.
type: docs
url: /id/com.aspose.slides/pdfoptions/
---
**Kewarisan:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format Pdf.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Membuat instance kelas PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Mengatur kualitas Jpeg
>      pdfOptions.setJpegQuality((byte)90);
>      // Mengatur perilaku untuk metafile
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Mengatur tingkat kompresi teks
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Mendefinisikan standar PDF
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Menyimpan presentasi sebagai PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Membuat instance kelas Presentation yang mewakili file PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Membuat instance kelas PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Menambahkan slide tersembunyi
>      pdfOptions.setShowHiddenSlides(true);
>      // Menyimpan presentasi sebagai PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Membuat instance objek Presentation yang mewakili file PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Membuat instance kelas PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Mengatur kata sandi PDF dan izin akses
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Menyimpan presentasi sebagai PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Membuat instance objek Presentation yang mewakili file presentasi
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Mengatur Tipe Slide dan Ukuran
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Konstruktor default. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Mendapatkan atau mengatur mode di mana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Mendapatkan atau mengatur mode di mana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [getTextCompression()](#getTextCompression--) | Menentukan jenis kompresi yang akan digunakan untuk semua konten teks dalam dokumen. |
| [setTextCompression(int value)](#setTextCompression-int-) | Menentukan jenis kompresi yang akan digunakan untuk semua konten teks dalam dokumen. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Menunjukkan apakah kompresi paling efektif (bukan yang default) untuk setiap gambar harus dipilih secara otomatis. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Menunjukkan apakah kompresi paling efektif (bukan yang default) untuk setiap gambar harus dipilih secara otomatis. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Menentukan apakah Aspose.Slides akan menyematkan font umum untuk teks ASCII (rentang kode 33..127). |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Menentukan apakah Aspose.Slides akan menyematkan font umum untuk teks ASCII (rentang kode 33..127). |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Mengembalikan atau mengatur array nama keluarga font yang ditentukan pengguna yang harus dianggap umum oleh Aspose.Slides. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Mengembalikan atau mengatur array nama keluarga font yang ditentukan pengguna yang harus dianggap umum oleh Aspose.Slides. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Menentukan apakah semua karakter font harus disematkan atau hanya subset yang digunakan. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Menentukan apakah semua karakter font harus disematkan atau hanya subset yang digunakan. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Menunjukkan apakah teks harus di rasterisasi sebagai bitmap dan disimpan ke PDF ketika font tidak mendukung gaya tebal. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Menunjukkan apakah teks harus di rasterisasi sebagai bitmap dan disimpan ke PDF ketika font tidak mendukung gaya tebal. |
| [getJpegQuality()](#getJpegQuality--) | Mengembalikan atau mengatur nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Mengembalikan atau mengatur nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF. |
| [getCompliance()](#getCompliance--) | Level kepatuhan yang diinginkan untuk dokumen PDF yang dihasilkan. |
| [setCompliance(int value)](#setCompliance-int-) | Level kepatuhan yang diinginkan untuk dokumen PDF yang dihasilkan. |
| [getPassword()](#getPassword--) | Menetapkan kata sandi pengguna untuk melindungi dokumen PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Menetapkan kata sandi pengguna untuk melindungi dokumen PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Berisi seperangkat flag yang menentukan izin akses mana yang harus diberikan saat dokumen dibuka dengan akses pengguna. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Berisi seperangkat flag yang menentukan izin akses mana yang harus diberikan saat dokumen dibuka dengan akses pengguna. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Benar untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Benar untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Mengembalikan atau mengatur nilai yang menentukan resolusi gambar dalam dokumen PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Mengembalikan atau mengatur nilai yang menentukan resolusi gambar dalam dokumen PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Benar untuk menggambar bingkai hitam di sekitar setiap slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Benar untuk menggambar bingkai hitam di sekitar setiap slide. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Mendapatkan atau mengatur warna transparan gambar. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Mendapatkan atau mengatur warna transparan gambar. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Menerapkan warna transparan yang ditentukan ke gambar jika true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Menerapkan warna transparan yang ditentukan ke gambar jika true. |
| [getIncludeOleData()](#getIncludeOleData--) | Benar untuk mengonversi semua data OLE dari presentasi menjadi file tersemat dalam PDF yang dihasilkan. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Benar untuk mengonversi semua data OLE dari presentasi menjadi file tersemat dalam PDF yang dihasilkan. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Konstruktor default.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Mendapatkan atau mengatur mode di mana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Mendapatkan atau mengatur mode di mana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. Hanya-baca [IInkOptions](../../com.aspose.slides/iinkoptions)

**Mengembalikan:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Defaultnya false.

**Mengembalikan:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Defaultnya false.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Menentukan jenis kompresi yang akan digunakan untuk semua konten teks dalam dokumen. Baca/tulis [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Defaultnya [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Mengembalikan:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Menentukan jenis kompresi yang akan digunakan untuk semua konten teks dalam dokumen. Baca/tulis [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Defaultnya [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Menunjukkan apakah kompresi paling efektif (bukan yang default) untuk setiap gambar harus dipilih secara otomatis. Jika diatur ke true, untuk setiap gambar dalam presentasi algoritma kompresi yang paling tepat akan dipilih, yang akan menghasilkan ukuran PDF yang lebih kecil.

--------------------

Pemilihan rasio kompresi gambar terbaik memerlukan komputasi yang berat dan menggunakan memori tambahan, dan opsi ini defaultnya false.

--------------------

Defaultnya false.

**Mengembalikan:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Menunjukkan apakah kompresi paling efektif (bukan yang default) untuk setiap gambar harus dipilih secara otomatis. Jika diatur ke true, untuk setiap gambar dalam presentasi algoritma kompresi yang paling tepat akan dipilih, yang akan menghasilkan ukuran PDF yang lebih kecil.

--------------------

Pemilihan rasio kompresi gambar terbaik memerlukan komputasi yang berat dan menggunakan memori tambahan, dan opsi ini defaultnya false.

--------------------

Defaultnya false.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Menentukan apakah Aspose.Slides akan menyematkan font umum untuk teks ASCII (rentang kode 33..127). Font untuk kode karakter di atas 127 selalu disematkan. Daftar font umum mencakup 14 font dasar PDF dan font tambahan yang ditentukan pengguna. Baca/tulis boolean.

--------------------

Defaultnya **true**.

**Mengembalikan:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Menentukan apakah Aspose.Slides akan menyematkan font umum untuk teks ASCII (rentang kode 33..127). Font untuk kode karakter di atas 127 selalu disematkan. Daftar font umum mencakup 14 font dasar PDF dan font tambahan yang ditentukan pengguna. Baca/tulis boolean.

--------------------

Defaultnya **true**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Mengembalikan atau mengatur array nama keluarga font yang ditentukan pengguna yang harus dianggap umum oleh Aspose.Slides. Baca/tulis String[].

**Mengembalikan:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Mengembalikan atau mengatur array nama keluarga font yang ditentukan pengguna yang harus dianggap umum oleh Aspose.Slides. Baca/tulis String[].

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Menentukan apakah semua karakter font harus disematkan atau hanya subset yang digunakan. Baca/tulis boolean.

--------------------

Defaultnya **false**.

**Mengembalikan:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Menentukan apakah semua karakter font harus disematkan atau hanya subset yang digunakan. Baca/tulis boolean.

--------------------

Defaultnya **false**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Menunjukkan apakah teks harus di rasterisasi sebagai bitmap dan disimpan ke PDF ketika font tidak mendukung gaya tebal. Pendekatan ini dapat meningkatkan kualitas teks dalam PDF yang dihasilkan untuk font tertentu. Baca/tulis boolean.

--------------------

Defaultnya **false**.

**Mengembalikan:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Menunjukkan apakah teks harus di rasterisasi sebagai bitmap dan disimpan ke PDF ketika font tidak mendukung gaya tebal. Pendekatan ini dapat meningkatkan kualitas teks dalam PDF yang dihasilkan untuk font tertentu. Baca/tulis boolean.

--------------------

Defaultnya **false**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Mengembalikan atau mengatur nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF. Baca/tulis byte.

--------------------

Berpengaruh hanya ketika dokumen berisi gambar JPEG.

Gunakan properti ini untuk mendapatkan atau mengatur kualitas gambar dalam dokumen ketika menyimpan dalam format PDF. Nilai dapat bervariasi antara 0 hingga 100, di mana 0 berarti kualitas terburuk tetapi kompresi maksimum dan 100 berarti kualitas terbaik tetapi kompresi minimum.

Nilai default adalah **100**.

**Mengembalikan:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Mengembalikan atau mengatur nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF. Baca/tulis byte.

--------------------

Berpengaruh hanya ketika dokumen berisi gambar JPEG.

Gunakan properti ini untuk mendapatkan atau mengatur kualitas gambar dalam dokumen ketika menyimpan dalam format PDF. Nilai dapat bervariasi antara 0 hingga 100, di mana 0 berarti kualitas terburuk tetapi kompresi maksimum dan 100 berarti kualitas terbaik tetapi kompresi minimum.

Nilai default adalah **100**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

Level kepatuhan yang diinginkan untuk dokumen PDF yang dihasilkan. Baca/tulis [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Defaultnya [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Mengembalikan:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Level kepatuhan yang diinginkan untuk dokumen PDF yang dihasilkan. Baca/tulis [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Defaultnya [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Menetapkan kata sandi pengguna untuk melindungi dokumen PDF. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Menetapkan kata sandi pengguna untuk melindungi dokumen PDF. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Berisi seperangkat flag yang menentukan izin akses mana yang harus diberikan saat dokumen dibuka dengan akses pengguna. Lihat [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Mengembalikan:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

Berisi seperangkat flag yang menentukan izin akses mana yang harus diberikan saat dokumen dibuka dengan akses pengguna. Lihat [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

Benar untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Baca/tulis boolean.

--------------------

Defaultnya **true**. Dokumen Pdf dapat berisi grafik vektor dan gambar raster. Jika SaveMetafilesAsPng diatur ke true maka gambar Metafile sumber akan dikonversi ke format Png dan disimpan ke Pdf sebagai gambar raster. Jika SaveMetafilesAsPng diatur ke false maka Metafile sumber akan dikonversi ke grafik vektor Pdf. Setiap pendekatan memiliki kelebihan dan kekurangan. Misalnya, jika Metafile dikonversi ke PNG, maka beberapa kehilangan kualitas mungkin terjadi selama penskalaan dokumen yang dihasilkan. Jika Metafile dikonversi ke grafik vektor Pdf, maka masalah kinerja pada penampil Pdf mungkin terjadi.

**Mengembalikan:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Benar untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Baca/tulis boolean.

--------------------

Defaultnya **true**. Dokumen Pdf dapat berisi grafik vektor dan gambar raster. Jika SaveMetafilesAsPng diatur ke true maka gambar Metafile sumber akan dikonversi ke format Png dan disimpan ke Pdf sebagai gambar raster. Jika SaveMetafilesAsPng diatur ke false maka Metafile sumber akan dikonversi ke grafik vektor Pdf. Setiap pendekatan memiliki kelebihan dan kekurangan. Misalnya, jika Metafile dikonversi ke PNG, maka beberapa kehilangan kualitas mungkin terjadi selama penskalaan dokumen yang dihasilkan. Jika Metafile dikonversi ke grafik vektor Pdf, maka masalah kinerja pada penampil Pdf mungkin terjadi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Mengembalikan atau mengatur nilai yang menentukan resolusi gambar dalam dokumen PDF. Baca/tulis float.

Nilai: Efek parameter ini bergantung pada beberapa faktor. Algoritma berupaya mendapatkan ukuran gambar keluaran terbaik berdasarkan nilai properti, ukuran gambar sumber, dan ukuran bingkai gambar. Penggunaan nilai properti yang serupa dapat memberi hasil yang sama. Disarankan menggunakan langkah 16 atau 32 untuk melihat efek yang terlihat.

--------------------

Properti memengaruhi ukuran file, waktu ekspor, dan kualitas gambar.

Nilai default adalah **96**.

**Mengembalikan:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Mengembalikan atau mengatur nilai yang menentukan resolusi gambar dalam dokumen PDF. Baca/tulis float.

Nilai: Efek parameter ini bergantung pada beberapa faktor. Algoritma berupaya mendapatkan ukuran gambar keluaran terbaik berdasarkan nilai properti, ukuran gambar sumber, dan ukuran bingkai gambar. Penggunaan nilai properti yang serupa dapat memberi hasil yang sama. Disarankan menggunakan langkah 16 atau 32 untuk melihat efek yang terlihat.

--------------------

Properti memengaruhi ukuran file, waktu ekspor, dan kualitas gambar.

Nilai default adalah **96**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

Benar untuk menggambar bingkai hitam di sekitar setiap slide. Baca/tulis boolean.

--------------------

Defaultnya **false**.

**Mengembalikan:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Benar untuk menggambar bingkai hitam di sekitar setiap slide. Baca/tulis boolean.

--------------------

Defaultnya **false**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

Mendapatkan atau mengatur warna transparan gambar.

Nilai: Warna transparan gambar.

**Mengembalikan:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

Mendapatkan atau mengatur warna transparan gambar.

Nilai: Warna transparan gambar.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Menerapkan warna transparan yang ditentukan ke gambar jika true.

**Mengembalikan:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Menerapkan warna transparan yang ditentukan ke gambar jika true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Benar untuk mengonversi semua data OLE dari presentasi menjadi file tersemat dalam PDF yang dihasilkan. Baca/tulis  boolean .

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Defaultnya **false**.

**Mengembalikan:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

Benar untuk mengonversi semua data OLE dari presentasi menjadi file tersemat dalam PDF yang dihasilkan. Baca/tulis  boolean .

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Defaultnya **false**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |