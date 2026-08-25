---
title: PictureFillFormat
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/picturefillformat/
---
## PictureFillFormat classe

 Représente un style de remplissage d'image.
 
### compressImage {#compressImage}

| Nom | Description |
| --- | --- |
| compressImage (boolean, int) | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Optionnellement, il supprime également les zones recadrées. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | Si vrai, la méthode supprimera les zones recadrées de l'image, réduisant potentiellement davantage sa taille. |
| resolution | int | La résolution cible pour la compression, spécifiée comme une valeur de l'énumération PicturesCompression. Cette méthode modifie la taille et la résolution de l'image de manière similaire à la fonctionnalité « Format d'image -> Compresser les images » de PowerPoint. |

 **Renvoie :**
boolean

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentException | Lancée lorsque la résolution n'est pas une valeur valide. |


---

### compressImage {#compressImage}

| Nom | Description |
| --- | --- |
| compressImage (boolean, float) | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Optionnellement, il supprime également les zones recadrées. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | Si vrai, la méthode supprimera les zones recadrées de l'image, réduisant potentiellement davantage sa taille. |
| resolution | float | La résolution cible en DPI. Cette valeur doit être positive et définit comment l'image sera redimensionnée. Cette méthode modifie la taille et la résolution de l'image de manière similaire à la fonctionnalité « Format d'image -> Compresser les images » de PowerPoint. |

 **Renvoie :**
boolean

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentException | Lancée lorsque la résolution n'est pas une valeur positive. |


---

### deletePictureCroppedAreas {#deletePictureCroppedAreas}

| Nom | Description |
| --- | --- |
| deletePictureCroppedAreas () | Supprime les zones recadrées de l'image de remplissage. |

 **Renvoie :**
[PPImage](../ppimage)


---

### getCropBottom {#getCropBottom}

| Nom | Description |
| --- | --- |
| getCropBottom () | Renvoie ou définit le nombre de pourcentages de la hauteur réelle de l'image qui sont recadrés en bas de l'image. Lecture/écriture float. |

 **Renvoie :**
float


---

### getCropLeft {#getCropLeft}

| Nom | Description |
| --- | --- |
| getCropLeft () | Renvoie ou définit le nombre de pourcentages de la largeur réelle de l'image qui sont recadrés à gauche de l'image. Lecture/écriture float. |

 **Renvoie :**
float


---

### getCropRight {#getCropRight}

| Nom | Description |
| --- | --- |
| getCropRight () | Renvoie ou définit le nombre de pourcentages de la largeur réelle de l'image qui sont recadrés à droite de l'image. Lecture/écriture float. |

 **Renvoie :**
float


---

### getCropTop {#getCropTop}

| Nom | Description |
| --- | --- |
| getCropTop () | Renvoie ou définit le nombre de pourcentages de la hauteur réelle de l'image qui sont recadrés en haut de l'image. Lecture/écriture float. |

 **Renvoie :**
float


---

### getDpi {#getDpi}

| Nom | Description |
| --- | --- |
| getDpi () | Renvoie ou définit le DPI utilisé pour remplir une image. Lecture/écriture int. |

 **Renvoie :**
int


---

### getPicture {#getPicture}

| Nom | Description |
| --- | --- |
| getPicture () | Renvoie l'image. Lecture seule ISlidesPicture. |

 **Renvoie :**
[Picture](../picture)


---

### getPictureFillMode {#getPictureFillMode}

| Nom | Description |
| --- | --- |
| getPictureFillMode () | Renvoie ou définit le mode de remplissage de l'image. Lecture/écriture PictureFillMode. |

 **Renvoie :**
int


---

### getStretchOffsetBottom {#getStretchOffsetBottom}

| Nom | Description |
| --- | --- |
| getStretchOffsetBottom () | Renvoie ou définit le bord inférieur du rectangle de remplissage défini par un décalage en pourcentage par rapport au bord inférieur de la boîte englobante de la forme. Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique une extension. Lecture/écriture float. |

 **Renvoie :**
float


---

### getStretchOffsetLeft {#getStretchOffsetLeft}

