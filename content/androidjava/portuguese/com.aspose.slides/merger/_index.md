---
title: Merger
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um grupo de métodos para mesclar apresentações do PowerPoint no mesmo formato em um único arquivo.
type: docs
url: /pt/com.aspose.slides/merger/
---
**Herança:**
java.lang.Object
```
public class Merger
```

Representa um grupo de métodos para mesclar apresentações do PowerPoint no mesmo formato em um único arquivo.
## Métodos

| Método | Descrição |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Mescla várias apresentações do PowerPoint no mesmo formato em um único arquivo de apresentação. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Mescla várias apresentações do PowerPoint no mesmo formato em um único arquivo de apresentação. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Mescla várias apresentações do PowerPoint no mesmo formato em um único arquivo de apresentação. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Mescla várias apresentações do PowerPoint no mesmo formato em um único arquivo de apresentação. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```


Mescla várias apresentações do PowerPoint no mesmo formato em um único arquivo de apresentação.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Um array com os nomes dos arquivos de apresentação de entrada. |
| outputFileName | java.lang.String | O nome do arquivo de saída da apresentação mesclada resultante. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```


Mescla várias apresentações do PowerPoint no mesmo formato em um único arquivo de apresentação.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Um array com os nomes dos arquivos de apresentação de entrada. |
| outputFileName | java.lang.String | O nome do arquivo de saída da apresentação mesclada resultante. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | As opções adicionais que definem como a apresentação mesclada será salva. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```


Mescla várias apresentações do PowerPoint no mesmo formato em um único arquivo de apresentação.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Um array com os nomes dos arquivos de apresentação de entrada. |
| outputStream | java.io.OutputStream | O fluxo de saída. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```


Mescla várias apresentações do PowerPoint no mesmo formato em um único arquivo de apresentação.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Um array com os nomes dos arquivos de apresentação de entrada. |
| outputStream | java.io.OutputStream | O fluxo de saída. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | As opções adicionais que definem como a apresentação mesclada será salva. |