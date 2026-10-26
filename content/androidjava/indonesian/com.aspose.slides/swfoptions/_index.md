---
title: SwfOptions
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format Swf.
type: docs
url: /id/com.aspose.slides/swfoptions/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format Swf.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Saving presentation and notes pages
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Konstruktor default. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [getCompressed()](#getCompressed--) | Menentukan apakah dokumen SWF yang dihasilkan harus dikompresi atau tidak. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Menentukan apakah dokumen SWF yang dihasilkan harus dikompresi atau tidak. |
| [getViewerIncluded()](#getViewerIncluded--) | Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. |
| [getShowPageBorder()](#getShowPageBorder--) | Menentukan apakah batas di sekitar halaman harus ditampilkan. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Menentukan apakah batas di sekitar halaman harus ditampilkan. |
| [getShowFullScreen()](#getShowFullScreen--) | Tampilkan/sembunyikan tombol layar penuh. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Tampilkan/sembunyikan tombol layar penuh. |
| [getShowPageStepper()](#getShowPageStepper--) | Tampilkan/sembunyikan pengatur langkah halaman. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Tampilkan/sembunyikan pengatur langkah halaman. |
| [getShowSearch()](#getShowSearch--) | Tampilkan/sembunyikan bagian pencarian. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Tampilkan/sembunyikan bagian pencarian. |
| [getShowTopPane()](#getShowTopPane--) | Tampilkan/sembunyikan seluruh panel atas. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Tampilkan/sembunyikan seluruh panel atas. |
| [getShowBottomPane()](#getShowBottomPane--) | Tampilkan/sembunyikan panel bawah. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Tampilkan/sembunyikan panel bawah. |
| [getShowLeftPane()](#getShowLeftPane--) | Tampilkan/sembunyikan panel kiri. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Tampilkan/sembunyikan panel kiri. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Mulai dengan panel kiri terbuka. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Mulai dengan panel kiri terbuka. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Aktifkan/nonaktifkan menu konteks. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Aktifkan/nonaktifkan menu konteks. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. |
| [getLogoLink()](#getLogoLink--) | Mendapatkan atau mengatur alamat hyperlink lengkap untuk logo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Mendapatkan atau mengatur alamat hyperlink lengkap untuk logo. |
| [getJpegQuality()](#getJpegQuality--) | Menentukan kualitas gambar JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Menentukan kualitas gambar JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Mendapatkan atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Mendapatkan atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```


Konstruktor default.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Bawaan adalah false.

**Mengembalikan:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Bawaan adalah false.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```


Menentukan apakah dokumen SWF yang dihasilkan harus dikompresi atau tidak. Bawaan adalah true.

**Mengembalikan:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```


Menentukan apakah dokumen SWF yang dihasilkan harus dikompresi atau tidak. Bawaan adalah true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```


Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. Bawaan adalah true.

**Mengembalikan:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```


Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. Bawaan adalah true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```


Menentukan apakah batas di sekitar halaman harus ditampilkan. Bawaan adalah true.

**Mengembalikan:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```


Menentukan apakah batas di sekitar halaman harus ditampilkan. Bawaan adalah true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```


Tampilkan/sembunyikan tombol layar penuh. Dapat ditimpa dalam flashvars. Bawaan adalah true.

**Mengembalikan:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```


Tampilkan/sembunyikan tombol layar penuh. Dapat ditimpa dalam flashvars. Bawaan adalah true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```


Tampilkan/sembunyikan pengatur langkah halaman. Dapat ditimpa dalam flashvars. Bawaan adalah true.

**Mengembalikan:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```


Tampilkan/sembunyikan pengatur langkah halaman. Dapat ditimpa dalam flashvars. Bawaan adalah true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```


Tampilkan/sembunyikan bagian pencarian. Dapat ditimpa dalam flashvars. Bawaan adalah true.

**Mengembalikan:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```


Tampilkan/sembunyikan bagian pencarian. Dapat ditimpa dalam flashvars. Bawaan adalah true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```


Tampilkan/sembunyikan seluruh panel atas. Dapat ditimpa dalam flashvars. Bawaan adalah true.

**Mengembalikan:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```


Tampilkan/sembunyikan seluruh panel atas. Dapat ditimpa dalam flashvars. Bawaan adalah true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```


Tampilkan/sembunyikan panel bawah. Dapat ditimpa dalam flashvars. Bawaan adalah true.

**Mengembalikan:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```


Tampilkan/sembunyikan panel bawah. Dapat ditimpa dalam flashvars. Bawaan adalah true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```


Tampilkan/sembunyikan panel kiri. Dapat ditimpa dalam flashvars. Bawaan adalah true.

**Mengembalikan:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```


Tampilkan/sembunyikan panel kiri. Dapat ditimpa dalam flashvars. Bawaan adalah true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```


Mulai dengan panel kiri terbuka. Dapat ditimpa dalam flashvars. Bawaan adalah false.

**Mengembalikan:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```


Mulai dengan panel kiri terbuka. Dapat ditimpa dalam flashvars. Bawaan adalah false.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```


Aktifkan/nonaktifkan menu konteks. Bawaan adalah true.

**Mengembalikan:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```


Aktifkan/nonaktifkan menu konteks. Bawaan adalah true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```


Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. Gambar harus berukuran 32x64 piksel PNG, jika tidak logo dapat ditampilkan tidak semestinya.

**Mengembalikan:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```


Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. Gambar harus berukuran 32x64 piksel PNG, jika tidak logo dapat ditampilkan tidak semestinya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```


Mendapatkan atau mengatur alamat hyperlink lengkap untuk logo. Memiliki efek hanya jika (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) ditentukan.

**Mengembalikan:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```


Mendapatkan atau mengatur alamat hyperlink lengkap untuk logo. Memiliki efek hanya jika (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```


Menentukan kualitas gambar JPEG. Bawaan adalah 95.

**Mengembalikan:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```


Menentukan kualitas gambar JPEG. Bawaan adalah 95.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Mendapatkan atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Properti ini tidak mendukung penetapan objek tipe [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
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


Mendapatkan atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Properti ini tidak mendukung penetapan objek tipe [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |