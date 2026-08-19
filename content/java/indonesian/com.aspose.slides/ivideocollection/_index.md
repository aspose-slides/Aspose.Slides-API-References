---
title: IVideoCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili sekumpulan objek Video.
type: docs
url: /id/com.aspose.slides/ivideocollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Mewakili koleksi objek Video.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Menambahkan salinan file video dari presentasi lain. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Membuat dan menambahkan video ke presentasi dari aliran. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Membuat dan menambahkan video ke presentasi dari array byte. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

Mendapatkan elemen pada indeks yang ditentukan. Hanya-baca [IVideo](../../com.aspose.slides/ivideo).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```

Menambahkan salinan file video dari presentasi lain.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video sumber. |

**Mengembalikan:**
[IVideo](../../com.aspose.slides/ivideo) - Video yang ditambahkan.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Membuat dan menambahkan video ke presentasi dari aliran.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk menambahkan file video. |
| loadingStreamBehavior | int | Perilaku yang akan diterapkan pada aliran. |

**Mengembalikan:**
[IVideo](../../com.aspose.slides/ivideo) - Ditambahkan [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```

Membuat dan menambahkan video ke presentasi dari array byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| videoData | byte[] | Byte video. |

**Mengembalikan:**
[IVideo](../../com.aspose.slides/ivideo) - Video yang ditambahkan.