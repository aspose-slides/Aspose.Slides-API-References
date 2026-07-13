---
title: IAudio
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili file audio yang disematkan.
type: docs
url: /id/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Mewakili file audio yang disematkan.
## Methods

| Metode | Deskripsi |
| --- | --- |
| [getContentType()](#getContentType--) | Mengembalikan tipe MIME dari audio, yang dienkode dalam (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Mengembalikan salinan data audio. |
| [getStream()](#getStream--) | Mengembalikan Stream stream untuk membaca. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Mengembalikan tipe MIME dari audio, yang dienkode dalam (\#getBinaryData.getBinaryData). String hanya-baca.

**Mengembalikan:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Mengembalikan salinan data audio. Dalam kasus sejumlah besar data, pertimbangkan menggunakan metode \#getStream.getStream untuk mencegah pemuatan data audio yang tidak perlu ke memori atau bahkan OutOfMemoryException. byte[] hanya-baca.

**Mengembalikan:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Mengembalikan Stream stream untuk membaca. Gunakan 'using' atau tutup stream setelah digunakan.

**Mengembalikan:**
java.io.InputStream - Stream untuk membaca.