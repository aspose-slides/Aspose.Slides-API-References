---
title: MarkdownSaveOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar alternativ som styr hur en presentation ska sparas som markdown.
type: docs
url: /sv/com.aspose.slides/markdownsaveoptions/
---
**Arv:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Representerar alternativ som styr hur en presentation ska sparas som markdown.

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
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getExportType()](#getExportType--) | Anger markdown-specifikationen för att konvertera presentationen. |
| [setExportType(int value)](#setExportType-int-) | Anger markdown-specifikationen för att konvertera presentationen. |
| [getBasePath()](#getBasePath--) | Anger sökvägen där dokumentet med resurser ska sparas. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Anger sökvägen där dokumentet med resurser ska sparas. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Anger mappnamnet för att spara bilder. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Anger mappnamnet för att spara bilder. |
| [getNewLineType()](#getNewLineType--) | Anger om det genererade dokumentet ska ha radbrytningar \\r(Macintosh) , \\n(Unix) eller \\r\\n(Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Anger om det genererade dokumentet ska ha radbrytningar \\r(Macintosh) , \\n(Unix) eller \\r\\n(Windows). |
| [getShowComments()](#getShowComments--) | Anger om det genererade dokumentet ska visa kommentarer eller inte. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Anger om det genererade dokumentet ska visa kommentarer eller inte. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Anger om det genererade dokumentet ska visa numret på varje bild eller inte. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Anger om det genererade dokumentet ska visa numret på varje bild eller inte. |
| [getFlavor()](#getFlavor--) | Anger markdown-specifikationen för att konvertera presentationen. |
| [setFlavor(int value)](#setFlavor-int-) | Anger markdown-specifikationen för att konvertera presentationen. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Hämtar eller anger formatsträngen som används för bildnummerrubriker i Markdown-utdata. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Hämtar eller anger formatsträngen som används för bildnummerrubriker i Markdown-utdata. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Anger hur upprepade vanliga mellanslagstecken ska hanteras vid Markdown-export. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Anger hur upprepade vanliga mellanslagstecken ska hanteras vid Markdown-export. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Om satt till true, tas tomma eller enbart blankstegslinjer bort från det slutgiltiga Markdown-utdata. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Om satt till true, tas tomma eller enbart blankstegslinjer bort från det slutgiltiga Markdown-utdata. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Uppstår för varje icke-SVG-bild (bitmap eller metafil) under Markdown-export. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Uppstår för varje SVG-bild under Markdown-export. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


Konstruktor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```


Anger markdown-specifikationen för att konvertera presentationen. Standardvärde är  TextOnly .

**Returnerar:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```


Anger markdown-specifikationen för att konvertera presentationen. Standardvärde är  TextOnly .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```


Anger sökvägen där dokumentet med resurser ska sparas. Standardvärde är den aktuella katalogen för applikationen.

**Returnerar:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```


Anger sökvägen där dokumentet med resurser ska sparas. Standardvärde är den aktuella katalogen för applikationen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```


Anger mappnamnet för att spara bilder. Standardvärde är  Images .

**Returnerar:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```


Anger mappnamnet för att spara bilder. Standardvärde är  Images .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```


Anger om det genererade dokumentet ska ha radbrytningar \\r(Macintosh) , \\n(Unix) eller \\r\\n(Windows). Standardvärde är  Unix .

**Returnerar:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```


Anger om det genererade dokumentet ska ha radbrytningar \\r(Macintosh) , \\n(Unix) eller \\r\\n(Windows). Standardvärde är  Unix .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```


Anger om det genererade dokumentet ska visa kommentarer eller inte. Standardvärde är false.

**Returnerar:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```


Anger om det genererade dokumentet ska visa kommentarer eller inte. Standardvärde är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standardvärde är false.

**Returnerar:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standardvärde är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```


Anger om det genererade dokumentet ska visa numret på varje bild eller inte. Standardvärde är false.

**Returnerar:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```


Anger om det genererade dokumentet ska visa numret på varje bild eller inte. Standardvärde är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```


Anger markdown-specifikationen för att konvertera presentationen. Standardvärde är  Multi-markdown .

**Returnerar:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```


Anger markdown-specifikationen för att konvertera presentationen. Standardvärde är  Multi-markdown .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```


Hämtar eller anger formatsträngen som används för bildnummerrubriker i Markdown-utdata. Formatet måste innehålla platshållaren "\{0\}", som kommer att ersättas med bildens index vid export. Exempel: "\# Slide \{0\}" ger "\# Slide 1", "\# Slide 2", osv.

**Returnerar:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```


Hämtar eller anger formatsträngen som används för bildnummerrubriker i Markdown-utdata. Formatet måste innehålla platshållaren "\{0\}", som kommer att ersättas med bildens index vid export. Exempel: "\# Slide \{0\}" ger "\# Slide 1", "\# Slide 2", osv.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```


Anger hur upprepade vanliga mellanslagstecken ska hanteras vid Markdown-export. Denna egenskap anger om på varandra följande mellanslag: - bevaras som vanliga mellanslagstecken, - växlas mellan vanliga mellanslag och icke-brytande mellanslagstecken (�), - eller helt ersätts (efter det första) med ett icke-brytande mellanslag för att bevara visuell justering i Markdown-utdata. Standardvärdet är [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Returnerar:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```


Anger hur upprepade vanliga mellanslagstecken ska hanteras vid Markdown-export. Denna egenskap anger om på varandra följande mellanslag: - bevaras som vanliga mellanslagstecken, - växlas mellan vanliga mellanslag och icke-brytande mellanslagstecken (�), - eller helt ersätts (efter det första) med ett icke-brytande mellanslag för att bevara visuell justering i Markdown-utdata. Standardvärdet är [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```


Om satt till true, tas tomma eller enbart blankstegslinjer bort från det slutgiltiga Markdown-utdata. Standardvärde är false.

**Returnerar:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```


Om satt till true, tas tomma eller enbart blankstegslinjer bort från det slutgiltiga Markdown-utdata. Standardvärde är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```


Uppstår för varje icke-SVG-bild (bitmap eller metafil) under Markdown-export. Tillåter anpassning av hur bilden sparas och refereras. Om den inte hanteras sparas bilden lokalt med en relativ länk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown-händelse för bildsparning. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```


Uppstår för varje SVG-bild under Markdown-export. Tillåter att standardlagring och länkgenerering överskrivs. Om den inte hanteras sparas SVG:n lokalt med en relativ länk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown-SVG-händelse för bildsparning. |