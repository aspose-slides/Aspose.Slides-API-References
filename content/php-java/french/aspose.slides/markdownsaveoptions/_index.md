---
title: MarkdownSaveOptions
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/markdownsaveoptions/
---
## classe MarkdownSaveOptions

 Représente les options qui contrôlent la façon dont une présentation doit être enregistrée au format markdown.
 
### MarkdownSaveOptions {#MarkdownSaveOptions}

| Nom | Description |
| --- | --- |
| MarkdownSaveOptions() | Constructeur. |

 **Renvoie :**  
MarkdownSaveOptions


---


### getBasePath {#getBasePath}

| Nom | Description |
| --- | --- |
| getBasePath () | Spécifie le chemin de base où le document avec ses ressources sera enregistré. La valeur par défaut est le répertoire courant de l'application. |

 **Renvoie :**  
String


---


### getExportType {#getExportType}

| Nom | Description |
| --- | --- |
| getExportType () | Spécifie la spécification markdown utilisée pour convertir la présentation. La valeur par défaut est TextOnly. |

 **Renvoie :**  
int


---


### getFlavor {#getFlavor}

| Nom | Description |
| --- | --- |
| getFlavor () | Spécifie la spécification markdown utilisée pour convertir la présentation. La valeur par défaut est Multi-markdown. |

 **Renvoie :**  
int


---


### getHandleRepeatedSpaces {#getHandleRepeatedSpaces}

| Nom | Description |
| --- | --- |
| getHandleRepeatedSpaces () | Spécifie comment les caractères d'espace réguliers répétés doivent être gérés lors de l'exportation Markdown. Cette propriété définit si les espaces consécutifs sont : - conservés comme des caractères d'espace normaux, - alternés entre espaces normaux et entités d'espace insécable (&nbsp;), - ou entièrement remplacés (après le premier) par un espace insécable afin de préserver l'alignement visuel dans la sortie Markdown. La valeur par défaut est HandleRepeatedSpaces#AlternateSpacesToNbsp. |

 **Renvoie :**  
int


---


### getImagesSaveFolderName {#getImagesSaveFolderName}

| Nom | Description |
| --- | --- |
| getImagesSaveFolderName () | Spécifie le nom du dossier où enregistrer les images. La valeur par défaut est Images. |

 **Renvoie :**  
String


---


### getNewLineType {#getNewLineType}

| Nom | Description |
| --- | --- |
| getNewLineType () | Spécifie si le document généré doit utiliser les sauts de ligne \\r (Macintosh), \\n (Unix) ou \\r\\n (Windows). La valeur par défaut est Unix. |

 **Renvoie :**  
int


---


### getRemoveEmptyLines {#getRemoveEmptyLines}

| Nom | Description |
| --- | --- |
| getRemoveEmptyLines () | Si la valeur est vraie, supprime les lignes vides ou contenant uniquement des espaces blancs de la sortie Markdown finale. La valeur par défaut est false. |

 **Renvoie :**  
boolean


---


### getShowComments {#getShowComments}

| Nom | Description |
| --- | --- |
| getShowComments () | Spécifie si le document généré doit afficher les commentaires ou non. La valeur par défaut est false. |

 **Renvoie :**  
boolean


---


### getShowHiddenSlides {#getShowHiddenSlides}

| Nom | Description |
| --- | --- |
| getShowHiddenSlides () | Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false. |

 **Renvoie :**  
boolean


---


### getShowSlideNumber {#getShowSlideNumber}

| Nom | Description |
| --- | --- |
| getShowSlideNumber () | Spécifie si le document généré doit afficher le numéro de chaque diapositive ou non. La valeur par défaut est false. |

 **Renvoie :**  
boolean


---


### getSlideNumberFormat {#getSlideNumberFormat}

| Nom | Description |
| --- | --- |
| getSlideNumberFormat () | Obtient ou définit la chaîne de format utilisée pour les en-têtes de numéros de diapositive dans la sortie Markdown. Le format doit inclure l'espace réservé \"{0}\", qui sera remplacé par l'indice de la diapositive lors de l'exportation. Exemple : \"# Slide {0}\" produira \"# Slide 1\", \"# Slide 2\", etc. |

 **Renvoie :**  
String

 **Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée si la chaîne de format ne contient pas le paramètre \"{0}\". |


---


### setBasePath {#setBasePath}

| Nom | Description |
| --- | --- |
| setBasePath (String) | Spécifie le chemin de base où le document avec ses ressources sera enregistré. La valeur par défaut est le répertoire courant de l'application. |

 **Renvoie :**  
void


---


### setExportType {#setExportType}

| Nom | Description |
| --- | --- |
| setExportType (int) | Spécifie la spécification markdown utilisée pour convertir la présentation. La valeur par défaut est TextOnly. |

 **Renvoie :**  
