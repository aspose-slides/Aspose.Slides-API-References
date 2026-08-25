---
title: HtmlOptions
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/htmloptions/
---
## HtmlOptions classe

 Représente des options d'exportation HTML.
 
### HtmlOptions {#HtmlOptions}

| Nom | Description |
| --- | --- |
| HtmlOptions([VideoPlayerHtmlController](../videoplayerhtmlcontroller)) | Crée un nouvel objet HtmlOptions spécifiant le rappel. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| linkEmbedController | [VideoPlayerHtmlController](../videoplayerhtmlcontroller) | Objet de rappel qui contrôle l'enregistrement du projet. |

**Renvoie:**
HtmlOptions


---


### HtmlOptions {#HtmlOptions}

| Nom | Description |
| --- | --- |
| HtmlOptions() | Crée un nouvel objet HtmlOptions pour enregistrer dans un fichier HTML unique. |

**Renvoie:**
HtmlOptions


---


### getDeletePicturesCroppedAreas {#getDeletePicturesCroppedAreas}

| Nom | Description |
| --- | --- |
| getDeletePicturesCroppedAreas () | Un drapeau boolean indique si les parties découpées restent dans le document. Si true, les parties découpées seront supprimées, si false elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux). |

**Renvoie:**
boolean


---


### getDisableFontLigatures {#getDisableFontLigatures}

| Nom | Description |
| --- | --- |
| getDisableFontLigatures () | Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser les ligatures. Lorsque la valeur est true, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur false. |

**Renvoie:**
boolean


---


### getHtmlFormatter {#getHtmlFormatter}

| Nom | Description |
| --- | --- |
| getHtmlFormatter () | Renvoie ou définit le modèle HTML. Lecture/écriture IHtmlFormatter. |

**Renvoie:**
[HtmlFormatter](../htmlformatter)


---


### getInkOptions {#getInkOptions}

| Nom | Description |
| --- | --- |
| getInkOptions () | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. Lecture seule IInkOptions |

**Renvoie:**
[InkOptions](../inkoptions)


---


### getJpegQuality {#getJpegQuality}

| Nom | Description |
| --- | --- |
| getJpegQuality () | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF. Lecture/écriture byte. N'a d'effet que lorsqu'un document contient des images JPEG. Utilisez cette propriété pour obtenir ou définir la qualité des images d'un document lors de l'enregistrement au format PDF. La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais la compression maximale et 100 signifie la meilleure qualité mais la compression minimale. La valeur par défaut est 95. |

**Renvoie:**
byte


---


### getPicturesCompression {#getPicturesCompression}

| Nom | Description |
| --- | --- |
| getPicturesCompression () | Représente le niveau de compression des images |

**Renvoie:**
int


---


### getShowHiddenSlides {#getShowHiddenSlides}

| Nom | Description |
| --- | --- |
| getShowHiddenSlides () | Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false. |

**Renvoie:**
boolean


---


### getSlideImageFormat {#getSlideImageFormat}

| Nom | Description |
| --- | --- |
| getSlideImageFormat () | Renvoie ou définit les options de format d'image des diapositives. Lecture/écriture ISlideImageFormat. |

**Renvoie:**
[SlideImageFormat](../slideimageformat)


---


### getSlidesLayoutOptions {#getSlidesLayoutOptions}

| Nom | Description |
| --- | --- |
| getSlidesLayoutOptions () | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation ISlidesLayoutOptions. |

**Renvoie:**
[NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), [HandoutLayoutingOptions](../handoutlayoutingoptions)


---


### getSvgResponsiveLayout {#getSvgResponsiveLayout}

| Nom | Description |
| --- | --- |
| getSvgResponsiveLayout () | True pour exclure les attributs width et height du conteneur svg - cela rendra la mise en page réactive. False sinon. Lecture/écriture boolean. |

**Renvoie:**
boolean


---


### setDeletePicturesCroppedAreas {#setDeletePicturesCroppedAreas}

| Nom | Description |
| --- | --- |
| setDeletePicturesCroppedAreas (boolean) | Un drapeau boolean indique si les parties découpées restent dans le document. Si true, les parties découpées seront supprimées, si false elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux). |

**Renvoie:**
void


---


### setDisableFontLigatures {#setDisableFontLigatures}

| Nom | Description |
| --- | --- |
| setDisableFontLigatures (boolean) | Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser les ligatures. Lorsque la valeur est true, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur false. |

**Renvoie:**
void


---


### setHtmlFormatter {#setHtmlFormatter}

| Nom | Description |
| --- | --- |
| setHtmlFormatter ([HtmlFormatter](../htmlformatter)) | Renvoie ou définit le modèle HTML. Lecture/écriture IHtmlFormatter. |

**Renvoie:**
void


---


### setJpegQuality {#setJpegQuality}

| Nom | Description |
| --- | --- |
| setJpegQuality (byte) | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF. Lecture/écriture byte. N'a d'effet que lorsqu'un document contient des images JPEG. Utilisez cette propriété pour obtenir ou définir la qualité des images d'un document lors de l'enregistrement au format PDF. La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais la compression maximale et 100 signifie la meilleure qualité mais la compression minimale. La valeur par défaut est 95. |

**Renvoie:**
void


---


### setPicturesCompression {#setPicturesCompression}

| Nom | Description |
| --- | --- |
| setPicturesCompression (int) | Représente le niveau de compression des images |

**Renvoie:**
void


---


### setShowHiddenSlides {#setShowHiddenSlides}

| Nom | Description |
| --- | --- |
| setShowHiddenSlides (boolean) | Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false. |

**Renvoie:**
void


---


### setSlideImageFormat {#setSlideImageFormat}

| Nom | Description |
| --- | --- |
| setSlideImageFormat ([SlideImageFormat](../slideimageformat)) | Renvoie ou définit les options de format d'image des diapositives. Lecture/écriture ISlideImageFormat. |

**Renvoie:**
void


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| Nom | Description |
| --- | --- |
| setSlidesLayoutOptions ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation ISlidesLayoutOptions. |

**Renvoie:**
void


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| Nom | Description |
| --- | --- |
| setSlidesLayoutOptions ([HandoutLayoutingOptions](../handoutlayoutingoptions)) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation ISlidesLayoutOptions. |

**Renvoie:**
void


---


### setSvgResponsiveLayout {#setSvgResponsiveLayout}

| Nom | Description |
| --- | --- |
| setSvgResponsiveLayout (boolean) | True pour exclure les attributs width et height du conteneur svg - cela rendra la mise en page réactive. False sinon. Lecture/écriture boolean. |

**Renvoie:**
void


---