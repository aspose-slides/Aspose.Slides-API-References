---
title: MarkdownSaveOptions
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili opsi yang mengontrol bagaimana presentasi harus disimpan ke markdown.
type: docs
url: /id/com.aspose.slides/markdownsaveoptions/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Mewakili opsi yang mengontrol bagaimana presentasi disimpan ke markdown.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Ctor. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getExportType()](#getExportType--) | Menentukan spesifikasi markdown untuk mengonversi presentasi. |
| [setExportType(int value)](#setExportType-int-) | Menentukan spesifikasi markdown untuk mengonversi presentasi. |
| [getBasePath()](#getBasePath--) | Menentukan jalur dasar tempat dokumen dengan sumber daya akan disimpan. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Menentukan jalur dasar tempat dokumen dengan sumber daya akan disimpan. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Menentukan nama folder untuk menyimpan gambar. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Menentukan nama folder untuk menyimpan gambar. |
| [getNewLineType()](#getNewLineType--) | Menentukan apakah dokumen yang dihasilkan harus memiliki baris baru \\r(Macintosh) atau \\n(Unix) atau \\r\\n(Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Menentukan apakah dokumen yang dihasilkan harus memiliki baris baru \\r(Macintosh) atau \\n(Unix) atau \\r\\n(Windows). |
| [getShowComments()](#getShowComments--) | Menentukan apakah dokumen yang dihasilkan harus menampilkan komentar atau tidak. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Menentukan apakah dokumen yang dihasilkan harus menampilkan komentar atau tidak. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Menentukan apakah dokumen yang dihasilkan harus menampilkan nomor setiap slide atau tidak. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Menentukan apakah dokumen yang dihasilkan harus menampilkan nomor setiap slide atau tidak. |
| [getFlavor()](#getFlavor--) | Menentukan spesifikasi markdown untuk mengonversi presentasi. |
| [setFlavor(int value)](#setFlavor-int-) | Menentukan spesifikasi markdown untuk mengonversi presentasi. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Mendapatkan atau mengatur string format yang digunakan untuk header nomor slide dalam output Markdown. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Mendapatkan atau mengatur string format yang digunakan untuk header nomor slide dalam output Markdown. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Menentukan bagaimana karakter spasi reguler yang berulang harus ditangani selama ekspor Markdown. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Menentukan bagaimana karakter spasi reguler yang berulang harus ditangani selama ekspor Markdown. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Jika diatur ke true, menghapus baris kosong atau hanya berisi spasi dari output Markdown akhir. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Jika diatur ke true, menghapus baris kosong atau hanya berisi spasi dari output Markdown akhir. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Terjadi untuk setiap gambar non-SVG (bitmap atau metafile) selama ekspor Markdown. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Terjadi untuk setiap gambar SVG selama ekspor Markdown. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Ctor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

Menentukan spesifikasi markdown untuk mengonversi presentasi. Default adalah TextOnly.

**Mengembalikan:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

Menentukan spesifikasi markdown untuk mengonversi presentasi. Default adalah TextOnly.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

Menentukan jalur dasar tempat dokumen dengan sumber daya akan disimpan. Default adalah direktori saat ini dari aplikasi.

**Mengembalikan:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

Menentukan jalur dasar tempat dokumen dengan sumber daya akan disimpan. Default adalah direktori saat ini dari aplikasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

Menentukan nama folder untuk menyimpan gambar. Default adalah Images.

**Mengembalikan:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

Menentukan nama folder untuk menyimpan gambar. Default adalah Images.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

Menentukan apakah dokumen yang dihasilkan harus memiliki baris baru \\r(Macintosh) atau \\n(Unix) atau \\r\\n(Windows). Default adalah Unix.

**Mengembalikan:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

Menentukan apakah dokumen yang dihasilkan harus memiliki baris baru \\r(Macintosh) atau \\n(Unix) atau \\r\\n(Windows). Default adalah Unix.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

Menentukan apakah dokumen yang dihasilkan harus menampilkan komentar atau tidak. Default adalah false.

**Mengembalikan:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

Menentukan apakah dokumen yang dihasilkan harus menampilkan komentar atau tidak. Default adalah false.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah false.

**Mengembalikan:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah false.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

Menentukan apakah dokumen yang dihasilkan harus menampilkan nomor setiap slide atau tidak. Default adalah false.

**Mengembalikan:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

Menentukan apakah dokumen yang dihasilkan harus menampilkan nomor setiap slide atau tidak. Default adalah false.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

Menentukan spesifikasi markdown untuk mengonversi presentasi. Default adalah Multi-markdown.

**Mengembalikan:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

Menentukan spesifikasi markdown untuk mengonversi presentasi. Default adalah Multi-markdown.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

Mendapatkan atau mengatur string format yang digunakan untuk header nomor slide dalam output Markdown. Format harus menyertakan placeholder "\{0\}", yang akan digantikan dengan indeks slide saat ekspor. Contoh: "\# Slide \{0\}" akan menghasilkan "\# Slide 1", "\# Slide 2", dll.

**Mengembalikan:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

Mendapatkan atau mengatur string format yang digunakan untuk header nomor slide dalam output Markdown. Format harus menyertakan placeholder "\{0\}", yang akan digantikan dengan indeks slide saat ekspor. Contoh: "\# Slide \{0\}" akan menghasilkan "\# Slide 1", "\# Slide 2", dll.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

Menentukan bagaimana karakter spasi reguler yang berulang harus ditangani selama ekspor Markdown. Properti ini mendefinisikan apakah spasi berurutan:
- dipertahankan sebagai karakter spasi reguler,
- bergantian antara spasi reguler dan entitas non-breaking space (�),
- atau sepenuhnya digantikan (setelah spasi pertama) dengan non-breaking space untuk mempertahankan penyelarasan visual dalam output Markdown. Nilai default adalah [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Mengembalikan:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

Menentukan bagaimana karakter spasi reguler yang berulang harus ditangani selama ekspor Markdown. Properti ini mendefinisikan apakah spasi berurutan:
- dipertahankan sebagai karakter spasi reguler,
- bergantian antara spasi reguler dan entitas non-breaking space (�),
- atau sepenuhnya digantikan (setelah spasi pertama) dengan non-breaking space untuk mempertahankan penyelarasan visual dalam output Markdown. Nilai default adalah [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

Jika diatur ke true, menghapus baris kosong atau hanya berisi spasi dari output Markdown akhir. Default adalah false.

**Mengembalikan:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

Jika diatur ke true, menghapus baris kosong atau hanya berisi spasi dari output Markdown akhir. Default adalah false.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

Terjadi untuk setiap gambar non-SVG (bitmap atau metafile) selama ekspor Markdown. Memungkinkan penyesuaian cara gambar disimpan dan direferensikan. Jika tidak ditangani, gambar disimpan secara lokal dengan tautan relatif.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Peristiwa penyimpanan gambar Markdown. |
### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

Terjadi untuk setiap gambar SVG selama ekspor Markdown. Memungkinkan mengganti penyimpanan dan pembuatan tautan default. Jika tidak ditangani, SVG disimpan secara lokal dengan tautan relatif.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Peristiwa penyimpanan gambar SVG Markdown. |