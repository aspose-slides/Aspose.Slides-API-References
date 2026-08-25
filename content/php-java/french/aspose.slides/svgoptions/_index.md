---
title: SVGOptions
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/svgoptions/
---
## SVGOptions classe

 Représente des options SVG.

### SVGOptions {#SVGOptions}

| Name | Description |
| --- | --- |
| SVGOptions() | Initialise une nouvelle instance de la classe SVGOptions. |

**Renvoie:**
SVGOptions


---

### SVGOptions {#SVGOptions}

| Name | Description |
| --- | --- |
| SVGOptions([VideoPlayerHtmlController](../videoplayerhtmlcontroller)) | Initialise une nouvelle instance de la classe SVGOptions en spécifiant l'objet du contrôleur d'intégration de lien. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| linkEmbedController | [VideoPlayerHtmlController](../videoplayerhtmlcontroller) | La référence du contrôleur d'intégration de lien. Le contrôleur d'intégration de lien est un objet délégué responsable de prendre des décisions si les ressources (telles que les images) doivent être intégrées ou référencées comme des ressources externes. |

**Renvoie:**
SVGOptions


---

### getDefault {#getDefault}

| Name | Description |
| --- | --- |
| getDefault () | Renvoie les paramètres par défaut. SVGOptions en lecture seule. |

**Renvoie:**
SVGOptions


---

### getDeletePicturesCroppedAreas {#getDeletePicturesCroppedAreas}

| Name | Description |
| --- | --- |
| getDeletePicturesCroppedAreas () | Un drapeau booléen indique si les parties rognées restent dans le document. Si true, les parties rognées seront supprimées, si false elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux) |

**Renvoie:**
boolean


---

### getDisable3DText {#getDisable3DText}

| Name | Description |
| --- | --- |
| getDisable3DText () | Détermine si le texte 3D est désactivé dans le SVG. Booléen lecture/écriture. |

**Renvoie:**
boolean


---

### getDisableFontLigatures {#getDisableFontLigatures}

| Name | Description |
| --- | --- |
| getDisableFontLigatures () | Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsqu'elle est définie sur true, les ligatures seront désactivées dans le rendu. Par défaut, cette propriété est définie sur false. |

**Renvoie:**
boolean


---

### getDisableGradientSplit {#getDisableGradientSplit}

| Name | Description |
| --- | --- |
| getDisableGradientSplit () | Désactive la division des dégradés FromCornerX et FromCenter. Booléen lecture/écriture. |

**Renvoie:**
boolean


---

### getDisableLineEndCropping {#getDisableLineEndCropping}

| Name | Description |
| --- | --- |
| getDisableLineEndCropping () | SVG 1.1 ne permet pas de définir des retraits pour les marqueurs. Le moteur d’écriture SVG d’Aspose.Slides propose une solution de contournement : il rogne l’extrémité de la ligne avec la flèche, de sorte que la ligne ne chevauche pas les marqueurs. Cette option désactive ce comportement. Booléen lecture/écriture. |

**Renvoie:**
boolean


---

### getExternalFontsHandling {#getExternalFontsHandling}

| Name | Description |
| --- | --- |
| getExternalFontsHandling () | Détermine la méthode de gestion des polices chargées externement. SvgExternalFontsHandling en lecture/écriture. |

**Renvoie:**
int


---

### getInkOptions {#getInkOptions}

| Name | Description |
| --- | --- |
| getInkOptions () | Fournit des options qui contrôlent l’apparence des objets Ink dans le document exporté. IInkOptions en lecture seule. |

**Renvoie:**
[InkOptions](../inkoptions)


---

### getJpegQuality {#getJpegQuality}

| Name | Description |
| --- | --- |
| getJpegQuality () | Détermine la qualité d’encodage JPEG. Int lecture/écriture. |

**Renvoie:**
int


---

### getMetafileRasterizationDpi {#getMetafileRasterizationDpi}

| Name | Description |
| --- | --- |
| getMetafileRasterizationDpi () | Renvoie ou définit la limite de résolution minimale pour la rasterisation du métafichier. Int lecture/écriture. |

**Renvoie:**
int


---

### getPicturesCompression {#getPicturesCompression}

| Name | Description |
| --- | --- |
| getPicturesCompression () | Représente le niveau de compression des images. |

**Renvoie:**
int


---

### getShapeFormattingController {#getShapeFormattingController}

| Name | Description |
| --- | --- |
| getShapeFormattingController () | Renvoie et définit une interface de rappel qui permet à l’utilisateur de contrôler la conversion des formes. ISvgShapeFormattingController en lecture/écriture. |

**Renvoie:**
[VideoPlayerHtmlController](../videoplayerhtmlcontroller)


---

### getSimple {#getSimple}

| Name | Description |
| --- | --- |
| getSimple () | Renvoie les paramètres pour la génération du fichier SVG le plus simple et le plus petit. SVGOptions en lecture seule. |

**Renvoie:**
SVGOptions


---

### getUseFrameRotation {#getUseFrameRotation}

