---
title: IVideo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a video embedded into a presentation.
type: docs
url: /id/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Mewakili video yang disematkan ke dalam presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getContentType()](#getContentType--) | Mengembalikan tipe MIME dari video, dienkode dalam (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Mengembalikan salinan data audio. |
| [getStream()](#getStream--) | Mengembalikan aliran Stream untuk membaca. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Mengembalikan tipe MIME dari video, dienkode dalam (\#getBinaryData.getBinaryData). Baca-saja String.

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Mengembalikan salinan data audio. Jika jumlah data besar, pertimbangkan penggunaan metode \#getStream.getStream untuk mencegah memuat data video yang tidak diperlukan ke memori atau bahkan OutOfMemoryException. Baca-saja byte[].

**Returns:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Mengembalikan aliran Stream untuk membaca. Gunakan 'using' atau tutup aliran setelah selesai digunakan.

**Returns:**
java.io.InputStream - Stream untuk membaca.