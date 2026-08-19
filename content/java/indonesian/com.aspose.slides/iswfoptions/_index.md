---
title: ISwfOptions
second_title: Referensi API Aspose.Slides untuk Java
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

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

Menentukan apakah dokumen SWF yang dihasilkan harus dikompresi atau tidak. Default adalah true.

**Mengembalikan:**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

Menentukan apakah dokumen SWF yang dihasilkan harus dikompresi atau tidak. Default adalah true.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. Default adalah true.

**Mengembalikan:**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. Default adalah true.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

Menentukan apakah batas di sekitar halaman harus ditampilkan. Default adalah true.

**Mengembalikan:**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

Menentukan apakah batas di sekitar halaman harus ditampilkan. Default adalah true.

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

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

Tampilkan/sembunyikan tombol layar penuh. Dapat ditimpa dalam flashvars. Default adalah true.

**Mengembalikan:**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

Tampilkan/sembunyikan tombol layar penuh. Dapat ditimpa dalam flashvars. Default adalah true.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

Tampilkan/sembunyikan pengatur langkah halaman. Dapat ditimpa dalam flashvars. Default adalah true.

**Mengembalikan:**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

Tampilkan/sembunyikan pengatur langkah halaman. Dapat ditimpa dalam flashvars. Default adalah true.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

Tampilkan/sembunyikan bagian pencarian. Dapat ditimpa dalam flashvars. Default adalah true.

**Mengembalikan:**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

Tampilkan/sembunyikan bagian pencarian. Dapat ditimpa dalam flashvars. Default adalah true.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

Tampilkan/sembunyikan seluruh panel atas. Dapat ditimpa dalam flashvars. Default adalah true.

**Mengembalikan:**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

Tampilkan/sembunyikan seluruh panel atas. Dapat ditimpa dalam flashvars. Default adalah true.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

Tampilkan/sembunyikan panel bawah. Dapat ditimpa dalam flashvars. Default adalah true.

**Mengembalikan:**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

Tampilkan/sembunyikan panel bawah. Dapat ditimpa dalam flashvars. Default adalah true.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

Tampilkan/sembunyikan panel kiri. Dapat ditimpa dalam flashvars. Default adalah true.

**Mengembalikan:**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

Tampilkan/sembunyikan panel kiri. Dapat ditimpa dalam flashvars. Default adalah true.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

Mulai dengan panel kiri terbuka. Dapat ditimpa dalam flashvars. Default adalah false.

**Mengembalikan:**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

Mulai dengan panel kiri terbuka. Dapat ditimpa dalam flashvars. Default adalah false.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

Aktifkan/nonaktifkan menu konteks. Default adalah true.

**Mengembalikan:**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

Aktifkan/nonaktifkan menu konteks. Default adalah true.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. Gambar harus berukuran 32x64 piksel PNG, jika tidak logo dapat ditampilkan secara tidak tepat.

**Mengembalikan:**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. Gambar harus berukuran 32x64 piksel PNG, jika tidak logo dapat ditampilkan secara tidak tepat.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

Mendapatkan atau mengatur alamat hyperlink lengkap untuk logo. Berpengaruh hanya jika (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) ditentukan.

**Mengembalikan:**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

Mendapatkan atau mengatur alamat hyperlink lengkap untuk logo. Berpengaruh hanya jika (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Menentukan kualitas gambar JPEG. Default adalah 95.

**Mengembalikan:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Menentukan kualitas gambar JPEG. Default adalah 95.

**Parameter:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |