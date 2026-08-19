---
title: MarkdownSaveOptions
second_title: Aspose.Slides för Java API-referens
description: Representerar alternativ som styr hur presentationen ska sparas till markdown.
type: docs
url: /sv/com.aspose.slides/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Representerar alternativ som styr hur presentationen ska sparas till markdown.

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
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Ctor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getExportType()](#getExportType--) | Anger markdown-specifikationen för att konvertera presentationen. |
| [setExportType(int value)](#setExportType-int-) | Anger markdown-specifikationen för att konvertera presentationen. |
| [getBasePath()](#getBasePath--) | Anger den basväg där dokumentet med resurser sparas. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Anger den basväg där dokumentet med resurser sparas. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Anger mappnamnet för att spara bilder. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Anger mappnamnet för att spara bilder. |
| [getNewLineType()](#getNewLineType--) | Anger om det genererade dokumentet ska ha radbrytningar \\r (Macintosh) av \\n (Unix) eller \\r\\n (Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Anger om det genererade dokumentet ska ha radbrytningar \\r (Macintosh) av \\n (Unix) eller \\r\\n (Windows). |
| [getShowComments()](#getShowComments--) | Anger om det genererade dokumentet ska visa kommentarer eller inte. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Anger om det genererade dokumentet ska visa kommentarer eller inte. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Anger om det genererade dokumentet ska visa numret på varje bild eller inte. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Anger om det genererade dokumentet ska visa numret på varje bild eller inte. |
| [getFlavor()](#getFlavor--) | Anger markdown-specifikationen för att konvertera presentationen. |
| [setFlavor(int value)](#setFlavor-int-) | Anger markdown-specifikationen för att konvertera presentationen. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Hämtar eller anger formatsträngen som används för bildnummerrubriker i Markdown-utmatning. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Hämtar eller anger formatsträngen som används för bildnummerrubriker i Markdown-utmatning. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Anger hur upprepade vanliga mellanslagstecken ska hanteras under Markdown-export. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Anger hur upprepade vanliga mellanslagstecken ska hanteras under Markdown-export. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Om den är satt till true tas tomma eller endast blanksteg innehållande rader bort från den slutliga Markdown-utmatningen. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Om den är satt till true tas tomma eller endast blanksteg innehållande rader bort från den slutliga Markdown-utmatningen. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Uppstår för varje icke-SVG-bild (bitmap eller metafil) under Markdown-export. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Uppstår för varje SVG-bild under Markdown-export. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


Ctor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```


Anger markdown-specifikationen för att konvertera presentationen. Standardvärdet är TextOnly.

**Returnerar:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```


Anger markdown-specifikationen för att konvertera presentationen. Standardvärdet är TextOnly.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```


Anger den basväg där dokumentet med resurser sparas. Standardvärdet är den aktuella katalogen för programmet.

**Returnerar:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```


Anger den basväg där dokumentet med resurser sparas. Standardvärdet är den aktuella katalogen för programmet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```


Anger mappnamnet för att spara bilder. Standardvärdet är Images.

**Returnerar:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```


Anger mappnamnet för att spara bilder. Standardvärdet är Images.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```


Anger om det genererade dokumentet ska ha radbrytningar \\r (Macintosh) av \\n (Unix) eller \\r\\n (Windows). Standardvärdet är Unix.

**Returnerar:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```


Anger om det genererade dokumentet ska ha radbrytningar \\r (Macintosh) av \\n (Unix) eller \\r\\n (Windows). Standardvärdet är Unix.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```


Anger om det genererade dokumentet ska visa kommentarer eller inte. Standardvärdet är false.

**Returnerar:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```


Anger om det genererade dokumentet ska visa kommentarer eller inte. Standardvärdet är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standardvärdet är false.

**Returnerar:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standardvärdet är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```


Anger om det genererade dokumentet ska visa numret på varje bild eller inte. Standardvärdet är false.

**Returnerar:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```


Anger om det genererade dokumentet ska visa numret på varje bild eller inte. Standardvärdet är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```


Anger markdown-specifikationen för att konvertera presentationen. Standardvärdet är Multi-markdown.

**Returnerar:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```


Anger markdown-specifikationen för att konvertera presentationen. Standardvärdet är Multi-markdown.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```


Hämtar eller anger formatsträngen som används för bildnummerrubriker i Markdown-utmatning. Formatet måste innehålla platshållaren "\{0\}", som ersätts med bildens index vid export. Exempel: "\# Slide \{0\}" ger "\# Slide 1", "\# Slide 2" osv.

**Returnerar:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```


Hämtar eller anger formatsträngen som används för bildnummerrubriker i Markdown-utmatning. Formatet måste innehålla platshållaren "\{0\}", som ersätts med bildens index vid export. Exempel: "\# Slide \{0\}" ger "\# Slide 1", "\# Slide 2" osv.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```


Anger hur upprepade vanliga mellanslagstecken ska hanteras under Markdown-export. Denna egenskap definierar om på varandra följande mellanslag: - bevaras som vanliga mellanslag, - växlas mellan vanliga mellanslag och icke-brytande mellanslagstecken (�), - eller helt ersätts (efter det första) med ett icke-brytande mellanslag för att bevara visuell justering i Markdown-utmatning. Standardvärdet är [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Returnerar:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```


Anger hur upprepade vanliga mellanslagstecken ska hanteras under Markdown-export. Denna egenskap definierar om på varandra följande mellanslag: - bevaras som vanliga mellanslag, - växlas mellan vanliga mellanslag och icke-brytande mellanslagstecken (�), - eller helt ersätts (efter det första) med ett icke-brytande mellanslag för att bevara visuell justering i Markdown-utmatning. Standardvärdet är [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```


Om den är satt till true tas tomma eller endast blanksteg innehållande rader bort från den slutliga Markdown-utmatningen. Standardvärdet är false.

**Returnerar:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```


Om den är satt till true tas tomma eller endast blanksteg innehållande rader bort från den slutliga Markdown-utmatningen. Standardvärdet är false.

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
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown-bildsparningsevent. |
### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```


Uppstår för varje SVG-bild under Markdown-export. Tillåter att åsidosätta standardlagring och länkgenerering. Om den inte hanteras sparas SVG:n lokalt med en relativ länk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown SVG-bildsparningsevent. |