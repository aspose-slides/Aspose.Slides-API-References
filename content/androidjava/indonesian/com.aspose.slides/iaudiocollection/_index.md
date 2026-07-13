---
title: IAudioCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili kumpulan file audio tersemat.
type: docs
url: /id/com.aspose.slides/iaudiocollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Mewakili kumpulan file audio tersemat.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Menambahkan salinan file audio dari presentasi lain. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Membuat dan menambahkan audio ke presentasi dari aliran. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Membuat dan menambahkan audio ke presentasi dari aliran. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Membuat dan menambahkan audio ke presentasi dari array byte. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

Mendapatkan elemen pada indeks yang ditentukan. Hanya-baca [IAudio](../../com.aspose.slides/iaudio).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```

Menambahkan salinan file audio dari presentasi lain.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Audio sumber. |

**Mengembalikan:**
[IAudio](../../com.aspose.slides/iaudio) - Audio yang ditambahkan.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

Membuat dan menambahkan audio ke presentasi dari aliran.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk menambahkan audio. |

**Mengembalikan:**
[IAudio](../../com.aspose.slides/iaudio) - Audio yang ditambahkan.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Membuat dan menambahkan audio ke presentasi dari aliran.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk menambahkan audio video. |
| loadingStreamBehavior | int | [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) yang akan diterapkan pada aliran. |

**Mengembalikan:**
[IAudio](../../com.aspose.slides/iaudio) - Audio yang ditambahkan.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

Membuat dan menambahkan audio ke presentasi dari array byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| audioData | byte[] | Byte audio. |

**Mengembalikan:**
[IAudio](../../com.aspose.slides/iaudio) - Audio yang ditambahkan.