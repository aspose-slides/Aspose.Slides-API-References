---
title: Merger
second_title: Aspose.Slides para Android mediante la Referencia de la API Java
description: Representa un grupo de métodos para combinar presentaciones de PowerPoint del mismo formato en un solo archivo.
type: docs
url: /es/com.aspose.slides/merger/
---
**Herencia:** 
java.lang.Object
```
public class Merger
```

Representa un grupo de métodos para combinar presentaciones de PowerPoint del mismo formato en un solo archivo.
## Métodos

| Método | Descripción |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Combina varias presentaciones de PowerPoint del mismo formato en un solo archivo de presentación. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Combina varias presentaciones de PowerPoint del mismo formato en un solo archivo de presentación. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Combina varias presentaciones de PowerPoint del mismo formato en un solo archivo de presentación. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Combina varias presentaciones de PowerPoint del mismo formato en un solo archivo de presentación. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```

Combina varias presentaciones de PowerPoint del mismo formato en un solo archivo de presentación.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Una matriz de los nombres de archivo de presentación de entrada. |
| outputFileName | java.lang.String | El nombre de archivo de salida de la presentación combinada resultante. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```

Combina varias presentaciones de PowerPoint del mismo formato en un solo archivo de presentación.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Una matriz de los nombres de archivo de presentación de entrada. |
| outputFileName | java.lang.String | El nombre de archivo de salida de la presentación combinada resultante. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Las opciones adicionales que definen cómo se guarda la presentación combinada. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```

Combina varias presentaciones de PowerPoint del mismo formato en un solo archivo de presentación.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Una matriz de los nombres de archivo de presentación de entrada. |
| outputStream | java.io.OutputStream | El flujo de salida. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```

Combina varias presentaciones de PowerPoint del mismo formato en un solo archivo de presentación.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Una matriz de los nombres de archivo de presentación de entrada. |
| outputStream | java.io.OutputStream | El flujo de salida. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Las opciones adicionales que definen cómo se guarda la presentación combinada. |