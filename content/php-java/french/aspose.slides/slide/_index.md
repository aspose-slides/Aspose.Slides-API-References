---
title: Slide
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/slide/
---
## Slide classe

  Représente une diapositive dans une présentation.
 
### getHeaderFooterManager {#getHeaderFooterManager}

| Nom | Description |
| --- | --- |
| getHeaderFooterManager () | Renvoie le gestionnaire HeaderFooter de la diapositive. lecture seule ISlideHeaderFooterManager. |

 **Renvoie :**
[SlideHeaderFooterManager](../slideheaderfootermanager)


---


### getHidden {#getHidden}

| Nom | Description |
| --- | --- |
| getHidden () | Détermine si la diapositive spécifiée est masquée pendant le diaporama. lecture/écriture boolean. |

 **Renvoie :**
boolean


---


### getImage {#getImage}

| Nom | Description |
| --- | --- |
| getImage (float, float) | Renvoie un objet Thumbnail Image avec un redimensionnement personnalisé. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| scaleX | float | La valeur par laquelle mettre à l'échelle cette Thumbnail dans la direction de l'axe x. |
| scaleY | float | La valeur par laquelle mettre à l'échelle cette Thumbnail dans la direction de l'axe y. |

 **Renvoie :**
IImage


---


### getImage {#getImage}

| Nom | Description |
| --- | --- |
| getImage () | Renvoie un objet Thumbnail Image (20 % de la taille réelle). |

 **Renvoie :**
IImage


---


### getImage {#getImage}

| Nom | Description |
| --- | --- |
| getImage (Dimension) | Renvoie un objet Thumbnail Image avec la taille spécifiée. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| imageSize | Dimension | Taille de l'image à créer. |

 **Renvoie :**
IImage


---


### getImage {#getImage}

| Nom | Description |
| --- | --- |
| getImage ([TiffOptions](../tiffoptions)) | Renvoie un objet d'image tiff Thumbnail avec les paramètres spécifiés. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| options | [TiffOptions](../tiffoptions) | Options tiff. |

 **Renvoie :**
IImage

 **Exception**

| Erreur | Condition |
| --- | --- |
 | InvalidOperationException | Levée lorsque options.SlideLayoutOption est NotesCommentsLayoutingOptions et que sa propriété NotesPosition prend la valeur NotesPositions.BottomFull. |


---


### getImage {#getImage}

| Nom | Description |
| --- | --- |
| getImage ([RenderingOptions](../renderingoptions)) | Renvoie un objet Thumbnail Image. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Options de rendu. |

 **Renvoie :**
IImage

 **Exception**

| Erreur | Condition |
| --- | --- |
 | InvalidOperationException | Levée lorsque notesCommentsLayouting.NotesPosition prend la valeur NotesPositions.BottomFull |



---


### getImage {#getImage}

| Nom | Description |
| --- | --- |
| getImage ([RenderingOptions](../renderingoptions), float, float) | Renvoie un objet Thumbnail Image avec un redimensionnement personnalisé. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Options de rendu. |
| scaleX | float | La valeur par laquelle mettre à l'échelle cette Thumbnail dans la direction de l'axe x. |
| scaleY | float | La valeur par laquelle mettre à l'échelle cette Thumbnail dans la direction de l'axe y. |

 **Renvoie :**
IImage

 **Exception**

| Erreur | Condition |
| --- | --- |
 | InvalidOperationException | Levée lorsque notesCommentsLayouting.NotesPosition prend la valeur NotesPositions.BottomFull |



---


### getImage {#getImage}

| Nom | Description |
| --- | --- |
| getImage ([RenderingOptions](../renderingoptions), Dimension) | Renvoie un objet Thumbnail Image avec la taille spécifiée. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Options de rendu. |
| imageSize | Dimension | Taille de l'image à créer. |

 **Renvoie :**
IImage

 **Exception**

| Erreur | Condition |
| --- | --- |
 | InvalidOperationException | Levée lorsque options.SlideLayoutOption est NotesCommentsLayoutingOptions et que sa propriété NotesPosition prend la valeur NotesPositions.BottomFull. |


---


### getLayoutSlide {#getLayoutSlide}

| Nom | Description |
| --- | --- |
| getLayoutSlide () | Renvoie ou définit la diapositive de mise en page pour la diapositive actuelle. lecture/écriture ILayoutSlide. |

 **Renvoie :**
[LayoutSlide](../layoutslide)


---


### getNotesSlideManager {#getNotesSlideManager}

