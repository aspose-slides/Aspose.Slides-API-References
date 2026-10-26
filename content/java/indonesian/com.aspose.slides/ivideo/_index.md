---
title: IVideo
second_title: Aspose.Slides for Java API Reference
description: Mewakili video yang disematkan ke dalam presentasi.
type: docs
url: /id/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Mewakili video yang disematkan ke dalam presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getContentType()](#getContentType--) | Mengembalikan tipe MIME dari video, terenkripsi dalam (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Mengembalikan salinan data audio. |
| [getStream()](#getStream--) | Mengembalikan aliran Stream untuk membaca. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Mengembalikan tipe MIME dari video, terenkripsi dalam (\#getBinaryData.getBinaryData). Read-only String.

**Mengembalikan:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Mengembalikan salinan data audio. Jika data dalam jumlah besar, pertimbangkan penggunaan metode \#getStream.getStream untuk mencegah pemuatan data video yang tidak diperlukan ke memori atau bahkan OutOfMemoryException. Read-only byte[].

**Mengembalikan:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Mengembalikan aliran Stream untuk membaca. Gunakan 'using' atau tutup aliran setelah selesai digunakan.

**Mengembalikan:**
java.io.InputStream - Stream untuk membaca.