---
title: SwfOptions
second_title: Referensi API Aspose.Slides untuk Java
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
>  // Membuat objek Presentation yang mewakili file presentasi
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Menyimpan presentasi dan halaman catatan
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
| [getShowFullScreen()](#getShowFullScreen--) | Menampilkan/menyembunyikan tombol layar penuh. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Menampilkan/menyembunyikan tombol layar penuh. |
| [getShowPageStepper()](#getShowPageStepper--) | Menampilkan/menyembunyikan penggerak halaman. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Menampilkan/menyembunyikan penggerak halaman. |
| [getShowSearch()](#getShowSearch--) | Menampilkan/menyembunyikan bagian pencarian. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Menampilkan/menyembunyikan bagian pencarian. |
| [getShowTopPane()](#getShowTopPane--) | Menampilkan/menyembunyikan seluruh panel atas. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Menampilkan/menyembunyikan seluruh panel atas. |
| [getShowBottomPane()](#getShowBottomPane--) | Menampilkan/menyembunyikan panel bawah. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Menampilkan/menyembunyikan panel bawah. |
| [getShowLeftPane()](#getShowLeftPane--) | Menampilkan/menyembunyikan panel kiri. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Menampilkan/menyembunyikan panel kiri. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Mulai dengan panel kiri terbuka. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Mulai dengan panel kiri terbuka. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Mengaktifkan/menonaktifkan menu konteks. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Mengaktifkan/menonaktifkan menu konteks. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. |
| [getLogoLink()](#getLogoLink--) | Mendapatkan atau mengatur alamat hyperlink lengkap untuk logo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Mendapatkan atau mengatur alamat hyperlink lengkap untuk logo. |
| [getJpegQuality()](#getJpegQuality--) | Menentukan kualitas gambar JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Menentukan kualitas gambar JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Mendapatkan atau mengatur mode di mana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Mendapatkan atau mengatur mode di mana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

Konstruktor default.

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

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

Menentukan apakah dokumen SWF yang dihasilkan harus dikompresi atau tidak. Defaultnya true.

**Mengembalikan:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

Menentukan apakah dokumen SWF yang dihasilkan harus dikompresi atau tidak. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. Defaultnya true.

**Mengembalikan:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

Menentukan apakah batas di sekitar halaman harus ditampilkan. Defaultnya true.

**Mengembalikan:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

Menentukan apakah batas di sekitar halaman harus ditampilkan. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

Menampilkan/menyembunyikan tombol layar penuh. Dapat ditimpa dalam flashvars. Defaultnya true.

**Mengembalikan:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

Menampilkan/menyembunyikan tombol layar penuh. Dapat ditimpa dalam flashvars. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

Menampilkan/menyembunyikan penggerak halaman. Dapat ditimpa dalam flashvars. Defaultnya true.

**Mengembalikan:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

Menampilkan/menyembunyikan penggerak halaman. Dapat ditimpa dalam flashvars. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

Menampilkan/menyembunyikan bagian pencarian. Dapat ditimpa dalam flashvars. Defaultnya true.

**Mengembalikan:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

Menampilkan/menyembunyikan bagian pencarian. Dapat ditimpa dalam flashvars. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

Menampilkan/menyembunyikan seluruh panel atas. Dapat ditimpa dalam flashvars. Defaultnya true.

**Mengembalikan:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

Menampilkan/menyembunyikan seluruh panel atas. Dapat ditimpa dalam flashvars. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

Menampilkan/menyembunyikan panel bawah. Dapat ditimpa dalam flashvars. Defaultnya true.

**Mengembalikan:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

Menampilkan/menyembunyikan panel bawah. Dapat ditimpa dalam flashvars. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

Menampilkan/menyembunyikan panel kiri. Dapat ditimpa dalam flashvars. Defaultnya true.

**Mengembalikan:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

Menampilkan/menyembunyikan panel kiri. Dapat ditimpa dalam flashvars. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

Mulai dengan panel kiri terbuka. Dapat ditimpa dalam flashvars. Defaultnya false.

**Mengembalikan:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

Mulai dengan panel kiri terbuka. Dapat ditimpa dalam flashvars. Defaultnya false.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

Mengaktifkan/menonaktifkan menu konteks. Defaultnya true.

**Mengembalikan:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```

Mengaktifkan/menonaktifkan menu konteks. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```

Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. Gambar harus berukuran 32x64 piksel PNG, jika tidak logo dapat ditampilkan tidak tepat.

**Mengembalikan:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. Gambar harus berukuran 32x64 piksel PNG, jika tidak logo dapat ditampilkan tidak tepat.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

Mendapatkan atau mengatur alamat hyperlink lengkap untuk logo. Berpengaruh hanya jika (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) ditentukan.

**Mengembalikan:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

Mendapatkan atau mengatur alamat hyperlink lengkap untuk logo. Berpengaruh hanya jika (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Menentukan kualitas gambar JPEG. Defaultnya 95.

**Mengembalikan:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Menentukan kualitas gambar JPEG. Defaultnya 95.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Mendapatkan atau mengatur mode di mana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Properti ini tidak mendukung penetapan objek bertipe [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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

Mendapatkan atau mengatur mode di mana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Properti ini tidak mendukung penetapan objek bertipe [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

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