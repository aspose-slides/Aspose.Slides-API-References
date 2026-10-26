---
title: IPresentationFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create presentation via COM interface
type: docs
url: /id/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Memungkinkan pembuatan presentasi melalui antarmuka COM.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createPresentation()](#createPresentation--) | Creates new presentation. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Creates new presentation with additional load options |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Gets info about presentation in specified file. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Gets info about presentation in specified stream. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Reads an existing presentation from array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Reads an existing presentation from array with additional load options |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Reads an existing presentation from stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Reads an existing presentation from file |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Retrieves the raw text from the slides |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```


Membuat presentasi baru.

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentasi baru
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```


Membuat presentasi baru dengan opsi muat tambahan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opsi muat |

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentasi baru
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```


Mendapatkan info tentang presentasi dalam file yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.lang.String | File presentasi. |

**Mengembalikan:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Info presentasi
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```


Mendapatkan info tentang presentasi dalam stream yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Stream presentasi. |

**Mengembalikan:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Info presentasi.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```


Membaca presentasi yang ada dari array

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Array untuk dibaca |

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentasi yang dibaca
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```


Membaca presentasi yang ada dari array dengan opsi muat tambahan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Array untuk dibaca |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opsi muat |

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentasi yang dibaca
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```


Membaca presentasi yang ada dari stream

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Stream input untuk dibaca |

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentasi yang dibaca
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


Membaca presentasi yang ada dari stream dengan opsi muat tambahan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Stream input untuk dibaca |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opsi muat |

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentasi yang dibaca
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```


Membaca presentasi yang ada dari file

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.lang.String | Nama file |

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentasi yang dibaca
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```


Membaca presentasi yang ada dari file dengan opsi muat tambahan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.lang.String | Nama file |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opsi muat |

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentasi yang dibaca
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```


Mengambil teks mentah dari slide

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.lang.String | File input |
| mode | int | Mode ekstraksi |

**Mengembalikan:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instansi PresentationText yang berisi array SlideText yang mewakili teks mentah slide
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```


Mengambil teks mentah dari slide

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Stream input |
| mode | int | Mode ekstraksi |

**Mengembalikan:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instansi PresentationText yang berisi array SlideText yang mewakili teks mentah slide
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


Mengambil teks mentah dari slide

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Stream input |
| mode | int | Mode ekstraksi |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opsi muat |

**Mengembalikan:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instansi PresentationText yang berisi array SlideText yang mewakili teks mentah slide