---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Java API Reference
description: Options for extracting HTML from the Pptx text.
type: docs
url: /id/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Opsi untuk mengekstrak HTML dari teks Pptx.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Returns or sets value, indicating if Clipboard headers should be added. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Returns or sets value, indicating if Clipboard headers should be added. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Returns or sets inhering depth for text properties. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Returns or sets inhering depth for text properties. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Returns or sets a callback object which controlls how external object will be stored. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Returns or sets a callback object which controlls how external object will be stored. |
| [getEncodingName()](#getEncodingName--) | Returns or sets html encoding name. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Returns or sets html encoding name. |
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

Mengembalikan atau mengatur objek callback yang mengendalikan bagaimana objek eksternal akan disimpan. Baca/tulis [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Mengembalikan:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

Mengembalikan atau mengatur objek callback yang mengendalikan bagaimana objek eksternal akan disimpan. Baca/tulis [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

Mengembalikan atau mengatur nama encoding html. Nilai ini akan disimpan ke file HTML yang dihasilkan, tetapi terserah pemanggil untuk memastikan file disimpan dengan encoding ini. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

Mengembalikan atau mengatur nama encoding html. Nilai ini akan disimpan ke file HTML yang dihasilkan, tetapi terserah pemanggil untuk memastikan file disimpan dengan encoding ini. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |