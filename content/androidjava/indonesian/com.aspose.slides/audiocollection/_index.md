---
title: AudioCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi file audio tersemat.
type: docs
url: /id/com.aspose.slides/audiocollection/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Mewakili koleksi file audio tersemat.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mengembalikan jumlah file audio dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Menambahkan salinan file audio dari presentasi lain. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Membuat dan menambahkan audio ke presentasi dari aliran. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Membuat dan menambahkan audio ke presentasi dari aliran. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Membuat dan menambahkan audio ke presentasi dari array byte. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin audio ke array yang ditentukan mulai dari indeks yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman terhadap thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
### size() {#size--}
```
public final int size()
```


Mengembalikan jumlah file audio dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
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
public final IAudio addAudio(IAudio audio)
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
public final IAudio addAudio(InputStream stream)
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
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


Membuat dan menambahkan audio ke presentasi dari aliran.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk menambahkan audio video. |
| loadingStreamBehavior | int | Perilaku yang akan diterapkan pada aliran. |

**Mengembalikan:**
[IAudio](../../com.aspose.slides/iaudio) - Audio yang ditambahkan.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```


Membuat dan menambahkan audio ke presentasi dari array byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| audioData | byte[] | Byte audio. |

**Mengembalikan:**
[IAudio](../../com.aspose.slides/iaudio) - Audio yang ditambahkan.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Menyalin audio ke array yang ditentukan mulai dari indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array. |
| index | int | Index. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman terhadap thread). Hanya-baca boolean.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Mengembalikan akar sinkronisasi. Hanya-baca Object.

**Mengembalikan:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```


Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - An java.util.Iterator for the entire collection.