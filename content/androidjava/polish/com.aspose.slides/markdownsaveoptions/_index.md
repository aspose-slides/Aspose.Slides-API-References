---
title: MarkdownSaveOptions
second_title: Aspose.Slides dla Androida poprzez odwołanie do Java API
description: Reprezentuje opcje kontrolujące, jak prezentacja ma być zapisywana w formacie markdown.
type: docs
url: /pl/com.aspose.slides/markdownsaveoptions/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Reprezentuje opcje kontrolujące, jak prezentacja ma być zapisywana w formacie markdown.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Konstruktor. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getExportType()](#getExportType--) | Określa specyfikację markdown używaną do konwersji prezentacji. |
| [setExportType(int value)](#setExportType-int-) | Określa specyfikację markdown używaną do konwersji prezentacji. |
| [getBasePath()](#getBasePath--) | Określa podstawową ścieżkę, w której zostanie zapisany dokument z zasobami. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Określa podstawową ścieżkę, w której zostanie zapisany dokument z zasobami. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Określa nazwę folderu, w którym zapisywane są obrazy. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Określa nazwę folderu, w którym zapisywane są obrazy. |
| [getNewLineType()](#getNewLineType--) | Określa, czy generowany dokument powinien mieć nowe linie \\\\r(Macintosh) , \\\\n(Unix) lub \\\\r\\\\n(Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Określa, czy generowany dokument powinien mieć nowe linie \\\\r(Macintosh) , \\\\n(Unix) lub \\\\r\\\\n(Windows). |
| [getShowComments()](#getShowComments--) | Określa, czy generowany dokument powinien wyświetlać komentarze. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Określa, czy generowany dokument powinien wyświetlać komentarze. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Określa, czy generowany dokument powinien zawierać ukryte slajdy. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Określa, czy generowany dokument powinien zawierać ukryte slajdy. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Określa, czy generowany dokument powinien wyświetlać numer każdego slajdu. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Określa, czy generowany dokument powinien wyświetlać numer każdego slajdu. |
| [getFlavor()](#getFlavor--) | Określa specyfikację markdown używaną do konwersji prezentacji. |
| [setFlavor(int value)](#setFlavor-int-) | Określa specyfikację markdown używaną do konwersji prezentacji. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Pobiera lub ustawia ciąg formatowania używany dla nagłówków numerów slajdów w wyjściu Markdown. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Pobiera lub ustawia ciąg formatowania używany dla nagłówków numerów slajdów w wyjściu Markdown. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Określa, jak powtarzające się regularne znaki spacji powinny być obsługiwane podczas eksportu Markdown. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Określa, jak powtarzające się regularne znaki spacji powinny być obsługiwane podczas eksportu Markdown. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Jeśli ustawione na true, usuwa puste lub zawierające tylko białe znaki linie z końcowego wyjścia Markdown. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Jeśli ustawione na true, usuwa puste lub zawierające tylko białe znaki linie z końcowego wyjścia Markdown. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Występuje dla każdego obrazu nie-SVG (bitmapa lub metafile) podczas eksportu Markdown. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Występuje dla każdego obrazu SVG podczas eksportu Markdown. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Konstruktor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

Określa specyfikację markdown używaną do konwersji prezentacji. Domyślna wartość to  TextOnly .

**Zwraca:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

Określa specyfikację markdown używaną do konwersji prezentacji. Domyślna wartość to  TextOnly .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

Określa podstawową ścieżkę, w której zostanie zapisany dokument z zasobami. Domyślną wartością jest bieżący katalog aplikacji.

**Zwraca:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

Określa podstawową ścieżkę, w której zostanie zapisany dokument z zasobami. Domyślną wartością jest bieżący katalog aplikacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

Określa nazwę folderu, w którym zapisywane są obrazy. Domyślną wartością jest  Images .

**Zwraca:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

Określa nazwę folderu, w którym zapisywane są obrazy. Domyślną wartością jest  Images .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

Określa, czy generowany dokument powinien mieć nowe linie \\\\r(Macintosh) , \\\\n(Unix) lub \\\\r\\\\n(Windows). Domyślna wartość to  Unix .

**Zwraca:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

Określa, czy generowany dokument powinien mieć nowe linie \\\\r(Macintosh) , \\\\n(Unix) lub \\\\r\\\\n(Windows). Domyślna wartość to  Unix .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

Określa, czy generowany dokument powinien wyświetlać komentarze. Domyślna wartość to false.

**Zwraca:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

Określa, czy generowany dokument powinien wyświetlać komentarze. Domyślna wartość to false.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Określa, czy generowany dokument powinien zawierać ukryte slajdy. Domyślna wartość to false.

**Zwraca:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Określa, czy generowany dokument powinien zawierać ukryte slajdy. Domyślna wartość to false.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

Określa, czy generowany dokument powinien wyświetlać numer każdego slajdu. Domyślna wartość to false.

**Zwraca:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

Określa, czy generowany dokument powinien wyświetlać numer każdego slajdu. Domyślna wartość to false.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

Określa specyfikację markdown używaną do konwersji prezentacji. Domyślna wartość to  Multi-markdown .

**Zwraca:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

Określa specyfikację markdown używaną do konwersji prezentacji. Domyślna wartość to  Multi-markdown .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

Pobiera lub ustawia ciąg formatowania używany dla nagłówków numerów slajdów w wyjściu Markdown. Format musi zawierać symbol "\{0\}", który zostanie zastąpiony indeksem slajdu podczas eksportu. Przykład: "\# Slide \{0\}" wygeneruje "\# Slide 1", "\# Slide 2" itd.

**Zwraca:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

Pobiera lub ustawia ciąg formatowania używany dla nagłówków numerów slajdów w wyjściu Markdown. Format musi zawierać symbol "\{0\}", który zostanie zastąpiony indeksem slajdu podczas eksportu. Przykład: "\# Slide \{0\}" wygeneruje "\# Slide 1", "\# Slide 2" itd.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

Określa, jak powtarzające się regularne znaki spacji powinny być obsługiwane podczas eksportu Markdown. Właściwość ta definiuje, czy kolejne spacje są: - zachowane jako regularne znaki spacji, - naprzemiennie zamieniane na regularne spacje i encje niełamliwych spacji (�), - albo całkowicie zastępowane (po pierwszej) niełamliwą spacją w celu zachowania wizualnego wyrównania w wyjściu Markdown. Domyślna wartość to [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Zwraca:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

Określa, jak powtarzające się regularne znaki spacji powinny być obsługiwane podczas eksportu Markdown. Właściwość ta definiuje, czy kolejne spacje są: - zachowane jako regularne znaki spacji, - naprzemiennie zamieniane na regularne spacje i encje niełamliwych spacji (�), - albo całkowicie zastępowane (po pierwszej) niełamliwą spacją w celu zachowania wizualnego wyrównania w wyjściu Markdown. Domyślna wartość to [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

Jeśli ustawione na true, usuwa puste lub zawierające tylko białe znaki linie z końcowego wyjścia Markdown. Domyślna wartość to false.

**Zwraca:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

Jeśli ustawione na true, usuwa puste lub zawierające tylko białe znaki linie z końcowego wyjścia Markdown. Domyślna wartość to false.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

Występuje dla każdego obrazu nie-SVG (bitmapa lub metafile) podczas eksportu Markdown. Umożliwia dostosowanie sposobu zapisu i odwoływania się do obrazu. Jeśli nie zostanie obsłużone, obraz zostanie zapisany lokalnie z linkiem względnym.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Zdarzenie zapisu obrazu Markdown. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

Występuje dla każdego obrazu SVG podczas eksportu Markdown. Umożliwia nadpisanie domyślnego zapisu i generowania linku. Jeśli nie zostanie obsłużone, SVG zostanie zapisany lokalnie z linkiem względnym.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Zdarzenie zapisu obrazu SVG Markdown. |