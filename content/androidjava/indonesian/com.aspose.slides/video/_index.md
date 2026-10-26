---
title: Video
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili gambar yang disematkan ke dalam presentasi.
type: docs
url: /id/com.aspose.slides/video/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Mewakili gambar yang disematkan ke dalam presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getContentType()](#getContentType--) | Mengembalikan tipe MIME dari sebuah video, yang dienkode dalam (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Mengembalikan salinan data audio. |
| [getStream()](#getStream--) | Mengembalikan aliran Stream untuk membaca. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Mengembalikan tipe MIME dari sebuah video, yang dienkode dalam (\#getBinaryData.getBinaryData). String hanya-baca.

**Mengembalikan:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Mengembalikan salinan data audio. Jika terdapat sejumlah besar data, pertimbangkan penggunaan metode \#getStream.getStream untuk mencegah pemuatan data video yang tidak diperlukan ke memori atau bahkan OutOfMemoryException. byte[] hanya-baca.

**Mengembalikan:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Mengembalikan aliran Stream untuk membaca. Gunakan 'using' atau tutup aliran setelah digunakan.

**Mengembalikan:**
java.io.InputStream - Aliran untuk membaca.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent\_Immediate. IDOMObject hanya-baca.

**Mengembalikan:**
com.aspose.slides.IDOMObject