| Nom | Description |
| --- | --- |
| getStretchOffsetLeft () | Renvoie ou définit le bord gauche du rectangle de remplissage défini par un décalage en pourcentage par rapport au bord gauche de la boîte englobante de la forme. Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique une extension. Lecture/écriture float. |

 **Renvoie :**
float


---

### getStretchOffsetRight {#getStretchOffsetRight}

| Nom | Description |
| --- | --- |
| getStretchOffsetRight () | Renvoie ou définit le bord droit du rectangle de remplissage défini par un décalage en pourcentage par rapport au bord droit de la boîte englobante de la forme. Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique une extension. Lecture/écriture float. |

 **Renvoie :**
float


---

### getStretchOffsetTop {#getStretchOffsetTop}

| Nom | Description |
| --- | --- |
| getStretchOffsetTop () | Renvoie ou définit le bord supérieur du rectangle de remplissage défini par un décalage en pourcentage par rapport au bord supérieur de la boîte englobante de la forme. Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique une extension. Lecture/écriture float. |

 **Renvoie :**
float


---

### getTileAlignment {#getTileAlignment}

| Nom | Description |
| --- | --- |
| getTileAlignment () | Renvoie ou définit comment la texture est alignée à l'intérieur de la forme. Ce paramètre contrôle le point de départ du motif de texture et la façon dont il se répète sur la forme. Lecture/écriture RectangleAlignment. Valeur par défaut est RectangleAlignment#TopLeft. |

 **Renvoie :**
byte


---

### getTileFlip {#getTileFlip}

| Nom | Description |
| --- | --- |
| getTileFlip () | Retourne la tuile de texture autour de son axe horizontal, vertical ou les deux. Lecture/écriture TileFlip. Valeur par défaut est TileFlip#NoFlip. |

 **Renvoie :**
int


---

### getTileOffsetX {#getTileOffsetX}

| Nom | Description |
| --- | --- |
| getTileOffsetX () | Renvoie ou définit le décalage horizontal de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers la droite, tandis qu'une valeur négative la déplace vers la gauche. Lecture/écriture float. |

 **Renvoie :**
float


---

### getTileOffsetY {#getTileOffsetY}

| Nom | Description |
| --- | --- |
| getTileOffsetY () | Renvoie ou définit le décalage vertical de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers le bas, tandis qu'une valeur négative la déplace vers le haut. Lecture/écriture float. |

 **Renvoie :**
float


---

### getTileScaleX {#getTileScaleX}

| Nom | Description |
| --- | --- |
| getTileScaleX () | Renvoie ou définit l'échelle horizontale pour le remplissage de texture en pourcentage. Lecture/écriture float. |

 **Renvoie :**
float


---

### getTileScaleY {#getTileScaleY}

| Nom | Description |
| --- | --- |
| getTileScaleY () | Renvoie ou définit l'échelle verticale pour le remplissage de texture en pourcentage. Lecture/écriture float. |

 **Renvoie :**
float


---

### getVersion {#getVersion}

| Nom | Description |
| --- | --- |
| getVersion () |  |

 **Renvoie :**
long


---

### setCropBottom {#setCropBottom}

| Nom | Description |
| --- | --- |
| setCropBottom (float) | Renvoie ou définit le nombre de pourcentages de la hauteur réelle de l'image qui sont recadrés en bas de l'image. Lecture/écriture float. |

 **Renvoie :**
void


---

### setCropLeft {#setCropLeft}

| Nom | Description |
| --- | --- |
| setCropLeft (float) | Renvoie ou définit le nombre de pourcentages de la largeur réelle de l'image qui sont recadrés à gauche de l'image. Lecture/écriture float. |

 **Renvoie :**
void


---

### setCropRight {#setCropRight}

| Nom | Description |
| --- | --- |
| setCropRight (float) | Renvoie ou définit le nombre de pourcentages de la largeur réelle de l'image qui sont recadrés à droite de l'image. Lecture/écriture float. |

 **Renvoie :**
void


---

### setCropTop {#setCropTop}

