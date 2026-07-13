---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Opsi untuk mengekstrak HTML dari teks Pptx.
type: docs
url: /id/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Opsi untuk mengekstrak HTML dari teks Pptx.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Mengembalikan atau mengatur nilai, yang menunjukkan apakah header Clipboard harus ditambahkan. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Mengembalikan atau mengatur nilai, yang menunjukkan apakah header Clipboard harus ditambahkan. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Mengembalikan atau mengatur kedalaman pewarisan untuk properti teks. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Mengembalikan atau mengatur kedalaman pewarisan untuk properti teks. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Mengembalikan atau mengatur objek callback yang mengontrol bagaimana objek eksternal akan disimpan. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Mengembalikan atau mengatur objek callback yang mengontrol bagaimana objek eksternal akan disimpan. |
| [getEncodingName()](#getEncodingName--) | Mengembalikan atau mengatur nama pengkodean html. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Mengembalikan atau mengatur nama pengkodean html. |

### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

Mengembalikan atau mengatur nilai, yang menunjukkan apakah header Clipboard harus ditambahkan. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

Mengembalikan atau mengatur nilai, yang menunjukkan apakah header Clipboard harus ditambahkan. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

Mengembalikan atau mengatur kedalaman pewarisan untuk properti teks. Baca/tulis [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Mengembalikan:**
int

### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

Mengembalikan atau mengatur kedalaman pewarisan untuk properti teks. Baca/tulis [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

Mengembalikan atau mengatur objek callback yang mengontrol bagaimana objek eksternal akan disimpan. Baca/tulis [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Mengembalikan:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)

### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

Mengembalikan atau mengatur objek callback yang mengontrol bagaimana objek eksternal akan disimpan. Baca/tulis [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

Mengembalikan atau mengatur nama pengkodean html. Nilai ini akan disimpan ke file HTML yang dihasilkan, tetapi terserah pemanggil untuk memastikan file disimpan dalam pengkodean ini. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

Mengembalikan atau mengatur nama pengkodean html. Nilai ini akan disimpan ke file HTML yang dihasilkan, tetapi terserah pemanggil untuk memastikan file disimpan dalam pengkodean ini. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |