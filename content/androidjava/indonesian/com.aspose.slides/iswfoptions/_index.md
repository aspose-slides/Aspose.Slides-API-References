---
title: ISwfOptions
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format SWF.
type: docs
url: /id/com.aspose.slides/iswfoptions/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format SWF.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCompressed()](#getCompressed--) | Menentukan apakah dokumen SWF yang dihasilkan harus dikompresi atau tidak. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Menentukan apakah dokumen SWF yang dihasilkan harus dikompresi atau tidak. |
| [getViewerIncluded()](#getViewerIncluded--) | Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. |
| [getShowPageBorder()](#getShowPageBorder--) | Menentukan apakah batas di sekitar halaman harus ditampilkan. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Menentukan apakah batas di sekitar halaman harus ditampilkan. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [getShowFullScreen()](#getShowFullScreen--) | Menampilkan/menyembunyikan tombol layar penuh. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Menampilkan/menyembunyikan tombol layar penuh. |
| [getShowPageStepper()](#getShowPageStepper--) | Menampilkan/menyembunyikan pengatur langkah halaman. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Menampilkan/menyembunyikan pengatur langkah halaman. |
| [getShowSearch()](#getShowSearch--) | Menampilkan/menyembunyikan bagian pencarian. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Menampilkan/menyembunyikan bagian pencarian. |
| [getShowTopPane()](#getShowTopPane--) | Menampilkan/menyembunyikan seluruh panel atas. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Menampilkan/menyembunyikan seluruh panel atas. |
| [getShowBottomPane()](#getShowBottomPane--) | Menampilkan/menyembunyikan panel bawah. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Menampilkan/menyembunyikan panel bawah. |
| [getShowLeftPane()](#getShowLeftPane--) | Menampilkan/menyembunyikan panel kiri. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Menampilkan/menyembunyikan panel kiri. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Memulai dengan panel kiri terbuka. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Memulai dengan panel kiri terbuka. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Mengaktifkan/menonaktifkan menu konteks. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Mengaktifkan/menonaktifkan menu konteks. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. |
| [getLogoLink()](#getLogoLink--) | Mendapatkan atau mengatur alamat hyperlink lengkap untuk logo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Mendapatkan atau mengatur alamat hyperlink lengkap untuk logo. |
| [getJpegQuality()](#getJpegQuality--) | Menentukan kualitas gambar JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Menentukan kualitas gambar JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Mendapatkan atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Mendapatkan atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

Menentukan apakah dokumen SWF yang dihasilkan harus dikompresi atau tidak. Defaultnya true.

**Mengembalikan:**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

Menentukan apakah dokumen SWF yang dihasilkan harus dikompresi atau tidak. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. Defaultnya true.

**Mengembalikan:**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

Menentukan apakah batas di sekitar halaman harus ditampilkan. Defaultnya true.

**Mengembalikan:**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

Menentukan apakah batas di sekitar halaman harus ditampilkan. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Defaultnya false.

**Mengembalikan:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Defaultnya false.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

Menampilkan/menyembunyikan tombol layar penuh. Dapat ditimpa dalam flashvars. Defaultnya true.

**Mengembalikan:**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

Menampilkan/menyembunyikan tombol layar penuh. Dapat ditimpa dalam flashvars. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

Menampilkan/menyembunyikan pengatur langkah halaman. Dapat ditimpa dalam flashvars. Defaultnya true.

**Mengembalikan:**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

Menampilkan/menyembunyikan pengatur langkah halaman. Dapat ditimpa dalam flashvars. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

Menampilkan/menyembunyikan bagian pencarian. Dapat ditimpa dalam flashvars. Defaultnya true.

**Mengembalikan:**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

Menampilkan/menyembunyikan bagian pencarian. Dapat ditimpa dalam flashvars. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

Menampilkan/menyembunyikan seluruh panel atas. Dapat ditimpa dalam flashvars. Defaultnya true.

**Mengembalikan:**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

Menampilkan/menyembunyikan seluruh panel atas. Dapat ditimpa dalam flashvars. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

Menampilkan/menyembunyikan panel bawah. Dapat ditimpa dalam flashvars. Defaultnya true.

**Mengembalikan:**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

Menampilkan/menyembunyikan panel bawah. Dapat ditimpa dalam flashvars. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

Menampilkan/menyembunyikan panel kiri. Dapat ditimpa dalam flashvars. Defaultnya true.

**Mengembalikan:**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

Menampilkan/menyembunyikan panel kiri. Dapat ditimpa dalam flashvars. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

Memulai dengan panel kiri terbuka. Dapat ditimpa dalam flashvars. Defaultnya false.

**Mengembalikan:**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

Memulai dengan panel kiri terbuka. Dapat ditimpa dalam flashvars. Defaultnya false.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

Mengaktifkan/menonaktifkan menu konteks. Defaultnya true.

**Mengembalikan:**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

Mengaktifkan/menonaktifkan menu konteks. Defaultnya true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. Gambar harus berupa PNG berukuran 32x64 piksel, jika tidak logo dapat ditampilkan secara tidak tepat.

**Mengembalikan:**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. Gambar harus berupa PNG berukuran 32x64 piksel, jika tidak logo dapat ditampilkan secara tidak tepat.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

Mendapatkan atau mengatur alamat hyperlink lengkap untuk logo. Memiliki efek hanya jika a (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) ditentukan.

**Mengembalikan:**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

Mendapatkan atau mengatur alamat hyperlink lengkap untuk logo. Memiliki efek hanya jika a (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Menentukan kualitas gambar JPEG. Defaultnya 95.

**Mengembalikan:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Menentukan kualitas gambar JPEG. Defaultnya 95.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Mendapatkan atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Properti ini tidak mendukung penugasan objek tipe [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Mendapatkan atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Properti ini tidak mendukung penugasan objek tipe [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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