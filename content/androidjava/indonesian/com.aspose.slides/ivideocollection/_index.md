---
title: IVideoCollection
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili kumpulan objek Video.
type: docs
url: /id/com.aspose.slides/ivideocollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Mewakili kumpulan objek Video.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengambil elemen pada indeks yang ditentukan. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Menambahkan salinan file video dari presentasi lain. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Membuat dan menambahkan video ke presentasi dari stream. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Membuat dan menambahkan video ke presentasi dari array byte. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

Mengambil elemen pada indeks yang ditentukan. Hanya-baca [IVideo](../../com.aspose.slides/ivideo).

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

Membuat dan menambahkan video ke presentasi dari stream.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk menambahkan file video dari. |
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