void


---


### setFlavor {#setFlavor}

| Nom | Description |
| --- | --- |
| setFlavor (int) | Spécifie la spécification markdown utilisée pour convertir la présentation. La valeur par défaut est Multi-markdown. |

 **Renvoie :**  
void


---


### setHandleRepeatedSpaces {#setHandleRepeatedSpaces}

| Nom | Description |
| --- | --- |
| setHandleRepeatedSpaces (int) | Spécifie comment les caractères d'espace réguliers répétés doivent être gérés lors de l'exportation Markdown. Cette propriété définit si les espaces consécutifs sont : - conservés comme des caractères d'espace normaux, - alternés entre espaces normaux et entités d'espace insécable (&nbsp;), - ou entièrement remplacés (après le premier) par un espace insécable afin de préserver l'alignement visuel dans la sortie Markdown. La valeur par défaut est HandleRepeatedSpaces#AlternateSpacesToNbsp. |

 **Renvoie :**  
void


---


### setImageSaving {#setImageSaving}

| Nom | Description |
| --- | --- |
| setImageSaving ([MarkdownSaveOptions.MarkdownImageSavingHandler](../markdownsaveoptions.markdownimagesavinghandler)) | Se produit pour chaque image non SVG (bitmap ou métafile) lors de l'exportation Markdown. Permet de personnaliser la façon dont l'image est enregistrée et référencée. Si l'événement n'est pas traité, l'image est enregistrée localement avec un lien relatif. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| event | [MarkdownSaveOptions.MarkdownImageSavingHandler](../markdownsaveoptions.markdownimagesavinghandler) | Événement d'enregistrement d'image Markdown. |

 **Renvoie :**  
void


---


### setImagesSaveFolderName {#setImagesSaveFolderName}

| Nom | Description |
| --- | --- |
| setImagesSaveFolderName (String) | Spécifie le nom du dossier où enregistrer les images. La valeur par défaut est Images. |

 **Renvoie :**  
void


---


### setNewLineType {#setNewLineType}

| Nom | Description |
| --- | --- |
| setNewLineType (int) | Spécifie si le document généré doit utiliser les sauts de ligne \\r (Macintosh), \\n (Unix) ou \\r\\n (Windows). La valeur par défaut est Unix. |

 **Renvoie :**  
void


---


### setRemoveEmptyLines {#setRemoveEmptyLines}

| Nom | Description |
| --- | --- |
| setRemoveEmptyLines (boolean) | Si la valeur est vraie, supprime les lignes vides ou contenant uniquement des espaces blancs de la sortie Markdown finale. La valeur par défaut est false. |

 **Renvoie :**  
void


---


### setShowComments {#setShowComments}

| Nom | Description |
| --- | --- |
| setShowComments (boolean) | Spécifie si le document généré doit afficher les commentaires ou non. La valeur par défaut est false. |

 **Renvoie :**  
void


---


### setShowHiddenSlides {#setShowHiddenSlides}

| Nom | Description |
| --- | --- |
| setShowHiddenSlides (boolean) | Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false. |

 **Renvoie :**  
void


---


### setShowSlideNumber {#setShowSlideNumber}

| Nom | Description |
| --- | --- |
| setShowSlideNumber (boolean) | Spécifie si le document généré doit afficher le numéro de chaque diapositive ou non. La valeur par défaut est false. |

 **Renvoie :**  
void


---


### setSlideNumberFormat {#setSlideNumberFormat}

| Nom | Description |
| --- | --- |
| setSlideNumberFormat (String) | Obtient ou définit la chaîne de format utilisée pour les en-têtes de numéros de diapositive dans la sortie Markdown. Le format doit inclure l'espace réservé \"{0}\", qui sera remplacé par l'indice de la diapositive lors de l'exportation. Exemple : \"# Slide {0}\" produira \"# Slide 1\", \"# Slide 2\", etc. |

 **Renvoie :**  
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée si la chaîne de format ne contient pas le paramètre \"{0}\". |


---


### setSvgImageSaving {#setSvgImageSaving}

| Nom | Description |
| --- | --- |
| setSvgImageSaving ([MarkdownSaveOptions.MarkdownSvgImageSavingHandler](../markdownsaveoptions.markdownsvgimagesavinghandler)) | Se produit pour chaque image SVG lors de l'exportation Markdown. Permet de remplacer le comportement d'enregistrement et de génération de lien par défaut. Si l'événement n'est pas traité, le SVG est enregistré localement avec un lien relatif. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| event | [MarkdownSaveOptions.MarkdownSvgImageSavingHandler](../markdownsaveoptions.markdownsvgimagesavinghandler) | Événement d'enregistrement d'image SVG Markdown. |

 **Renvoie :**  
void


---