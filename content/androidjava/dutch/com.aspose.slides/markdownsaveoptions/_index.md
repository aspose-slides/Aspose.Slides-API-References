---
title: MarkdownSaveOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt opties voor die bepalen hoe een presentatie moet worden opgeslagen in markdown.
type: docs
url: /nl/com.aspose.slides/markdownsaveoptions/
---
**Erfenis:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Stelt opties voor die bepalen hoe een presentatie moet worden opgeslagen in markdown.

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
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Ctor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getExportType()](#getExportType--) | Specificeert markdown-specificatie om presentatie te converteren. |
| [setExportType(int value)](#setExportType-int-) | Specificeert markdown-specificatie om presentatie te converteren. |
| [getBasePath()](#getBasePath--) | Specificeert het basispad waar het document met resources wordt opgeslagen. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Specificeert het basispad waar het document met resources wordt opgeslagen. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Specificeert de mapnaam om afbeeldingen op te slaan. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Specificeert de mapnaam om afbeeldingen op te slaan. |
| [getNewLineType()](#getNewLineType--) | Specificeert of het gegenereerde document nieuwe regels moet hebben \\r (Macintosh), \\n (Unix) of \\r\\n (Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Specificeert of het gegenereerde document nieuwe regels moet hebben \\r (Macintosh), \\n (Unix) of \\r\\n (Windows). |
| [getShowComments()](#getShowComments--) | Specificeert of het gegenereerde document opmerkingen moet weergeven of niet. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Specificeert of het gegenereerde document opmerkingen moet weergeven of niet. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specificeert of het gegenereerde document verborgen dia's moet opnemen of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specificeert of het gegenereerde document verborgen dia's moet opnemen of niet. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Specificeert of het gegenereerde document het nummer van elke dia moet weergeven of niet. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Specificeert of het gegenereerde document het nummer van elke dia moet weergeven of niet. |
| [getFlavor()](#getFlavor--) | Specificeert markdown-specificatie om presentatie te converteren. |
| [setFlavor(int value)](#setFlavor-int-) | Specificeert markdown-specificatie om presentatie te converteren. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Haalt op of stelt de opmaakreeks in die wordt gebruikt voor dia-nummerkoppen in de Markdown-output. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Haalt op of stelt de opmaakreeks in die wordt gebruikt voor dia-nummerkoppen in de Markdown-output. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Specificeert hoe herhaalde reguliere spatie-tekens moeten worden behandeld tijdens de Markdown-export. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Specificeert hoe herhaalde reguliere spatie-tekens moeten worden behandeld tijdens de Markdown-export. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Indien true, worden lege of alleen uit spaties bestaande regels uit de uiteindelijke Markdown-output verwijderd. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Indien true, worden lege of alleen uit spaties bestaande regels uit de uiteindelijke Markdown-output verwijderd. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Komt voor elke niet-SVG-afbeelding (bitmap of metafile) tijdens de Markdown-export. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Komt voor elke SVG-afbeelding tijdens de Markdown-export. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Ctor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

Specificeert markdown-specificatie om presentatie te converteren. Standaard is TextOnly.

**Retour:**  
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

Specificeert markdown-specificatie om presentatie te converteren. Standaard is TextOnly.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

Specificeert het basispad waar het document met resources wordt opgeslagen. Standaard is de huidige werkmap van de applicatie.

**Retour:**  
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

Specificeert het basispad waar het document met resources wordt opgeslagen. Standaard is de huidige werkmap van de applicatie.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

Specificeert de mapnaam om afbeeldingen op te slaan. Standaard is Images.

**Retour:**  
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

Specificeert de mapnaam om afbeeldingen op te slaan. Standaard is Images.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

Specificeert of het gegenereerde document nieuwe regels moet hebben \\r (Macintosh), \\n (Unix) of \\r\\n (Windows). Standaard is Unix.

**Retour:**  
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

Specificeert of het gegenereerde document nieuwe regels moet hebben \\r (Macintosh), \\n (Unix) of \\r\\n (Windows). Standaard is Unix.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

Specificeert of het gegenereerde document opmerkingen moet weergeven of niet. Standaard is false.

**Retour:**  
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

Specificeert of het gegenereerde document opmerkingen moet weergeven of niet. Standaard is false.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Specificeert of het gegenereerde document verborgen dia's moet opnemen of niet. Standaard is false.

**Retour:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specificeert of het gegenereerde document verborgen dia's moet opnemen of niet. Standaard is false.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

Specificeert of het gegenereerde document het nummer van elke dia moet weergeven of niet. Standaard is false.

**Retour:**  
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

Specificeert of het gegenereerde document het nummer van elke dia moet weergeven of niet. Standaard is false.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

Specificeert markdown-specificatie om presentatie te converteren. Standaard is Multi-markdown.

**Retour:**  
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

Specificeert markdown-specificatie om presentatie te converteren. Standaard is Multi-markdown.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

Haalt op of stelt de opmaakreeks in die wordt gebruikt voor dia-nummerkoppen in de Markdown-output. Het formaat moet de “\{0\}”-plaatsaanduiding bevatten, die tijdens export wordt vervangen door de dia-index. Voorbeeld: “\# Slide \{0\}” levert “\# Slide 1”, “\# Slide 2”, enz. op.

**Retour:**  
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

Haalt op of stelt de opmaakreeks in die wordt gebruikt voor dia-nummerkoppen in de Markdown-output. Het formaat moet de “\{0\}”-plaatsaanduiding bevatten, die tijdens export wordt vervangen door de dia-index. Voorbeeld: “\# Slide \{0\}” levert “\# Slide 1”, “\# Slide 2”, enz. op.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

Specificeert hoe herhaalde reguliere spatie-tekens moeten worden behandeld tijdens de Markdown-export. Deze eigenschap bepaalt of opeenvolgende spaties: - behouden blijven als reguliere spaties, - afwisselend worden opgeslagen als reguliere spatie en non-breaking-space-entiteit (�), - of volledig (na de eerste) worden vervangen door een non-breaking-space om visuele uitlijning in de Markdown-output te behouden. Standaardwaarde is [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Retour:**  
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

Specificeert hoe herhaalde reguliere spatie-tekens moeten worden behandeld tijdens de Markdown-export. Deze eigenschap bepaalt of opeenvolgende spaties: - behouden blijven als reguliere spaties, - afwisselend worden opgeslagen als reguliere spatie en non-breaking-space-entiteit (�), - of volledig (na de eerste) worden vervangen door een non-breaking-space om visuele uitlijning in de Markdown-output te behouden. Standaardwaarde is [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

Indien true, worden lege of alleen uit spaties bestaande regels uit de uiteindelijke Markdown-output verwijderd. Standaard is false.

**Retour:**  
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

Indien true, worden lege of alleen uit spaties bestaande regels uit de uiteindelijke Markdown-output verwijderd. Standaard is false.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

Komt voor elke niet-SVG-afbeelding (bitmap of metafile) tijdens de Markdown-export. Stelt aangepaste opslag en verwijzing van de afbeelding mogelijk. Indien niet afgehandeld, wordt de afbeelding lokaal opgeslagen met een relatieve link.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown-afbeelding-opslaagevenement. |
### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

Komt voor elke SVG-afbeelding tijdens de Markdown-export. Stelt overschrijven van de standaard opslaan- en linkgeneratie mogelijk. Indien niet afgehandeld, wordt de SVG lokaal opgeslagen met een relatieve link.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown-SVG-afbeelding-opslaagevenement. |