| Nom | Description |
| --- | --- |
| setCropTop (float) | Renvoie ou définit le nombre de pourcentages de la hauteur réelle de l'image qui sont recadrés en haut de l'image. Lecture/écriture float. |

 **Renvoie :**
void


---

### setDpi {#setDpi}

| Nom | Description |
| --- | --- |
| setDpi (int) | Renvoie ou définit le DPI utilisé pour remplir une image. Lecture/écriture int. |

 **Renvoie :**
void


---

### setPictureFillMode {#setPictureFillMode}

| Nom | Description |
| --- | --- |
| setPictureFillMode (int) | Renvoie ou définit le mode de remplissage de l'image. Lecture/écriture PictureFillMode. |

 **Renvoie :**
void


---

### setStretchOffsetBottom {#setStretchOffsetBottom}

| Nom | Description |
| --- | --- |
| setStretchOffsetBottom (float) | Renvoie ou définit le bord inférieur du rectangle de remplissage défini par un décalage en pourcentage par rapport au bord inférieur de la boîte englobante de la forme. Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique une extension. Lecture/écriture float. |

 **Renvoie :**
void


---

### setStretchOffsetLeft {#setStretchOffsetLeft}

| Nom | Description |
| --- | --- |
| setStretchOffsetLeft (float) | Renvoie ou définit le bord gauche du rectangle de remplissage défini par un décalage en pourcentage par rapport au bord gauche de la boîte englobante de la forme. Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique une extension. Lecture/écriture float. |

 **Renvoie :**
void


---

### setStretchOffsetRight {#setStretchOffsetRight}

| Nom | Description |
| --- | --- |
| setStretchOffsetRight (float) | Renvoie ou définit le bord droit du rectangle de remplissage défini par un décalage en pourcentage par rapport au bord droit de la boîte englobante de la forme. Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique une extension. Lecture/écriture float. |

 **Renvoie :**
void


---

### setStretchOffsetTop {#setStretchOffsetTop}

| Nom | Description |
| --- | --- |
| setStretchOffsetTop (float) | Renvoie ou définit le bord supérieur du rectangle de remplissage défini par un décalage en pourcentage par rapport au bord supérieur de la boîte englobante de la forme. Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique une extension. Lecture/écriture float. |

 **Renvoie :**
void


---

### setTileAlignment {#setTileAlignment}

| Nom | Description |
| --- | --- |
| setTileAlignment (byte) | Renvoie ou définit comment la texture est alignée à l'intérieur de la forme. Ce paramètre contrôle le point de départ du motif de texture et la façon dont il se répète sur la forme. Lecture/écriture RectangleAlignment. Valeur par défaut est RectangleAlignment#TopLeft. |

 **Renvoie :**
void


---

### setTileFlip {#setTileFlip}

| Nom | Description |
| --- | --- |
| setTileFlip (int) | Retourne la tuile de texture autour de son axe horizontal, vertical ou les deux. Lecture/écriture TileFlip. Valeur par défaut est TileFlip#NoFlip. |

 **Renvoie :**
void


---

### setTileOffsetX {#setTileOffsetX}

| Nom | Description |
| --- | --- |
| setTileOffsetX (float) | Renvoie ou définit le décalage horizontal de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers la droite, tandis qu'une valeur négative la déplace vers la gauche. Lecture/écriture float. |

 **Renvoie :**
void


---

### setTileOffsetY {#setTileOffsetY}

| Nom | Description |
| --- | --- |
| setTileOffsetY (float) | Renvoie ou définit le décalage vertical de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers le bas, tandis qu'une valeur négative la déplace vers le haut. Lecture/écriture float. |

 **Renvoie :**
void


---

### setTileScaleX {#setTileScaleX}

| Nom | Description |
| --- | --- |
| setTileScaleX (float) | Renvoie ou définit l'échelle horizontale pour le remplissage de texture en pourcentage. Lecture/écriture float. |

 **Renvoie :**
void


---

### setTileScaleY {#setTileScaleY}

| Nom | Description |
| --- | --- |
| setTileScaleY (float) | Renvoie ou définit l'échelle verticale pour le remplissage de texture en pourcentage. Lecture/écriture float. |

 **Renvoie :**
void


---