---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Antarmuka callback yang digunakan untuk mendapatkan hasil pencarian teks.
type: docs
url: /id/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Antarmuka callback yang digunakan untuk mendapatkan hasil pencarian teks.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Metode callback yang menerima data tentang teks yang ditemukan. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```


Metode callback yang menerima data tentang teks yang ditemukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | [ITextFrame](../../com.aspose.slides/itextframe) tempat teks ditemukan. |
| sourceText | java.lang.String | Teks sumber tempat teks ditemukan. |
| foundText | java.lang.String | Teks yang ditemukan. |
| textPosition | int | Posisi teks yang ditemukan. |