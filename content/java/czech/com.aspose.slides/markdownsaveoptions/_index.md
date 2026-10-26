---
title: MarkdownSaveOptions
second_title: Aspose.Slides pro Java – referenční příručka API
description: Representuje možnosti, které řídí, jak má být prezentace uložena do markdownu.
type: docs
url: /cs/com.aspose.slides/markdownsaveoptions/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Represents options that control how presentation should be saved to markdown.

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

| Konstruktor | Popis |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Konstruktor. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getExportType()](#getExportType--) | Specifikuje specifikaci markdownu pro konverzi prezentace. |
| [setExportType(int value)](#setExportType-int-) | Specifikuje specifikaci markdownu pro konverzi prezentace. |
| [getBasePath()](#getBasePath--) | Specifikuje základní cestu, kam bude dokument s prostředky uložen. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Specifikuje základní cestu, kam bude dokument s prostředky uložen. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Specifikuje název složky pro uložení obrázků. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Specifikuje název složky pro uložení obrázků. |
| [getNewLineType()](#getNewLineType--) | Určuje, zda má vygenerovaný dokument používat nové řádky \\r (Macintosh), \\n (Unix) nebo \\r\\n (Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Určuje, zda má vygenerovaný dokument používat nové řádky \\r (Macintosh), \\n (Unix) nebo \\r\\n (Windows). |
| [getShowComments()](#getShowComments--) | Určuje, zda má vygenerovaný dokument zobrazovat komentáře. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Určuje, zda má vygenerovaný dokument zobrazovat komentáře. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Určuje, zda má vygenerovaný dokument zobrazovat číslo každého snímku. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Určuje, zda má vygenerovaný dokument zobrazovat číslo každého snímku. |
| [getFlavor()](#getFlavor--) | Specifikuje specifikaci markdownu pro konverzi prezentace. |
| [setFlavor(int value)](#setFlavor-int-) | Specifikuje specifikaci markdownu pro konverzi prezentace. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Získá nebo nastaví formátovací řetězec používaný pro záhlaví čísel snímků ve výstupu Markdown. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Získá nebo nastaví formátovací řetězec používaný pro záhlaví čísel snímků ve výstupu Markdown. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Určuje, jak mají být při exportu do Markdownu zpracovány opakované běžné mezery. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Určuje, jak mají být při exportu do Markdownu zpracovány opakované běžné mezery. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Pokud je nastaveno na true, odstraňuje prázdné řádky nebo řádky obsahující pouze mezery z konečného výstupu Markdown. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Pokud je nastaveno na true, odstraňuje prázdné řádky nebo řádky obsahující pouze mezery z konečného výstupu Markdown. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Vyskytuje se pro každý ne-SVG obrázek (bitmapa nebo metafile) během exportu do Markdownu. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Vyskytuje se pro každý SVG obrázek během exportu do Markdownu. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Konstruktor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

Specifikuje specifikaci markdownu pro konverzi prezentace. Výchozí je TextOnly.

**Vrací:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

Specifikuje specifikaci markdownu pro konverzi prezentace. Výchozí je TextOnly.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

Specifikuje základní cestu, kam bude dokument s prostředky uložen. Výchozí je aktuální adresář aplikace.

**Vrací:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

Specifikuje základní cestu, kam bude dokument s prostředky uložen. Výchozí je aktuální adresář aplikace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

Specifikuje název složky pro uložení obrázků. Výchozí je Images.

**Vrací:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

Specifikuje název složky pro uložení obrázků. Výchozí je Images.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

Určuje, zda má vygenerovaný dokument používat nové řádky \\r (Macintosh), \\n (Unix) nebo \\r\\n (Windows). Výchozí je Unix.

**Vrací:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

Určuje, zda má vygenerovaný dokument používat nové řádky \\r (Macintosh), \\n (Unix) nebo \\r\\n (Windows). Výchozí je Unix.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

Určuje, zda má vygenerovaný dokument zobrazovat komentáře. Výchozí je false.

**Vrací:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

Určuje, zda má vygenerovaný dokument zobrazovat komentáře. Výchozí je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky. Výchozí je false.

**Vrací:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky. Výchozí je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

Určuje, zda má vygenerovaný dokument zobrazovat číslo každého snímku. Výchozí je false.

**Vrací:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

Určuje, zda má vygenerovaný dokument zobrazovat číslo každého snímku. Výchozí je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

Specifikuje specifikaci markdownu pro konverzi prezentace. Výchozí je Multi-markdown.

**Vrací:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

Specifikuje specifikaci markdownu pro konverzi prezentace. Výchozí je Multi-markdown.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

Získá nebo nastaví formátovací řetězec používaný pro záhlaví čísel snímků ve výstupu Markdown. Formát musí obsahovat zástupný znak "\{0\}", který bude během exportu nahrazen indexem snímku. Příklad: "\# Slide \{0\}" vytvoří "\# Slide 1", "\# Slide 2" atd.

**Vrací:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

Získá nebo nastaví formátovací řetězec používaný pro záhlaví čísel snímků ve výstupu Markdown. Formát musí obsahovat zástupný znak "\{0\}", který bude během exportu nahrazen indexem snímku. Příklad: "\# Slide \{0\}" vytvoří "\# Slide 1", "\# Slide 2" atd.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

Určuje, jak mají být při exportu do Markdownu zpracovány opakované běžné mezery. Tato vlastnost určuje, zda jsou po sobě jdoucí mezery: - zachovány jako běžné mezerné znaky, - střídány mezi běžnými mezerami a neoddělitelnými mezerovými entitami (�), - nebo plně nahrazeny (po první) neoddělitelní mezerou pro zachování vizuálního zarovnání ve výstupu Markdown. Výchozí hodnota je [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Vrací:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

Určuje, jak mají být při exportu do Markdownu zpracovány opakované běžné mezery. Tato vlastnost určuje, zda jsou po sobě jdoucí mezery: - zachovány jako běžné mezerné znaky, - střídány mezi běžnými mezerami a neoddělitelnými mezerovými entitami (�), - nebo plně nahrazeny (po první) neoddělitelní mezerou pro zachování vizuálního zarovnání ve výstupu Markdown. Výchozí hodnota je [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

Pokud je nastaveno na true, odstraňuje prázdné řádky nebo řádky obsahující pouze mezery z konečného výstupu Markdown. Výchozí je false.

**Vrací:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

Pokud je nastaveno na true, odstraňuje prázdné řádky nebo řádky obsahující pouze mezery z konečného výstupu Markdown. Výchozí je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

Vyskytuje se pro každý ne-SVG obrázek (bitmapa nebo metafile) během exportu do Markdownu. Umožňuje přizpůsobit způsob, jakým je obrázek uložen a odkazován. Pokud není ošetřeno, obrázek je uložen lokálně s relativním odkazem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Událost ukládání obrázku Markdown. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

Vyskytuje se pro každý SVG obrázek během exportu do Markdownu. Umožňuje přepsat výchozí ukládání a generování odkazu. Pokud není ošetřeno, SVG je uložen lokálně s relativním odkazem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Událost ukládání SVG obrázku Markdown. |