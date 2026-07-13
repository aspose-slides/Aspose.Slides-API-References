---
title: Audio
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili file audio tertanam.
type: docs
url: /id/com.aspose.slides/audio/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Mewakili file audio tertanam.
## Metode

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Mengembalikan tipe MIME dari audio, yang dienkode dalam (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Mengembalikan tipe MIME dari audio, yang dienkode dalam (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Mengembalikan salinan data audio. |
| [getStream()](#getStream--) | Mengembalikan aliran Stream untuk membaca. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Mengembalikan tipe MIME dari audio, yang dienkode dalam (\#getBinaryData.getBinaryData). String hanya-baca.

**Mengembalikan:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Mengembalikan tipe MIME dari audio, yang dienkode dalam (\#getBinaryData.getBinaryData). String hanya-baca.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Mengembalikan salinan data audio. Jika ada sejumlah besar data, pertimbangkan menggunakan metode \#getStream.getStream untuk mencegah pemuatan data audio yang tidak diperlukan ke memori atau bahkan OutOfMemoryException. byte[] hanya-baca.

**Mengembalikan:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Mengembalikan aliran Stream untuk membaca. Gunakan 'using' atau tutup aliran setelah digunakan.

**Mengembalikan:**
java.io.InputStream - Aliran untuk membaca.