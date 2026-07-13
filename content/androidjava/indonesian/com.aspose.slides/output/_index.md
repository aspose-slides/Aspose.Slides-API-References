---
title: Output
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili koleksi elemen output untuk IWebDocument.
type: docs
url: /id/com.aspose.slides/output/
---
**Pewarisan:**
java.lang.Object
```
public final class Output
```

Mewakili koleksi elemen output untuk IWebDocument.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Menambahkan elemen output untuk objek konteks. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Menambahkan elemen output untuk gambar. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Menambahkan elemen output untuk gambar. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Menambahkan elemen output untuk video. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Membuat dan menambahkan elemen file output untuk font yang ditentukan. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Menambahkan elemen output untuk konten teks. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Mengikat sumber daya ke file output. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Mengembalikan jalur untuk sumber daya tertentu. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

Menambahkan elemen output untuk objek konteks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | java.lang.String | Jalur output. |
| templateKey | java.lang.String | Kunci template yang digunakan untuk transformasi objek konteks sebelum output. |
| contextObject | TContextObject | Objek konteks. |

**Mengembalikan:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objek untuk objek konteks.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

Menambahkan elemen output untuk gambar.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | java.lang.String | Jalur output. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Gambar untuk output. |

**Mengembalikan:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objek untuk gambar.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

Menambahkan elemen output untuk gambar.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | java.lang.String | Jalur output. |
| image | [IImage](../../com.aspose.slides/iimage) | Gambar untuk output. |

**Mengembalikan:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objek untuk gambar.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

Menambahkan elemen output untuk video.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | java.lang.String | Jalur output. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video untuk output. |

**Mengembalikan:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objek untuk video.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

Membuat dan menambahkan elemen file output untuk font yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | java.lang.String | Jalur file tempat output font akan disimpan. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Data font yang akan ditulis ke output. |
| fontStyle | int | Gaya font (misalnya, Regular, Bold, Italic). |

**Mengembalikan:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Sebuah instance [IOutputFile](../../com.aspose.slides/ioutputfile) untuk font yang dihasilkan.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

Menambahkan elemen output untuk konten teks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | java.lang.String | Jalur output. |
| textContent | java.lang.String | Konten untuk output. |

**Mengembalikan:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objek untuk konten teks.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

Mengikat sumber daya ke file output.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | File output. |
| obj | java.lang.Object | Objek sumber daya. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

Mengembalikan jalur untuk sumber daya tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek sumber daya. |

**Mengembalikan:**
java.lang.String - Jalur sumber daya.