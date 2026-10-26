---
title: MarkdownSaveOptions
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje možnosti, které řídí, jak má být prezentace uložena do formátu markdown.
type: docs
url: /cs/com.aspose.slides/markdownsaveoptions/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Reprezentuje možnosti, které řídí, jak má být prezentace uložena do formátu markdown.

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
| [getExportType()](#getExportType--) | Určuje specifikaci markdown pro převod prezentace. |
| [setExportType(int value)](#setExportType-int-) | Určuje specifikaci markdown pro převod prezentace. |
| [getBasePath()](#getBasePath--) | Určuje základní cestu, kde bude dokument s prostředky uložen. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Určuje základní cestu, kde bude dokument s prostředky uložen. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Určuje název složky pro ukládání obrázků. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Určuje název složky pro ukládání obrázků. |
| [getNewLineType()](#getNewLineType--) | Určuje, zda má vygenerovaný dokument mít nové řádky \\r(Macintosh) nebo \\n(Unix) nebo \\r\\n(Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Určuje, zda má vygenerovaný dokument mít nové řádky \\r(Macintosh) nebo \\n(Unix) nebo \\r\\n(Windows). |
| [getShowComments()](#getShowComments--) | Určuje, zda má vygenerovaný dokument zobrazovat komentáře, nebo ne. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Určuje, zda má vygenerovaný dokument zobrazovat komentáře, nebo ne. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Určuje, zda má vygenerovaný dokument zobrazovat číslo každého snímku, nebo ne. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Určuje, zda má vygenerovaný dokument zobrazovat číslo každého snímku, nebo ne. |
| [getFlavor()](#getFlavor--) | Určuje specifikaci markdown pro převod prezentace. |
| [setFlavor(int value)](#setFlavor-int-) | Určuje specifikaci markdown pro převod prezentace. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Získá nebo nastaví řetězec formátu používaný pro záhlaví číslování snímků ve výstupu Markdown. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Získá nebo nastaví řetězec formátu používaný pro záhlaví číslování snímků ve výstupu Markdown. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Určuje, jak mají být během exportu Markdown zpracovávány opakované běžné mezery. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Určuje, jak mají být během exportu Markdown zpracovávány opakované běžné mezery. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Pokud je nastaveno na true, odstraňuje prázdné řádky nebo řádky obsahující pouze mezery z konečného výstupu Markdown. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Pokud je nastaveno na true, odstraňuje prázdné řádky nebo řádky obsahující pouze mezery z konečného výstupu Markdown. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Vyskytuje se pro každý ne-SVG obrázek (bitmapa nebo metafile) během exportu Markdown. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Vyskytuje se pro každý SVG obrázek během exportu Markdown. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Konstruktor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

Určuje specifikaci markdown pro převod prezentace. Výchozí je  TextOnly .

**Vrací:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

Určuje specifikaci markdown pro převod prezentace. Výchozí je  TextOnly .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

Určuje základní cestu, kde bude dokument s prostředky uložen. Výchozí je aktuální adresář aplikace.

**Vrací:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

Určuje základní cestu, kde bude dokument s prostředky uložen. Výchozí je aktuální adresář aplikace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

Určuje název složky pro ukládání obrázků. Výchozí je  Images .

**Vrací:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

Určuje název složky pro ukládání obrázků. Výchozí je  Images .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

Určuje, zda má vygenerovaný dokument mít nové řádky \\r(Macintosh) nebo \\n(Unix) nebo \\r\\n(Windows). Výchozí je  Unix .

**Vrací:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

Určuje, zda má vygenerovaný dokument mít nové řádky \\r(Macintosh) nebo \\n(Unix) nebo \\r\\n(Windows). Výchozí je  Unix .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

Určuje, zda má vygenerovaný dokument zobrazovat komentáře, nebo ne. Výchozí je false.

**Vrací:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

Určuje, zda má vygenerovaný dokument zobrazovat komentáře, nebo ne. Výchozí je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. Výchozí je false.

**Vrací:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. Výchozí je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

Určuje, zda má vygenerovaný dokument zobrazovat číslo každého snímku, nebo ne. Výchozí je false.

**Vrací:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

Určuje, zda má vygenerovaný dokument zobrazovat číslo každého snímku, nebo ne. Výchozí je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

Určuje specifikaci markdown pro převod prezentace. Výchozí je  Multi-markdown .

**Vrací:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

Určuje specifikaci markdown pro převod prezentace. Výchozí je  Multi-markdown .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

Získá nebo nastaví řetězec formátu používaný pro záhlaví číslování snímků ve výstupu Markdown. Formát musí obsahovat zástupný znak "\{0\}", který bude během exportu nahrazen indexem snímku. Příklad: "\# Slide \{0\}" vytvoří "\# Slide 1", "\# Slide 2" atd.

**Vrací:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

Získá nebo nastaví řetězec formátu používaný pro záhlaví číslování snímků ve výstupu Markdown. Formát musí obsahovat zástupný znak "\{0\}", který bude během exportu nahrazen indexem snímku. Příklad: "\# Slide \{0\}" vytvoří "\# Slide 1", "\# Slide 2" atd.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

Určuje, jak mají být během exportu Markdown zpracovávány opakované běžné mezery. Tato vlastnost určuje, zda jsou sousední mezery: - zachovány jako běžné mezery, - střídány mezi běžnými mezerami a entitami nezlomitelných mezer (�), - nebo kompletně nahrazeny (po první) nezlomitelnou mezerou pro zachování vizuálního zarovnání ve výstupu Markdown. Výchozí hodnota je [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Vrací:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

Určuje, jak mají být během exportu Markdown zpracovávány opakované běžné mezery. Tato vlastnost určuje, zda jsou sousední mezery: - zachovány jako běžné mezery, - střídány mezi běžnými mezerami a entitami nezlomitelných mezer (�), - nebo kompletně nahrazeny (po první) nezlomitelnou mezerou pro zachování vizuálního zarovnání ve výstupu Markdown. Výchozí hodnota je [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

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

Vyskytuje se pro každý ne-SVG obrázek (bitmapa nebo metafile) během exportu Markdown. Umožňuje přizpůsobit, jak je obrázek uložen a odkazován. Pokud není ošetřeno, obrázek je uložen lokálně s relativním odkazem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Událost ukládání obrázku Markdown. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

Vyskytuje se pro každý SVG obrázek během exportu Markdown. Umožňuje přepsat výchozí ukládání a generování odkazu. Pokud není ošetřeno, SVG je uložen lokálně s relativním odkazem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Událost ukládání SVG obrázku Markdown. |