---
title: Merger
second_title: Aspose.Slides for Android Java API Referansı
description: Aynı formatta PowerPoint sunumlarını tek bir dosyada birleştirmek için bir grup yöntemi temsil eder.
type: docs
url: /tr/com.aspose.slides/merger/
---
**Kalıtım:**
java.lang.Object
```
public class Merger
```

Aynı formatta PowerPoint sunumlarını tek bir dosyada birleştirmek için bir grup yöntemi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Aynı formatta birden fazla PowerPoint sunumunu tek bir sunum dosyasına birleştirir. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Aynı formatta birden fazla PowerPoint sunumunu tek bir sunum dosyasına birleştirir. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Aynı formatta birden fazla PowerPoint sunumunu tek bir sunum dosyasına birleştirir. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Aynı formatta birden fazla PowerPoint sunumunu tek bir sunum dosyasına birleştirir. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```


Aynı formatta birden fazla PowerPoint sunumunu tek bir sunum dosyasına birleştirir.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Girdi sunum dosyası adlarının dizisi. |
| outputFileName | java.lang.String | Oluşturulan birleştirilmiş sunum dosyasının çıktı dosya adı. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```


Aynı formatta birden fazla PowerPoint sunumunu tek bir sunum dosyasına birleştirir.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Girdi sunum dosyası adlarının dizisi. |
| outputFileName | java.lang.String | Oluşturulan birleştirilmiş sunum dosyasının çıktı dosya adı. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Birleştirilmiş sunumun nasıl kaydedileceğini tanımlayan ek seçenekler. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```


Aynı formatta birden fazla PowerPoint sunumunu tek bir sunum dosyasına birleştirir.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Girdi sunum dosyası adlarının dizisi. |
| outputStream | java.io.OutputStream | Çıktı akışı. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```


Aynı formatta birden fazla PowerPoint sunumunu tek bir sunum dosyasına birleştirir.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Girdi sunum dosyası adlarının dizisi. |
| outputStream | java.io.OutputStream | Çıktı akışı. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Birleştirilmiş sunumun nasıl kaydedileceğini tanımlayan ek seçenekler. |