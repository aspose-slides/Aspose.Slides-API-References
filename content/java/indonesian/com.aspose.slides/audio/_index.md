---
title: Audio
second_title: Referensi API Aspose.Slides untuk Java
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

| Metode | Deskripsi |
| --- | --- |
| [getContentType()](#getContentType--) | Mengembalikan tipe MIME audio, dienkode dalam (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Mengembalikan tipe MIME audio, dienkode dalam (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Mengembalikan salinan data audio. |
| [getStream()](#getStream--) | Mengembalikan Stream untuk membaca. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Mengembalikan tipe MIME audio, dienkode dalam (\#getBinaryData.getBinaryData). Hanya-baca String.

**Mengembalikan:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Mengembalikan tipe MIME audio, dienkode dalam (\#getBinaryData.getBinaryData). Hanya-baca String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Mengembalikan salinan data audio. Jika terdapat sejumlah besar data, pertimbangkan penggunaan metode \#getStream.getStream untuk mencegah pemuatan data audio yang tidak diperlukan ke memori atau bahkan OutOfMemoryException. Hanya-baca byte[].

**Mengembalikan:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Mengembalikan Stream untuk membaca. Gunakan 'using' atau tutup stream setelah digunakan.

**Mengembalikan:**
java.io.InputStream - Stream untuk membaca.