| Nom | Description |
| --- | --- |
| getNotesSlideManager () | Permet d'accéder à la diapositive de notes, de l'ajouter et de la supprimer. lecture seule INotesSlideManager. |

 **Renvoie :**
[NotesSlideManager](../notesslidemanager)


---


### getShowMasterShapes {#getShowMasterShapes}

| Nom | Description |
| --- | --- |
| getShowMasterShapes () | Spécifie si les formes sur la diapositive maîtresse doivent être affichées sur les diapositives ou non. lecture/écriture boolean. |

 **Renvoie :**
boolean


---


### getSlideComments {#getSlideComments}

| Nom | Description |
| --- | --- |
| getSlideComments ([CommentAuthor](../commentauthor)) | Renvoie tous les commentaires de diapositive ajoutés par un auteur spécifique. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| author | [CommentAuthor](../commentauthor) | Auteur des commentaires à rechercher ou null pour renvoyer tous les commentaires. |

 **Renvoie :**
[Comment](../comment), [ModernComment](../moderncomment)


---


### getSlideNumber {#getSlideNumber}

| Nom | Description |
| --- | --- |
| getSlideNumber () | Renvoie le numéro d'une diapositive. L'index de la diapositive dans la collection Presentation#getSlides est toujours égal à SlideNumber - Presentation.FirstSlideNumber. lecture/écriture int. |

 **Renvoie :**
int


---


### getThemeManager {#getThemeManager}

| Nom | Description |
| --- | --- |
| getThemeManager () | Renvoie le gestionnaire de thème de substitution. lecture seule IOverrideThemeManager. |

 **Renvoie :**
[SlideThemeManager](../slidethememanager), [LayoutSlideThemeManager](../layoutslidethememanager), [ChartThemeManager](../chartthememanager), [BaseOverrideThemeManager](../baseoverridethememanager), [NotesSlideThemeManager](../notesslidethememanager)


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Nom | Description |
| --- | --- |
| joinPortionsWithSameFormatting () | Regroupe les segments avec le même formatage dans tous les paragraphes de toutes les formes acceptables. |

 **Renvoie :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove () | Supprime la diapositive de la présentation. |

 **Renvoie :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | PptxEditException | Levée si la diapositive est déjà supprimée de la présentation. |


---


### reset {#reset}

| Nom | Description |
| --- | --- |
| reset () | Réinitialise la position, la taille et le formatage de chaque forme qui possède un prototype sur LayoutSlide. |

 **Renvoie :**
void


---


### setHidden {#setHidden}

| Nom | Description |
| --- | --- |
| setHidden (boolean) | Détermine si la diapositive spécifiée est masquée pendant le diaporama. lecture/écriture boolean. |

 **Renvoie :**
void


---


### setLayoutSlide {#setLayoutSlide}

| Nom | Description |
| --- | --- |
| setLayoutSlide ([LayoutSlide](../layoutslide)) | Renvoie ou définit la diapositive de mise en page pour la diapositive actuelle. lecture/écriture ILayoutSlide. |

 **Renvoie :**
void


---


### setShowMasterShapes {#setShowMasterShapes}

| Nom | Description |
| --- | --- |
| setShowMasterShapes (boolean) | Spécifie si les formes sur la diapositive maîtresse doivent être affichées sur les diapositives ou non. lecture/écriture boolean. |

 **Renvoie :**
void


---


### setSlideNumber {#setSlideNumber}

| Nom | Description |
| --- | --- |
| setSlideNumber (int) | Renvoie le numéro d'une diapositive. L'index de la diapositive dans la collection Presentation#getSlides est toujours égal à SlideNumber - Presentation.FirstSlideNumber. lecture/écriture int. |

 **Renvoie :**
void


---


### writeAsEmf {#writeAsEmf}

| Nom | Description |
| --- | --- |
| writeAsEmf (OutputStream) | Enregistre le contenu de la diapositive sous forme de fichier EMF. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux cible |

 **Renvoie :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentNullException | Le flux cible est {@code null} |


---


### writeAsSvg {#writeAsSvg}

| Nom | Description |
| --- | --- |
| writeAsSvg (OutputStream) | Enregistre le contenu de la diapositive sous forme de fichier SVG. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux cible |

 **Renvoie :**
void


---


### writeAsSvg {#writeAsSvg}

| Nom | Description |
| --- | --- |
| writeAsSvg (OutputStream, [SVGOptions](../svgoptions)) | Enregistre le contenu de la diapositive sous forme de fichier SVG. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux cible |
| svgOptions | [SVGOptions](../svgoptions) | Options de génération SVG |

 **Renvoie :**
void


---