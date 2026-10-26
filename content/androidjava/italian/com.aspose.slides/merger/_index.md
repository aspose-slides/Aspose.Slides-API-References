---
title: Merger
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta un gruppo di metodi per unire presentazioni PowerPoint dello stesso formato in un unico file.
type: docs
url: /it/com.aspose.slides/merger/
---
**Eredità:**  
java.lang.Object  
```
public class Merger
```

Rappresenta un gruppo di metodi per unire presentazioni PowerPoint dello stesso formato in un unico file.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione. |

### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```

Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Un array dei nomi dei file di presentazione di input. |
| outputFileName | java.lang.String | Il nome del file di output della presentazione unita risultante. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```

Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Un array dei nomi dei file di presentazione di input. |
| outputFileName | java.lang.String | Il nome del file di output della presentazione unita risultante. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Le opzioni aggiuntive che definiscono come viene salvata la presentazione unita. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```

Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```


**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Un array dei nomi dei file di presentazione di input. |
| outputStream | java.io.OutputStream | Il flusso di output. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```

Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Un array dei nomi dei file di presentazione di input. |
| outputStream | java.io.OutputStream | Il flusso di output. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Le opzioni aggiuntive che definiscono come viene salvata la presentazione unita. |