---
title: Merger
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili sekumpulan metode untuk menggabungkan presentasi PowerPoint dengan format yang sama menjadi satu file.
type: docs
url: /id/com.aspose.slides/merger/
---
**Warisan:**
java.lang.Object
```
public class Merger
```

Mewakili sekumpulan metode untuk menggabungkan presentasi PowerPoint dengan format yang sama menjadi satu file.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```


Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Sekumpulan nama file presentasi input. |
| outputFileName | java.lang.String | Nama file output dari presentasi gabungan yang dihasilkan. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```


Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Sekumpulan nama file presentasi input. |
| outputFileName | java.lang.String | Nama file output dari presentasi gabungan yang dihasilkan. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opsi tambahan yang menentukan bagaimana presentasi gabungan disimpan. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```


Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Sekumpulan nama file presentasi input. |
| outputStream | java.io.OutputStream | Aliran output. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```


Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Sekumpulan nama file presentasi input. |
| outputStream | java.io.OutputStream | Aliran output. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opsi tambahan yang menentukan bagaimana presentasi gabungan disimpan. |