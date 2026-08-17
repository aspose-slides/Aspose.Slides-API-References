---
title: Merger
second_title: Aspose.Slides for Java API Referansı
description: Aynı formatta PowerPoint sunumlarını tek bir dosyada birleştirmek için bir grup yöntemi temsil eder.
type: docs
url: /tr/com.aspose.slides/merger/
---
**Kalıtım:**
java.lang.Object
```
public class Merger
```

Aynı formatta birden çok PowerPoint sunumunu tek bir dosyada birleştirmek için bir grup yöntem temsil eder.
## Metotlar

| Method | Description |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```


Aynı formatta birden çok PowerPoint sunumunu tek bir sunum dosyasında birleştirir.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Girdi sunum dosyalarının adlarını içeren bir dizi. |
| outputFileName | java.lang.String | Sonuçta elde edilen birleştirilmiş sunum dosyasının çıktı dosya adı. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```


Aynı formatta birden çok PowerPoint sunumunu tek bir sunum dosyasında birleştirir.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Girdi sunum dosyalarının adlarını içeren bir dizi. |
| outputFileName | java.lang.String | Sonuçta elde edilen birleştirilmiş sunum dosyasının çıktı dosya adı. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Birleştirilen sunumun nasıl kaydedileceğini tanımlayan ek seçenekler. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```


Aynı formatta birden çok PowerPoint sunumunu tek bir sunum dosyasında birleştirir.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Girdi sunum dosyalarının adlarını içeren bir dizi. |
| outputStream | java.io.OutputStream | Çıktı akışı. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```


Aynı formatta birden çok PowerPoint sunumunu tek bir sunum dosyasında birleştirir.

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
| inputFileNames | java.lang.String[] | Girdi sunum dosyalarının adlarını içeren bir dizi. |
| outputStream | java.io.OutputStream | Çıktı akışı. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Birleştirilen sunumun nasıl kaydedileceğini tanımlayan ek seçenekler. |