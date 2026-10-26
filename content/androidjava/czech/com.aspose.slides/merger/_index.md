---
title: Merger
second_title: Aspose.Slides pro Android přes Java API Reference
description: Representuje skupinu metod pro sloučení prezentací PowerPointu ve stejném formátu do jednoho souboru.
type: docs
url: /cs/com.aspose.slides/merger/
---
**Dědičnost:**
java.lang.Object
```
public class Merger
```

Representuje skupinu metod pro sloučení prezentací PowerPointu ve stejném formátu do jednoho souboru.
## Metody

| Metoda | Popis |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Sloučí několik prezentací PowerPointu ve stejném formátu do jediného souboru prezentace. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Sloučí několik prezentací PowerPointu ve stejném formátu do jediného souboru prezentace. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Sloučí několik prezentací PowerPointu ve stejném formátu do jediného souboru prezentace. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Sloučí několik prezentací PowerPointu ve stejném formátu do jediného souboru prezentace. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```


Sloučí několik prezentací PowerPointu ve stejném formátu do jediného souboru prezentace.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Pole názvů vstupních souborů prezentací. |
| outputFileName | java.lang.String | Název výstupního souboru výsledné sloučené prezentace. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```


Sloučí několik prezentací PowerPointu ve stejném formátu do jediného souboru prezentace.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Pole názvů vstupních souborů prezentací. |
| outputFileName | java.lang.String | Název výstupního souboru výsledné sloučené prezentace. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Další možnosti, které určují, jak bude sloučená prezentace uložena. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```


Sloučí několik prezentací PowerPointu ve stejném formátu do jediného souboru prezentace.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Pole názvů vstupních souborů prezentací. |
| outputStream | java.io.OutputStream | Výstupní stream. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```


Sloučí několik prezentací PowerPointu ve stejném formátu do jediného souboru prezentace.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Pole názvů vstupních souborů prezentací. |
| outputStream | java.io.OutputStream | Výstupní stream. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Další možnosti, které určují, jak bude sloučená prezentace uložena. |