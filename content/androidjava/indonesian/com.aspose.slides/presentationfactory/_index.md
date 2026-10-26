---
title: PresentationFactory
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Memungkinkan membuat presentasi melalui antarmuka COM
type: docs
url: /id/com.aspose.slides/presentationfactory/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Memungkinkan pembuatan presentasi melalui antarmuka COM

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getInstance()](#getInstance--) | Instansi statis pabrik presentasi. |
| [createPresentation()](#createPresentation--) | Membuat presentasi baru. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Membuat presentasi baru dengan opsi pemuatan tambahan |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Membuat objek PresentationInfo dari file dan mengaitkan presentasi dengan objek tersebut. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Membuat objek PresentationInfo dari aliran dan mengaitkan presentasi dengan objek tersebut. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Membaca presentasi yang ada dari array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Membaca presentasi yang ada dari array dengan opsi pemuatan tambahan |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Membaca presentasi yang ada dari aliran |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Membaca presentasi yang ada dari aliran dengan opsi pemuatan tambahan |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Membaca presentasi yang ada dari file |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Membaca presentasi yang ada dari aliran dengan opsi pemuatan tambahan |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Mengambil teks mentah dari slide |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Mengambil teks mentah dari slide |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Mengambil teks mentah dari slide |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```


### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```


Instansi statis pabrik presentasi. Hanya-baca [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Mengembalikan:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```


Membuat presentasi baru.

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentasi baru
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```


Membuat presentasi baru dengan opsi pemuatan tambahan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opsi pemuatan |

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentasi baru
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```


Membuat objek PresentationInfo dari file dan mengaitkan presentasi dengan objek tersebut.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.lang.String | File presentasi. |

**Mengembalikan:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informasi presentasi yang terikat pada presentasi.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```


Membuat objek PresentationInfo dari aliran dan mengaitkan presentasi dengan objek tersebut. Mendapatkan info tentang presentasi dalam aliran yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran presentasi. |

**Mengembalikan:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informasi presentasi yang terikat pada presentasi.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
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
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```


Membaca presentasi yang ada dari array dengan opsi pemuatan tambahan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Array untuk dibaca |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opsi pemuatan |

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentasi yang dibaca
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```


Membaca presentasi yang ada dari aliran

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran masukan untuk dibaca |

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentasi yang dibaca
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


Membaca presentasi yang ada dari aliran dengan opsi pemuatan tambahan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran masukan untuk dibaca |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opsi pemuatan |

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentasi yang dibaca
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPPresentation readPresentation(String file)
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
public final IPresentation readPresentation(String file, ILoadOptions options)
```


Membaca presentasi yang ada dari aliran dengan opsi pemuatan tambahan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.lang.String | Nama file |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opsi pemuatan |

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentasi yang dibaca
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```


Mengambil teks mentah dari slide

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.lang.String | File masukan |
| mode | int | Mode ekstraksi |

**Mengembalikan:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instansi dari PresentationText yang berisi array SlideText yang mewakili teks mentah slide
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```


Mengambil teks mentah dari slide

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran masukan |
| mode | int | Mode ekstraksi |

**Mengembalikan:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instansi dari PresentationText yang berisi array SlideText yang mewakili teks mentah slide
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


Mengambil teks mentah dari slide

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran masukan |
| mode | int | Mode ekstraksi |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opsi pemuatan |

**Mengembalikan:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instansi dari PresentationText yang berisi array SlideText yang mewakili teks mentah slide