| Name | Description |
| --- | --- |
| getUseFrameRotation () | Détermine s’il faut appliquer la rotation spécifiée de la forme lors du rendu ou non. Booléen lecture/écriture. Valeur par défaut : true. |

**Renvoie:**
boolean


---

### getUseFrameSize {#getUseFrameSize}

| Name | Description |
| --- | --- |
| getUseFrameSize () | Détermine si le cadre de texte sera inclus dans la zone de rendu ou non. Booléen lecture/écriture. Valeur par défaut : false. |

**Renvoie:**
boolean


---

### getVectorizeText {#getVectorizeText}

| Name | Description |
| --- | --- |
| getVectorizeText () | Détermine si le texte d’une diapositive sera enregistré sous forme de graphiques. Booléen lecture/écriture. |

**Renvoie:**
boolean


---

### getWYSIWYG {#getWYSIWYG}

| Name | Description |
| --- | --- |
| getWYSIWYG () | Renvoie les paramètres pour la génération du fichier SVG la plus précise. SVGOptions en lecture seule. |

**Renvoie:**
SVGOptions


---

### setDeletePicturesCroppedAreas {#setDeletePicturesCroppedAreas}

| Name | Description |
| --- | --- |
| setDeletePicturesCroppedAreas (boolean) | Un drapeau booléen indique si les parties rognées restent dans le document. Si true, les parties rognées seront supprimées, si false elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux) |

**Renvoie:**
void


---

### setDisable3DText {#setDisable3DText}

| Name | Description |
| --- | --- |
| setDisable3DText (boolean) | Détermine si le texte 3D est désactivé dans le SVG. Booléen lecture/écriture. |

**Renvoie:**
void


---

### setDisableFontLigatures {#setDisableFontLigatures}

| Name | Description |
| --- | --- |
| setDisableFontLigatures (boolean) | Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsqu'elle est définie sur true, les ligatures seront désactivées dans le rendu. Par défaut, cette propriété est définie sur false. |

**Renvoie:**
void


---

### setDisableGradientSplit {#setDisableGradientSplit}

| Name | Description |
| --- | --- |
| setDisableGradientSplit (boolean) | Désactive la division des dégradés FromCornerX et FromCenter. Booléen lecture/écriture. |

**Renvoie:**
void


---

### setDisableLineEndCropping {#setDisableLineEndCropping}

| Name | Description |
| --- | --- |
| setDisableLineEndCropping (boolean) | SVG 1.1 ne permet pas de définir des retraits pour les marqueurs. Le moteur d’écriture SVG d’Aspose.Slides propose une solution de contournement : il rogne l’extrémité de la ligne avec la flèche, de sorte que la ligne ne chevauche pas les marqueurs. Cette option désactive ce comportement. Booléen lecture/écriture. |

**Renvoie:**
void


---

### setExternalFontsHandling {#setExternalFontsHandling}

| Name | Description |
| --- | --- |
| setExternalFontsHandling (int) | Détermine la méthode de gestion des polices chargées externement. SvgExternalFontsHandling en lecture/écriture. |

**Renvoie:**
void


---

### setJpegQuality {#setJpegQuality}

| Name | Description |
| --- | --- |
| setJpegQuality (int) | Détermine la qualité d’encodage JPEG. Int lecture/écriture. |

**Renvoie:**
void


---

### setMetafileRasterizationDpi {#setMetafileRasterizationDpi}

| Name | Description |
| --- | --- |
| setMetafileRasterizationDpi (int) | Renvoie ou définit la limite de résolution minimale pour la rasterisation du métafichier. Int lecture/écriture. |

**Renvoie:**
void


---

### setPicturesCompression {#setPicturesCompression}

| Name | Description |
| --- | --- |
| setPicturesCompression (int) | Représente le niveau de compression des images. |

**Renvoie:**
void


---

### setShapeFormattingController {#setShapeFormattingController}

| Name | Description |
| --- | --- |
| setShapeFormattingController ([VideoPlayerHtmlController](../videoplayerhtmlcontroller)) | Renvoie et définit une interface de rappel qui permet à l’utilisateur de contrôler la conversion des formes. ISvgShapeFormattingController en lecture/écriture. |

**Renvoie:**
void


---

### setUseFrameRotation {#setUseFrameRotation}

| Name | Description |
| --- | --- |
| setUseFrameRotation (boolean) | Détermine s’il faut appliquer la rotation spécifiée de la forme lors du rendu ou non. Booléen lecture/écriture. Valeur par défaut : true. |

**Renvoie:**
void


---

### setUseFrameSize {#setUseFrameSize}

| Name | Description |
| --- | --- |
| setUseFrameSize (boolean) | Détermine si le cadre de texte sera inclus dans la zone de rendu ou non. Booléen lecture/écriture. Valeur par défaut : false. |

**Renvoie:**
void


---

### setVectorizeText {#setVectorizeText}

| Name | Description |
| --- | --- |
| setVectorizeText (boolean) | Détermine si le texte d’une diapositive sera enregistré sous forme de graphiques. Booléen lecture/écriture. |

**Renvoie:**
void

