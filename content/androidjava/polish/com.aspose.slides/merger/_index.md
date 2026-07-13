---
title: Merger
second_title: Aspose.Slides dla Androida poprzez dokumentację API Java
description: Reprezentuje grupę metod służących do łączenia prezentacji PowerPoint o tym samym formacie w jeden plik.
type: docs
url: /pl/com.aspose.slides/merger/
---
**Dziedziczenie:**
java.lang.Object
```
public class Merger
```

Reprezentuje grupę metod służących do łączenia prezentacji PowerPoint o tym samym formacie w jeden plik prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Łączy wiele prezentacji PowerPoint o tym samym formacie w jeden plik prezentacji. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Łączy wiele prezentacji PowerPoint o tym samym formacie w jeden plik prezentacji. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Łączy wiele prezentacji PowerPoint o tym samym formacie w jeden plik prezentacji. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Łączy wiele prezentacji PowerPoint o tym samym formacie w jeden plik prezentacji. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```


Łączy wiele prezentacji PowerPoint o tym samym formacie w jeden plik prezentacji.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Tablica nazw plików prezentacji wejściowych. |
| outputFileName | java.lang.String | Nazwa pliku wyjściowego wynikowej połączonej prezentacji. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```


Łączy wiele prezentacji PowerPoint o tym samym formacie w jeden plik prezentacji.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Tablica nazw plików prezentacji wejściowych. |
| outputFileName | java.lang.String | Nazwa pliku wyjściowego wynikowej połączonej prezentacji. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatkowe opcje określające sposób zapisywania połączonej prezentacji. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```


Łączy wiele prezentacji PowerPoint o tym samym formacie w jeden plik prezentacji.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Tablica nazw plików prezentacji wejściowych. |
| outputStream | java.io.OutputStream | Strumień wyjściowy. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```


Łączy wiele prezentacji PowerPoint o tym samym formacie w jeden plik prezentacji.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Tablica nazw plików prezentacji wejściowych. |
| outputStream | java.io.OutputStream | Strumień wyjściowy. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatkowe opcje określające sposób zapisywania połączonej prezentacji. |