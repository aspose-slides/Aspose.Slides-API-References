---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: Mewakili file audio yang tertanam.
type: docs
url: /id/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Mewakili file audio yang tertanam.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getContentType()](#getContentType--) | Mengembalikan tipe MIME audio, yang dikodekan dalam (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Mengembalikan salinan data audio. |
| [getStream()](#getStream--) | Mengembalikan Stream untuk membaca. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Mengembalikan tipe MIME audio, yang dikodekan dalam (\#getBinaryData.getBinaryData). String hanya baca.

**Mengembalikan:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Mengembalikan salinan data audio. Jika jumlah data besar, pertimbangkan menggunakan metode \#getStream.getStream untuk mencegah pemuatan data audio yang tidak perlu ke memori atau bahkan OutOfMemoryException. byte[] hanya baca.

**Mengembalikan:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Mengembalikan Stream untuk membaca. Gunakan 'using' atau tutup stream setelah penggunaan.

**Mengembalikan:**
java.io.InputStream - Stream untuk membaca.