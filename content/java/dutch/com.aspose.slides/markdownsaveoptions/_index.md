---
title: MarkdownSaveOptions
second_title: Aspose.Slides voor Java API-referentie
description: Stelt opties voor die bepalen hoe een presentatie moet worden opgeslagen als markdown.
type: docs
url: /nl/com.aspose.slides/markdownsaveoptions/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Stelt opties voor die bepalen hoe een presentatie moet worden opgeslagen als markdown.

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
## Constructeurs

| Constructor | Beschrijving |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Ctor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getExportType()](#getExportType--) | Specificeert markdown-specificatie om de presentatie te converteren. |
| [setExportType(int value)](#setExportType-int-) | Specificeert markdown-specificatie om de presentatie te converteren. |
| [getBasePath()](#getBasePath--) | Specificeert het basispad waar het document met bronnen wordt opgeslagen. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Specificeert het basispad waar het document met bronnen wordt opgeslagen. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Specificeert de mapnaam om afbeeldingen op te slaan. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Specificeert de mapnaam om afbeeldingen op te slaan. |
| [getNewLineType()](#getNewLineType--) | Specificeert of het gegenereerde document nieuwe regels \\r (Macintosh) of \\n (Unix) of \\r\\n (Windows) moet hebben. |
| [setNewLineType(int value)](#setNewLineType-int-) | Specificeert of het gegenereerde document nieuwe regels \\r (Macintosh) of \\n (Unix) of \\r\\n (Windows) moet hebben. |
| [getShowComments()](#getShowComments--) | Specificeert of het gegenereerde document opmerkingen moet weergeven of niet. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Specificeert of het gegenereerde document opmerkingen moet weergeven of niet. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specificeert of het gegenereerde document verborgen dia’s moet bevatten of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specificeert of het gegenereerde document verborgen dia’s moet bevatten of niet. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Specificeert of het gegenereerde document het nummer van elke dia moet weergeven of niet. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Specificeert of het gegenereerde document het nummer van elke dia moet weergeven of niet. |
| [getFlavor()](#getFlavor--) | Specificeert markdown-specificatie om de presentatie te converteren. |
| [setFlavor(int value)](#setFlavor-int-) | Specificeert markdown-specificatie om de presentatie te converteren. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Geeft de opmaakstring terug of stelt deze in die wordt gebruikt voor dia-nummerkoppen in Markdown-output. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Geeft de opmaakstring terug of stelt deze in die wordt gebruikt voor dia-nummerkoppen in Markdown-output. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Specificeert hoe herhaalde reguliere spatie-tekens moeten worden afgehandeld tijdens de Markdown-export. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Specificeert hoe herhaalde reguliere spatie-tekens moeten worden afgehandeld tijdens de Markdown-export. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Indien ingesteld op true, verwijdert lege of alleen uit spaties bestaande regels uit de uiteindelijke Markdown-output. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Indien ingesteld op true, verwijdert lege of alleen uit spaties bestaande regels uit de uiteindelijke Markdown-output. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Komt voor bij elke niet-SVG-afbeelding (bitmap of metabestand) tijdens de Markdown-export. Hiermee kan worden aangepast hoe de afbeelding wordt opgeslagen en verwezen. Als dit niet wordt afgehandeld, wordt de afbeelding lokaal opgeslagen met een relatieve link. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Komt voor bij elke SVG-afbeelding tijdens de Markdown-export. Hiermee kan de standaardopslag en linkgeneratie worden overschreven. Als dit niet wordt afgehandeld, wordt de SVG lokaal opgeslagen met een relatieve link. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Ctor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

Specificeert markdown-specificatie om de presentatie te converteren. Standaard is TextOnly.

**Retour:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

Specificeert markdown-specificatie om de presentatie te converteren. Standaard is TextOnly.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

Specificeert het basispad waar het document met bronnen wordt opgeslagen. Standaard is de huidige map van de toepassing.

**Retour:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

Specificeert het basispad waar het document met bronnen wordt opgeslagen. Standaard is de huidige map van de toepassing.

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

Specificeert of het gegenereerde document nieuwe regels \\r (Macintosh) of \\n (Unix) of \\r\\n (Windows) moet hebben. Standaard is Unix.

**Retour:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

Specificeert of het gegenereerde document nieuwe regels \\r (Macintosh) of \\n (Unix) of \\r\\n (Windows) moet hebben. Standaard is Unix.

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

Specificeert of het gegenereerde document verborgen dia’s moet bevatten of niet. Standaard is false.

**Retour:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specificeert of het gegenereerde document verborgen dia’s moet bevatten of niet. Standaard is false.

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

Specificeert markdown-specificatie om de presentatie te converteren. Standaard is Multi-markdown.

**Retour:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

Specificeert markdown-specificatie om de presentatie te converteren. Standaard is Multi-markdown.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

Geeft de opmaakstring terug of stelt deze in die wordt gebruikt voor dia-nummerkoppen in Markdown-output. Het formaat moet de “\{0\}”-plaatsaanduiding bevatten, die tijdens export wordt vervangen door het dia-index. Voorbeeld: “\# Slide \{0\}” produceert “\# Slide 1”, “\# Slide 2”, enz.

**Retour:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

Geeft de opmaakstring terug of stelt deze in die wordt gebruikt voor dia-nummerkoppen in Markdown-output. Het formaat moet de “\{0\}”-plaatsaanduiding bevatten, die tijdens export wordt vervangen door het dia-index. Voorbeeld: “\# Slide \{0\}” produceert “\# Slide 1”, “\# Slide 2”, enz.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

Specificeert hoe herhaalde reguliere spatie-tekens moeten worden afgehandeld tijdens de Markdown-export. Deze eigenschap bepaalt of opeenvolgende spaties: - behouden blijven als reguliere spatie-tekens, - afwisselend worden weergegeven als reguliere spaties en niet-brekende-spatie-entiteiten (�), - of volledig worden vervangen (na de eerste) door een niet-brekende spatie om visuele uitlijning te behouden in de Markdown-output. De standaardwaarde is [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Retour:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

Specificeert hoe herhaalde reguliere spatie-tekens moeten worden afgehandeld tijdens de Markdown-export. Deze eigenschap bepaalt of opeenvolgende spaties: - behouden blijven als reguliere spatie-tekens, - afwisselend worden weergegeven als reguliere spaties en niet-brekende-spatie-entiteiten (�), - of volledig worden vervangen (na de eerste) door een niet-brekende spatie om visuele uitlijning te behouden in de Markdown-output. De standaardwaarde is [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

Indien ingesteld op true, verwijdert lege of alleen uit spaties bestaande regels uit de uiteindelijke Markdown-output. Standaard is false.

**Retour:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

Indien ingesteld op true, verwijdert lege of alleen uit spaties bestaande regels uit de uiteindelijke Markdown-output. Standaard is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

Komt voor bij elke niet-SVG-afbeelding (bitmap of metabestand) tijdens de Markdown-export. Hiermee kan worden aangepast hoe de afbeelding wordt opgeslagen en verwezen. Als dit niet wordt afgehandeld, wordt de afbeelding lokaal opgeslagen met een relatieve link.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown-afbeelding-opslaanevenement. |
### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

Komt voor bij elke SVG-afbeelding tijdens de Markdown-export. Hiermee kan de standaardopslag en linkgeneratie worden overschreven. Als dit niet wordt afgehandeld, wordt de SVG lokaal opgeslagen met een relatieve link.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown-SVG-afbeelding-opslaanevenement. |