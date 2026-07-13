---
title: IPresentationFactory
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Memungkinkan membuat presentasi melalui antarmuka COM
type: docs
url: /id/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Memungkinkan membuat presentasi melalui antarmuka COM

## Metode

| Method | Description |
| --- | --- |
| [createPresentation()](#createPresentation--) | Membuat presentasi baru. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Membuat presentasi baru dengan opsi pemuatan tambahan |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Mendapatkan info tentang presentasi dalam file yang ditentukan. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Mendapatkan info tentang presentasi dalam stream yang ditentukan. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Membaca presentasi yang ada dari array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Membaca presentasi yang ada dari array dengan opsi pemuatan tambahan |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Membaca presentasi yang ada dari stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Membaca presentasi yang ada dari stream dengan opsi pemuatan tambahan |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Membaca presentasi yang ada dari file |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Membaca presentasi yang ada dari stream dengan opsi pemuatan tambahan |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Mengambil teks mentah dari slide |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Mengambil teks mentah dari slide |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Mengambil teks mentah dari slide |

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

Membuat presentasi baru dengan opsi pemuatan tambahan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opsi pemuatan |

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

Membaca presentasi yang ada dari stream dengan opsi pemuatan tambahan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Stream input untuk dibaca |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opsi pemuatan |

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

Membaca presentasi yang ada dari file dengan opsi pemuatan tambahan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.lang.String | Nama file |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opsi pemuatan |

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
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opsi pemuatan |

**Mengembalikan:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instansi PresentationText yang berisi array SlideText yang mewakili teks mentah slide