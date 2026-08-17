---
title: MarkdownSaveOptions
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les options qui contrôlent la façon dont la présentation doit être enregistrée au format markdown.
type: docs
url: /fr/com.aspose.slides/markdownsaveoptions/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Représente les options qui contrôlent la façon dont la présentation doit être enregistrée au format markdown.

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

| Constructeur | Description |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getExportType()](#getExportType--) | Spécifie la spécification markdown pour convertir la présentation. |
| [setExportType(int value)](#setExportType-int-) | Spécifie la spécification markdown pour convertir la présentation. |
| [getBasePath()](#getBasePath--) | Spécifie le chemin de base où le document avec les ressources sera enregistré. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Spécifie le chemin de base où le document avec les ressources sera enregistré. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Spécifie le nom du dossier où enregistrer les images. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Spécifie le nom du dossier où enregistrer les images. |
| [getNewLineType()](#getNewLineType--) | Spécifie si le document généré doit avoir des sauts de ligne \\\\r(Macintosh) ou \\\\n(Unix) ou \\\\r\\\\n(Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Spécifie si le document généré doit avoir des sauts de ligne \\\\r(Macintosh) ou \\\\n(Unix) ou \\\\r\\\\n(Windows). |
| [getShowComments()](#getShowComments--) | Spécifie si le document généré doit afficher les commentaires ou non. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Spécifie si le document généré doit afficher les commentaires ou non. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Spécifie si le document généré doit inclure les diapositives cachées ou non. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Spécifie si le document généré doit inclure les diapositives cachées ou non. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Spécifie si le document généré doit afficher le numéro de chaque diapositive ou non. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Spécifie si le document généré doit afficher le numéro de chaque diapositive ou non. |
| [getFlavor()](#getFlavor--) | Spécifie la spécification markdown pour convertir la présentation. |
| [setFlavor(int value)](#setFlavor-int-) | Spécifie la spécification markdown pour convertir la présentation. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Obtient ou définit la chaîne de format utilisée pour les en-têtes de numéro de diapositive dans la sortie Markdown. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Obtient ou définit la chaîne de format utilisée pour les en-têtes de numéro de diapositive dans la sortie Markdown. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Spécifie comment les espaces réguliers répétés doivent être traités lors de l’exportation Markdown. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Spécifie comment les espaces réguliers répétés doivent être traités lors de l’exportation Markdown. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Si la valeur est true, supprime les lignes vides ou contenant uniquement des espaces blancs du Markdown final. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Si la valeur est true, supprime les lignes vides ou contenant uniquement des espaces blancs du Markdown final. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Se produit pour chaque image non SVG (bitmap ou métafile) lors de l’exportation Markdown. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Se produit pour chaque image SVG lors de l’exportation Markdown. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Constructeur.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

Spécifie la spécification markdown pour convertir la présentation. La valeur par défaut est TextOnly.

**Renvoie :**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

Spécifie la spécification markdown pour convertir la présentation. La valeur par défaut est TextOnly.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

Spécifie le chemin de base où le document avec les ressources sera enregistré. La valeur par défaut est le répertoire courant de l’application.

**Renvoie :**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

Spécifie le chemin de base où le document avec les ressources sera enregistré. La valeur par défaut est le répertoire courant de l’application.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

Spécifie le nom du dossier où enregistrer les images. La valeur par défaut est Images.

**Renvoie :**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

Spécifie le nom du dossier où enregistrer les images. La valeur par défaut est Images.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

Spécifie si le document généré doit avoir des sauts de ligne \\\\r(Macintosh) ou \\\\n(Unix) ou \\\\r\\\\n(Windows). La valeur par défaut est Unix.

**Renvoie :**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

Spécifie si le document généré doit avoir des sauts de ligne \\\\r(Macintosh) ou \\\\n(Unix) ou \\\\r\\\\n(Windows). La valeur par défaut est Unix.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

Spécifie si le document généré doit afficher les commentaires ou non. La valeur par défaut est false.

**Renvoie :**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

Spécifie si le document généré doit afficher les commentaires ou non. La valeur par défaut est false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Spécifie si le document généré doit inclure les diapositives cachées ou non. La valeur par défaut est false.

**Renvoie :**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Spécifie si le document généré doit inclure les diapositives cachées ou non. La valeur par défaut est false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

Spécifie si le document généré doit afficher le numéro de chaque diapositive ou non. La valeur par défaut est false.

**Renvoie :**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

Spécifie si le document généré doit afficher le numéro de chaque diapositive ou non. La valeur par défaut est false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

Spécifie la spécification markdown pour convertir la présentation. La valeur par défaut est Multi-markdown.

**Renvoie :**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

Spécifie la spécification markdown pour convertir la présentation. La valeur par défaut est Multi-markdown.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

Obtient ou définit la chaîne de format utilisée pour les en-têtes de numéro de diapositive dans la sortie Markdown. Le format doit inclure le placeholder "\{0\}", qui sera remplacé par l’index de la diapositive lors de l’exportation. Exemple : "\# Slide \{0\}" donnera "\# Slide 1", "\# Slide 2", etc.

**Renvoie :**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

Obtient ou définit la chaîne de format utilisée pour les en-têtes de numéro de diapositive dans la sortie Markdown. Le format doit inclure le placeholder "\{0\}", qui sera remplacé par l’index de la diapositive lors de l’exportation. Exemple : "\# Slide \{0\}" donnera "\# Slide 1", "\# Slide 2", etc.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

Spécifie comment les espaces réguliers répétés doivent être traités lors de l’exportation Markdown. Cette propriété définit si les espaces consécutifs sont : - conservés comme espaces réguliers, - alternés entre espaces réguliers et entités d’espace insécable (�), - ou entièrement remplacés (après le premier) par un espace insécable afin de préserver l’alignement visuel dans la sortie Markdown. La valeur par défaut est [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Renvoie :**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

Spécifie comment les espaces réguliers répétés doivent être traités lors de l’exportation Markdown. Cette propriété définit si les espaces consécutifs sont : - conservés comme espaces réguliers, - alternés entre espaces réguliers et entités d’espace insécable (�), - ou entièrement remplacés (après le premier) par un espace insécable afin de préserver l’alignement visuel dans la sortie Markdown. La valeur par défaut est [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

Si la valeur est true, supprime les lignes vides ou contenant uniquement des espaces blancs du Markdown final. La valeur par défaut est false.

**Renvoie :**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

Si la valeur est true, supprime les lignes vides ou contenant uniquement des espaces blancs du Markdown final. La valeur par défaut est false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

Se produit pour chaque image non SVG (bitmap ou métafile) lors de l’exportation Markdown. Permet de personnaliser la façon dont l’image est enregistrée et référencée. Si non géré, l’image est enregistrée localement avec un lien relatif.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Événement d’enregistrement d’image Markdown. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

Se produit pour chaque image SVG lors de l’exportation Markdown. Permet de remplacer le comportement d’enregistrement et de génération de lien par défaut. Si non géré, le SVG est enregistré localement avec un lien relatif.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Événement d’enregistrement d’image SVG Markdown. |