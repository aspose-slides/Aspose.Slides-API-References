---
title: IPdfOptions
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format PDF.
type: docs
url: /id/com.aspose.slides/ipdfoptions/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format PDF.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Menentukan jenis kompresi yang akan digunakan untuk semua konten teks dalam dokumen. |
| [setTextCompression(int value)](#setTextCompression-int-) | Menentukan jenis kompresi yang akan digunakan untuk semua konten teks dalam dokumen. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Menunjukkan apakah kompresi paling efektif (bukan yang default) untuk setiap gambar harus dipilih secara otomatis. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Menunjukkan apakah kompresi paling efektif (bukan yang default) untuk setiap gambar harus dipilih secara otomatis. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True untuk menyematkan font true type untuk karakter ASCII 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True untuk menyematkan font true type untuk karakter ASCII 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Mengembalikan atau menetapkan array nama keluarga font yang didefinisikan pengguna yang harus dianggap umum oleh Aspose.Slides. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Menentukan apakah semua karakter font harus disematkan atau hanya subset yang digunakan. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Menentukan apakah semua karakter font harus disematkan atau hanya subset yang digunakan. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Menunjukkan apakah teks harus dirasterisasi sebagai bitmap dan disimpan ke PDF ketika font tidak mendukung gaya tebal. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Menunjukkan apakah teks harus dirasterisasi sebagai bitmap dan disimpan ke PDF ketika font tidak mendukung gaya tebal. |
| [getJpegQuality()](#getJpegQuality--) | Mengembalikan atau menetapkan nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Mengembalikan atau menetapkan nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF. |
| [getCompliance()](#getCompliance--) | Tingkat kepatuhan yang diinginkan untuk dokumen PDF yang dihasilkan. |
| [setCompliance(int value)](#setCompliance-int-) | Tingkat kepatuhan yang diinginkan untuk dokumen PDF yang dihasilkan. |
| [getPassword()](#getPassword--) | Menetapkan kata sandi pengguna untuk melindungi dokumen PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Menetapkan kata sandi pengguna untuk melindungi dokumen PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Berisi sekumpulan flag yang menentukan izin akses mana yang harus diberikan ketika dokumen dibuka dengan akses pengguna. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Berisi sekumpulan flag yang menentukan izin akses mana yang harus diberikan ketika dokumen dibuka dengan akses pengguna. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Mengembalikan atau menetapkan nilai yang menentukan resolusi gambar dalam dokumen PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Mengembalikan atau menetapkan nilai yang menentukan resolusi gambar dalam dokumen PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True untuk menggambar bingkai hitam di sekitar setiap slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True untuk menggambar bingkai hitam di sekitar setiap slide. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Mendapatkan atau menetapkan mode dimana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Mendapatkan atau menetapkan mode dimana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Mendapatkan atau menetapkan warna transparan gambar. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Mendapatkan atau menetapkan warna transparan gambar. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Menerapkan warna transparan yang ditentukan ke gambar jika true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Menerapkan warna transparan yang ditentukan ke gambar jika true. |
| [getInkOptions()](#getInkOptions--) | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. |
| [getIncludeOleData()](#getIncludeOleData--) | True untuk mengonversi semua data OLE dari presentasi menjadi file tersemat dalam PDF yang dihasilkan. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True untuk mengonversi semua data OLE dari presentasi menjadi file tersemat dalam PDF yang dihasilkan. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Menentukan jenis kompresi yang akan digunakan untuk semua konten teks dalam dokumen. Baca/tulis [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Default is [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Mengembalikan:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Menentukan jenis kompresi yang akan digunakan untuk semua konten teks dalam dokumen. Baca/tulis [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Default is [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Menunjukkan apakah kompresi paling efektif (bukan yang default) untuk setiap gambar harus dipilih secara otomatis. Jika diatur ke true, untuk setiap gambar dalam presentasi algoritma kompresi yang paling tepat akan dipilih, yang akan menghasilkan ukuran PDF yang lebih kecil.

--------------------

Pemilihan rasio kompresi gambar terbaik memerlukan komputasi yang mahal dan membutuhkan tambahan RAM, dan opsi ini bernilai false secara default.

--------------------

Default is false.

**Mengembalikan:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Menunjukkan apakah kompresi paling efektif (bukan yang default) untuk setiap gambar harus dipilih secara otomatis. Jika diatur ke true, untuk setiap gambar dalam presentasi algoritma kompresi yang paling tepat akan dipilih, yang akan menghasilkan ukuran PDF yang lebih kecil.

--------------------

Pemilihan rasio kompresi gambar terbaik memerlukan komputasi yang mahal dan membutuhkan tambahan RAM, dan opsi ini bernilai false secara default.

--------------------

Default is false.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

True untuk menyematkan font true type untuk karakter ASCII 32-127. Font untuk kode karakter lebih dari 127 selalu disematkan. Baca/tulis boolean.

--------------------

Default is **true**.

**Mengembalikan:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True untuk menyematkan font true type untuk karakter ASCII 32-127. Font untuk kode karakter lebih dari 127 selalu disematkan. Baca/tulis boolean.

--------------------

Default is **true**.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah false.

**Mengembalikan:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah false.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Mengembalikan atau menetapkan array nama keluarga font yang didefinisikan pengguna yang harus dianggap umum oleh Aspose.Slides. Baca/tulis String[].

**Mengembalikan:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Mengembalikan atau menetapkan array nama keluarga font yang didefinisikan pengguna yang harus dianggap umum oleh Aspose.Slides. Baca/tulis String[].

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Menentukan apakah semua karakter font harus disematkan atau hanya subset yang digunakan. Baca/tulis boolean.

--------------------

Default is **false**.

**Mengembalikan:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Menentukan apakah semua karakter font harus disematkan atau hanya subset yang digunakan. Baca/tulis boolean.

--------------------

Default is **false**.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Menunjukkan apakah teks harus dirasterisasi sebagai bitmap dan disimpan ke PDF ketika font tidak mendukung gaya tebal. Pendekatan ini dapat meningkatkan kualitas teks dalam PDF yang dihasilkan untuk font tertentu. Baca/tulis boolean.

--------------------

Default is **false**.

**Mengembalikan:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Menunjukkan apakah teks harus dirasterisasi sebagai bitmap dan disimpan ke PDF ketika font tidak mendukung gaya tebal. Pendekatan ini dapat meningkatkan kualitas teks dalam PDF yang dihasilkan untuk font tertentu. Baca/tulis boolean.

--------------------

Default is **false**.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Mengembalikan atau menetapkan nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF. Baca/tulis byte.

--------------------

Berpengaruh hanya ketika dokumen berisi gambar JPEG.

Gunakan properti ini untuk mendapatkan atau mengatur kualitas gambar dalam dokumen saat menyimpan dalam format PDF. Nilai dapat berkisar antara 0 hingga 100 dimana 0 berarti kualitas terburuk tetapi kompresi maksimum dan 100 berarti kualitas terbaik tetapi kompresi minimum.

Nilai default adalah **100**.

**Mengembalikan:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Mengembalikan atau menetapkan nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF. Baca/tulis byte.

--------------------

Berpengaruh hanya ketika dokumen berisi gambar JPEG.

Gunakan properti ini untuk mendapatkan atau mengatur kualitas gambar dalam dokumen saat menyimpan dalam format PDF. Nilai dapat berkisar antara 0 hingga 100 dimana 0 berarti kualitas terburuk tetapi kompresi maksimum dan 100 berarti kualitas terbaik tetapi kompresi minimum.

Nilai default adalah **100**.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Tingkat kepatuhan yang diinginkan untuk dokumen PDF yang dihasilkan. Baca/tulis [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Default is [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Mengembalikan:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Tingkat kepatuhan yang diinginkan untuk dokumen PDF yang dihasilkan. Baca/tulis [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Default is [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Menetapkan kata sandi pengguna untuk melindungi dokumen PDF. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Menetapkan kata sandi pengguna untuk melindungi dokumen PDF. Baca/tulis String.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Berisi sekumpulan flag yang menentukan izin akses mana yang harus diberikan ketika dokumen dibuka dengan akses pengguna. Lihat [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract void setAccessPermissions(int value)
```

Berisi sekumpulan flag yang menentukan izin akses mana yang harus diberikan ketika dokumen dibuka dengan akses pengguna. Lihat [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Baca/tulis boolean.

--------------------

Default adalah **true**. Dokumen PDF dapat berisi grafik vektor dan gambar raster. Jika SaveMetafilesAsPng diatur ke true maka gambar Metafile sumber dikonversi ke format Png dan disimpan ke Pdf sebagai gambar raster. Jika SaveMetafilesAsPng diatur ke false maka Metafile sumber dikonversi ke grafik vektor Pdf. Setiap pendekatan memiliki kelebihan dan kekurangan. Misalnya, jika Metafile dikonversi ke PNG, maka beberapa kehilangan kualitas dapat terjadi selama penskalaan dokumen yang dihasilkan. Jika Metafile dikonversi ke grafik vektor Pdf, maka masalah performa pada alat penampil Pdf mungkin terjadi.

**Mengembalikan:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Baca/tulis boolean.

--------------------

Default adalah **true**. Dokumen PDF dapat berisi grafik vektor dan gambar raster. Jika SaveMetafilesAsPng diatur ke true maka gambar Metafile sumber dikonversi ke format Png dan disimpan ke Pdf sebagai gambar raster. Jika SaveMetafilesAsPng diatur ke false maka Metafile sumber dikonversi ke grafik vektor Pdf. Setiap pendekatan memiliki kelebihan dan kekurangan. Misalnya, jika Metafile dikonversi ke PNG, maka beberapa kehilangan kualitas dapat terjadi selama penskalaan dokumen yang dihasilkan. Jika Metafile dikonversi ke grafik vektor Pdf, maka masalah performa pada alat penampil Pdf mungkin terjadi.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Mengembalikan atau menetapkan nilai yang menentukan resolusi gambar dalam dokumen PDF. Baca/tulis float.

Nilai: Efek parameter ini bergantung pada beberapa faktor. Algoritma berusaha mendapatkan ukuran gambar keluaran terbaik berdasarkan nilai properti, ukuran gambar sumber, dan ukuran bingkai gambar. Penggunaan nilai properti yang serupa dapat memberikan hasil yang sama. Direkomendasikan menggunakan langkah 16 atau 32 untuk memperoleh efek yang terlihat.

Properti memengaruhi ukuran file, waktu ekspor, dan kualitas gambar.

Nilai default adalah **96**.

**Mengembalikan:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Mengembalikan atau menetapkan nilai yang menentukan resolusi gambar dalam dokumen PDF. Baca/tulis float.

Nilai: Efek parameter ini bergantung pada beberapa faktor. Algoritma berusaha mendapatkan ukuran gambar keluaran terbaik berdasarkan nilai properti, ukuran gambar sumber, dan ukuran bingkai gambar. Penggunaan nilai properti yang serupa dapat memberikan hasil yang sama. Direkomendasikan menggunakan langkah 16 atau 32 untuk memperoleh efek yang terlihat.

Properti memengaruhi ukuran file, waktu ekspor, dan kualitas gambar.

Nilai default adalah **96**.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True untuk menggambar bingkai hitam di sekitar setiap slide. Baca/tulis boolean.

--------------------

Default is **false**.

**Mengembalikan:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True untuk menggambar bingkai hitam di sekitar setiap slide. Baca/tulis boolean.

--------------------

Default is **false**.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Mendapatkan atau menetapkan mode dimana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Mendapatkan atau menetapkan mode dimana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

Mendapatkan atau menetapkan warna transparan gambar.

Nilai: Warna transparan gambar.

**Mengembalikan:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

Mendapatkan atau menetapkan warna transparan gambar.

Nilai: Warna transparan gambar.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Menerapkan warna transparan yang ditentukan ke gambar jika true.

**Mengembalikan:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Menerapkan warna transparan yang ditentukan ke gambar jika true.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. Baca-saja [IInkOptions](../../com.aspose.slides/iinkoptions)

**Mengembalikan:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

True untuk mengonversi semua data OLE dari presentasi menjadi file tersemat dalam PDF yang dihasilkan. Baca/tulis boolean.

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
>      if (pres != null) presentation.dispose();
>  }
> ```

--------------------

Default is  **false** .

**Mengembalikan:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

True untuk mengonversi semua data OLE dari presentasi menjadi file tersemat dalam PDF yang dihasilkan. Baca/tulis boolean.

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

Default is  **false** .

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |