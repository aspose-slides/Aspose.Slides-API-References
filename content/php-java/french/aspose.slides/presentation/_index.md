---
title: Presentation
second_title: Référence de l'API Java Aspose.Sildes pour PHP
description: 
type: docs

url: /fr/aspose.slides/presentation/
---
## Presentation classe

  Représente une présentation Microsoft PowerPoint.
 
### Presentation {#Presentation}

| Nom | Description |
| --- | --- |
| Presentation() | Cette fonction crée une nouvelle présentation à partir de zéro. La présentation créée possède une diapositive vide. |

**Retourne :**
Presentation


---


### Presentation {#Presentation}

| Nom | Description |
| --- | --- |
| Presentation([LoadOptions](../loadoptions)) | Cette fonction crée une nouvelle présentation à partir de zéro. La présentation créée possède une diapositive vide. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| loadOptions | [LoadOptions](../loadoptions) | Options de chargement supplémentaires. |

**Retourne :**
Presentation


---


### Presentation {#Presentation}

| Nom | Description |
| --- | --- |
| Presentation(InputStream) | Cette fonction est le mécanisme principal de lecture d’une présentation existante. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | InputStream | Flux d’entrée. |

**Retourne :**
Presentation


---


### Presentation {#Presentation}

| Nom | Description |
| --- | --- |
| Presentation(InputStream, [LoadOptions](../loadoptions)) | Cette fonction est le mécanisme principal de lecture d’une présentation existante. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | InputStream | Flux d’entrée. |
| loadOptions | [LoadOptions](../loadoptions) | Options de chargement supplémentaires. |

**Retourne :**
Presentation


---


### Presentation {#Presentation}

| Nom | Description |
| --- | --- |
| Presentation(String) | Cette fonction obtient le chemin d’un fichier source à partir duquel le contenu de la présentation est lu. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| file | String | Fichier d’entrée. |

**Retourne :**
Presentation

**Erreur**

| Erreur | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | Levée lorsque le fichier d’entrée a une longueur nulle |


---


### Presentation {#Presentation}

| Nom | Description |
| --- | --- |
| Presentation(String, [LoadOptions](../loadoptions)) | Cette fonction obtient le chemin d’un fichier source à partir duquel le contenu de la présentation est lu. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| file | String | Fichier d’entrée. |
| loadOptions | [LoadOptions](../loadoptions) | Options de chargement supplémentaires. |

**Retourne :**
Presentation

**Erreur**

| Erreur | Condition |
| --- | --- |
 | ArgumentException | Levée lorsque le fichier d’entrée a une longueur nulle |


---


### dispose {#dispose}

| Nom | Description |
| --- | --- |
| dispose () | Libère toutes les ressources utilisées par cet objet Presentation. |

**Retourne :**
void


---


### getAllCustomXmlParts {#getAllCustomXmlParts}

| Nom | Description |
| --- | --- |
| getAllCustomXmlParts () | Renvoie toutes les parties de données personnalisées de la présentation. Lecture seule ICustomXmlPart[]. |

**Retourne :**
[CustomXmlPart](../customxmlpart)


---


### getAudios {#getAudios}

| Nom | Description |
| --- | --- |
| getAudios () | Renvoie la collection de tous les fichiers audio intégrés dans la présentation. Lecture seule IAudioCollection. |

**Retourne :**
[AudioCollection](../audiocollection)


---


### getCommentAuthors {#getCommentAuthors}

| Nom | Description |
| --- | --- |
| getCommentAuthors () | Renvoie la collection des auteurs de commentaires. Lecture seule ICommentAuthorCollection. |

**Retourne :**
[CommentAuthorCollection](../commentauthorcollection)


---


### getCurrentDateTime {#getCurrentDateTime}

| Nom | Description |
| --- | --- |
| getCurrentDateTime () | Renvoie ou définit la date et l’heure qui remplaceront le contenu des champs datetime. Heure de création de cet objet Presentation par défaut. Lecture/écriture java.util.Date. |

**Retourne :**
Date


---


### getCustomData {#getCustomData}

| Nom | Description |
| --- | --- |
| getCustomData () | Renvoie les données personnalisées de la présentation. Lecture seule ICustomData. |

**Retourne :**
[CustomData](../customdata)


---


### getDefaultTextStyle {#getDefaultTextStyle}

| Nom | Description |
| --- | --- |
| getDefaultTextStyle () | Renvoie le style de texte par défaut pour les formes. Lecture seule ITextStyle. |

**Retourne :**
[TextStyle](../textstyle)


---


### getDigitalSignatures {#getDigitalSignatures}

| Nom | Description |
| --- | --- |
| getDigitalSignatures () | Renvoie la collection des signatures utilisées pour signer la présentation. Lecture seule IDigitalSignatureCollection. |

**Retourne :**
[DigitalSignatureCollection](../digitalsignaturecollection)


---


### getDocumentProperties {#getDocumentProperties}

| Nom | Description |
| --- | --- |
| getDocumentProperties () | Renvoie l’objet DocumentProperties qui contient les propriétés de document standard et personnalisées. Lecture seule IDocumentProperties. |

**Retourne :**
[DocumentProperties](../documentproperties)


---


### getFirstSlideNumber {#getFirstSlideNumber}

| Nom | Description |
| --- | --- |
| getFirstSlideNumber () | Représente le numéro de la première diapositive dans la présentation. |

**Retourne :**
int


---


### getFontsManager {#getFontsManager}

| Nom | Description |
| --- | --- |
| getFontsManager () | Renvoie le gestionnaire de polices. Lecture seule IFontsManager. |

**Retourne :**
[FontsManager](../fontsmanager)


---


### getHeaderFooterManager {#getHeaderFooterManager}

| Nom | Description |
| --- | --- |
| getHeaderFooterManager () | Renvoie le gestionnaire actuel HeaderFooter. Lecture seule IPresentationHeaderFooterManager. |

**Retourne :**
[PresentationHeaderFooterManager](../presentationheaderfootermanager)


---


### getHyperlinkQueries {#getHyperlinkQueries}

| Nom | Description |
| --- | --- |
| getHyperlinkQueries () | Fournit un accès facile à tous les hyperliens contenus dans les diapositives de la présentation (pas dans les maîtres, mises en page, diapositives de notes). Lecture seule IHyperlinkQueries. |

**Retourne :**
[HyperlinkQueries](../hyperlinkqueries)


---


### getImages {#getImages}

| Nom | Description |
| --- | --- |
| getImages () | Renvoie la collection de toutes les images de la présentation. Lecture seule IImageCollection. |

**Retourne :**
[ImageCollection](../imagecollection)


---


### getImages {#getImages}

| Nom | Description |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions)) | Renvoie des objets Image pour toutes les diapositives d’une présentation. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Options Tiff. |

**Retourne :**
IImage


---


### getImages {#getImages}

| Nom | Description |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions), int[]) | Renvoie des objets Image miniature pour les diapositives spécifiées d’une présentation. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Options Tiff. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |

**Retourne :**
IImage


---


### getImages {#getImages}

| Nom | Description |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions), float, float) | Renvoie des objets Image miniature pour toutes les diapositives d’une présentation avec un redimensionnement personnalisé. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Options Tiff. |
| scaleX | float | Valeur par laquelle mettre à l’échelle cette miniature sur l’axe x. |
| scaleY | float | Valeur par laquelle mettre à l’échelle cette miniature sur l’axe y. |

**Retourne :**
IImage


---


### getImages {#getImages}

| Nom | Description |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions), int[], float, float) | Renvoie des objets Image miniature pour les diapositives spécifiées d’une présentation avec un redimensionnement personnalisé. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Options Tiff. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| scaleX | float | Valeur par laquelle mettre à l’échelle cette miniature sur l’axe x. |
| scaleY | float | Valeur par laquelle mettre à l’échelle cette miniature sur l’axe y. |

**Retourne :**
IImage


---


### getImages {#getImages}

| Nom | Description |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions), Dimension) | Renvoie des objets Image miniature pour toutes les diapositives d’une présentation avec une taille spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Options Tiff. |
| imageSize | Dimension | Taille de l’image à créer. |

**Retourne :**
IImage


---


### getImages {#getImages}

| Nom | Description |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions), int[], Dimension) | Renvoie des objets Image miniature pour les diapositives spécifiées d’une présentation avec une taille spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Options Tiff. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| imageSize | Dimension | Taille de l’image à créer. |

**Retourne :**
IImage


---


### getLayoutSlides {#getLayoutSlides}

| Nom | Description |
| --- | --- |
| getLayoutSlides () | Renvoie une liste de toutes les diapositives de mise en page définies dans la présentation. Lecture seule IGlobalLayoutSlideCollection. Vous pouvez accéder à une API alternative pour ajouter/insérer/supprimer/dupliquer des diapositives de mise en page en utilisant la propriété IMasterSlide.LayoutSlides. |

**Retourne :**
[GlobalLayoutSlideCollection](../globallayoutslidecollection)


---


### getMasterHandoutSlideManager {#getMasterHandoutSlideManager}

| Nom | Description |
| --- | --- |
| getMasterHandoutSlideManager () | Renvoie le gestionnaire du maître de notes. Lecture seule IMasterHandoutSlideManager. |

**Retourne :**
MasterHandoutSlideManager


---


### getMasterNotesSlideManager {#getMasterNotesSlideManager}

| Nom | Description |
| --- | --- |
| getMasterNotesSlideManager () | Renvoie le gestionnaire du maître de notes. Lecture seule IMasterNotesSlideManager. |

**Retourne :**
MasterNotesSlideManager


---


### getMasterTheme {#getMasterTheme}

| Nom | Description |
| --- | --- |
| getMasterTheme () | Renvoie le thème maître. Lecture seule IMasterTheme. |

**Retourne :**
[MasterTheme](../mastertheme)


---


### getMasters {#getMasters}

| Nom | Description |
| --- | --- |
| getMasters () | Renvoie une liste de toutes les diapositives maîtres définies dans la présentation. Lecture seule IMasterSlideCollection. |

**Retourne :**
[MasterSlideCollection](../masterslidecollection)


---


### getNotesSize {#getNotesSize}

| Nom | Description |
| --- | --- |
| getNotesSize () | Renvoie l’objet de taille de diapositive de notes. Lecture seule INotesSize. |

**Retourne :**
[NotesSize](../notessize)


---


### getPresentation {#getPresentation}

| Nom | Description |
| --- | --- |
| getPresentation () | Renvoie la présentation parente d’un texte. Lecture seule IPresentation. |

**Retourne :**
[Presentation](../presentation)


---


### getProtectionManager {#getProtectionManager}

| Nom | Description |
| --- | --- |
| getProtectionManager () | Obtient le gestionnaire des autorisations pour cette présentation. Lecture seule IProtectionManager. |

**Retourne :**
[ProtectionManager](../protectionmanager)


---


### getSections {#getSections}

| Nom | Description |
| --- | --- |
| getSections () | Renvoie une liste de toutes les sections de diapositives définies dans la présentation. Lecture seule ISectionCollection. |

**Retourne :**
[SectionCollection](../sectioncollection)


---


### getSensitivityLabels {#getSensitivityLabels}

| Nom | Description |
| --- | --- |
| getSensitivityLabels () | Renvoie la collection des libellés de sensibilité appliqués au document de présentation. Lecture seule ISensitivityLabelCollection. |

**Retourne :**
[SensitivityLabelCollection](../sensitivitylabelcollection)


---


### getSlideById {#getSlideById}

| Nom | Description |
| --- | --- |
| getSlideById (long) | Renvoie une Slide, MasterSlide ou LayoutSlide selon l’Id. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| id | long | Id d’une diapositive. |

**Retourne :**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getSlideShowSettings {#getSlideShowSettings}

| Nom | Description |
| --- | --- |
| getSlideShowSettings () | Renvoie les paramètres du diaporama pour la présentation. |

**Retourne :**
SlideShowSettings


---


### getSlideSize {#getSlideSize}

| Nom | Description |
| --- | --- |
| getSlideSize () | Renvoie l’objet de taille de diapositive. Lecture seule ISlideSize. |

**Retourne :**
[SlideSize](../slidesize)


---


### getSlides {#getSlides}

| Nom | Description |
| --- | --- |
| getSlides () | Renvoie une liste de toutes les diapositives définies dans la présentation. Lecture seule ISlideCollection. |

**Retourne :**
[SlideCollection](../slidecollection)


---


### getSourceFormat {#getSourceFormat}

| Nom | Description |
| --- | --- |
| getSourceFormat () | Renvoie des informations sur le format à partir duquel la présentation a été chargée. Lecture seule SourceFormat. |

**Retourne :**
int


---


### getVbaProject {#getVbaProject}

| Nom | Description |
| --- | --- |
| getVbaProject () | Obtient ou définit le projet VBA contenant les macros de la présentation. Lecture/écriture IVbaProject. |

**Retourne :**
[VbaProject](../vbaproject)


---


### getVideos {#getVideos}

| Nom | Description |
| --- | --- |
| getVideos () | Renvoie la collection de toutes les vidéos intégrées dans la présentation. Lecture seule IVideoCollection. |

**Retourne :**
{{L...}}
| getVideos () | Renvoie la collection de tous les fichiers vidéo intégrés dans la présentation. Lecture seule IVideoCollection. |
**Valeur de retour :**
[VideoCollection](../videocollection)

---

### getViewProperties {#getViewProperties}

| Nom | Description |
| --- | --- |
| getViewProperties () | Obtient les propriétés d’affichage de la présentation. Lecture seule IViewProperties. |
**Valeur de retour :**
[ViewProperties](../viewproperties)

---

### highlightRegex {#highlightRegex}

| Nom | Description |
| --- | --- |
| highlightRegex (Pattern, Color, [IFindResultCallback](../ifindresultcallback)) | Met en surbrillance toutes les correspondances de l’expression régulière avec la couleur spécifiée. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| regex | Pattern | L’expression régulière java.util.regex.Pattern pour obtenir les chaînes à mettre en surbrillance. |
| highlightColor | Color | La couleur pour mettre le texte en surbrillance. |
| callback | [IFindResultCallback](../ifindresultcallback) | L’objet de rappel pour recevoir les résultats de recherche IFindResultCallback. |
**Valeur de retour :**
void

---

### highlightText {#highlightText}

| Nom | Description |
| --- | --- |
| highlightText (String, Color) | Met en surbrillance toutes les correspondances du texte d’exemple avec la couleur spécifiée. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| text | String | Le texte à mettre en surbrillance. |
| highlightColor | Color | La couleur pour mettre le texte en surbrillance. |
**Valeur de retour :**
void

---

### highlightText {#highlightText}

| Nom | Description |
| --- | --- |
| highlightText (String, Color, [TextSearchOptions](../textsearchoptions), [IFindResultCallback](../ifindresultcallback)) | Met en surbrillance toutes les correspondances du texte d’exemple avec la couleur spécifiée. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| text | String | Le texte à mettre en surbrillance. |
| highlightColor | Color | La couleur pour mettre le texte en surbrillance. |
| options | [TextSearchOptions](../textsearchoptions) | Options de recherche de texte ITextSearchOptions. |
| callback | [IFindResultCallback](../ifindresultcallback) | L’objet de rappel pour recevoir les résultats de recherche IFindResultCallback. |
**Valeur de retour :**
void

---

### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Nom | Description |
| --- | --- |
| joinPortionsWithSameFormatting () | Fusionne les segments avec le même formatage dans tous les paragraphes de toutes les formes acceptables de toutes les diapositives. |
**Valeur de retour :**
void

---

### replaceRegex {#replaceRegex}

| Nom | Description |
| --- | --- |
| replaceRegex (Pattern, String, [IFindResultCallback](../ifindresultcallback)) | Remplace toutes les correspondances de l’expression régulière par la chaîne spécifiée. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| regex | Pattern | L’expression régulière java.util.regex.Pattern pour obtenir les chaînes à remplacer. |
| newText | String | La chaîne pour remplacer toutes les occurrences des chaînes à remplacer. |
| callback | [IFindResultCallback](../ifindresultcallback) | L’objet de rappel pour recevoir les résultats de recherche IFindResultCallback. |
**Valeur de retour :**
void

---

### replaceText {#replaceText}

| Nom | Description |
| --- | --- |
| replaceText (String, String, [TextSearchOptions](../textsearchoptions), [IFindResultCallback](../ifindresultcallback)) | Remplace toutes les occurrences du texte spécifié par un autre texte spécifié. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| oldText | String | La chaîne à remplacer. |
| newText | String | La chaîne pour remplacer toutes les occurrences de oldText. |
| options | [TextSearchOptions](../textsearchoptions) | Options de recherche de texte ITextSearchOptions. |
| callback | [IFindResultCallback](../ifindresultcallback) | L’objet de rappel pour recevoir les résultats de recherche IFindResultCallback. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int) | Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int, [RenderingOptions](../renderingoptions)) | Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
| options | [RenderingOptions](../renderingoptions) | Options de format supplémentaires. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int, [PptOptions](../pptoptions)) | Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
| options | [PptOptions](../pptoptions) | Options de format supplémentaires. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int, [XamlOptions](../xamloptions)) | Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
| options | [XamlOptions](../xamloptions) | Options de format supplémentaires. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int, [SVGOptions](../svgoptions)) | Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
| options | [SVGOptions](../svgoptions) | Options de format supplémentaires. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int, [MarkdownSaveOptions](../markdownsaveoptions)) | Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
| options | [MarkdownSaveOptions](../markdownsaveoptions) | Options de format supplémentaires. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int, [HtmlOptions](../htmloptions)) | Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
| options | [HtmlOptions](../htmloptions) | Options de format supplémentaires. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int, [PdfOptions](../pdfoptions)) | Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
| options | [PdfOptions](../pdfoptions) | Options de format supplémentaires. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int, [SwfOptions](../swfoptions)) | Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
| options | [SwfOptions](../swfoptions) | Options de format supplémentaires. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int, [TiffOptions](../tiffoptions)) | Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
| options | [TiffOptions](../tiffoptions) | Options de format supplémentaires. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int, [Html5Options](../html5options)) | Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
| options | [Html5Options](../html5options) | Options de format supplémentaires. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int, [XpsOptions](../xpsoptions)) | Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
| options | [XpsOptions](../xpsoptions) | Options de format supplémentaires. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int, [SaveOptions](../saveoptions)) | Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
| options | [SaveOptions](../saveoptions) | Options de format supplémentaires. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int, [GifOptions](../gifoptions)) | Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
| options | [GifOptions](../gifoptions) | Options de format supplémentaires. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int, [PptxOptions](../pptxoptions)) | Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
| options | [PptxOptions](../pptxoptions) | Options de format supplémentaires. |
**Valeur de retour :**
void

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int, [RenderingOptions](../renderingoptions)) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
| options | [RenderingOptions](../renderingoptions) | Options de format supplémentaires. |
**Valeur de retour :**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int, [PptOptions](../pptoptions)) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
| options | [PptOptions](../pptoptions) | Options de format supplémentaires. |
**Valeur de retour :**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |

---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int, [XamlOptions](../xamloptions)) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié et avec des options supplémentaires. |
**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
| options | [XamlOptions](../xamloptions) | Options de format supplémentaires. |
**Valeur de retour :**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |
| save (OutputStream, int, [SVGOptions](../svgoptions)) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié avec des options supplémentaires. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
| options | [SVGOptions](../svgoptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 **Exception**
 
| Error | Condition |
| --- | --- |
| NotSupportedException | Si vous essayez d’enregistrer un fichier chiffré dans un format non Office 2007-2010 |
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (OutputStream, int, [MarkdownSaveOptions](../markdownsaveoptions)) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié avec des options supplémentaires. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
| options | [MarkdownSaveOptions](../markdownsaveoptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 **Exception**
 
| Error | Condition |
| --- | --- |
| NotSupportedException | Si vous essayez d’enregistrer un fichier chiffré dans un format non Office 2007-2010 |
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (OutputStream, int, [HtmlOptions](../htmloptions)) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié avec des options supplémentaires. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
| options | [HtmlOptions](../htmloptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 **Exception**
 
| Error | Condition |
| --- | --- |
| NotSupportedException | Si vous essayez d’enregistrer un fichier chiffré dans un format non Office 2007-2010 |
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (OutputStream, int, [PdfOptions](../pdfoptions)) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié avec des options supplémentaires. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
| options | [PdfOptions](../pdfoptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 **Exception**
 
| Error | Condition |
| --- | --- |
| NotSupportedException | Si vous essayez d’enregistrer un fichier chiffré dans un format non Office 2007-2010 |
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (OutputStream, int, [SwfOptions](../swfoptions)) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié avec des options supplémentaires. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
| options | [SwfOptions](../swfoptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 **Exception**
 
| Error | Condition |
| --- | --- |
| NotSupportedException | Si vous essayez d’enregistrer un fichier chiffré dans un format non Office 2007-2010 |
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (OutputStream, int, [TiffOptions](../tiffoptions)) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié avec des options supplémentaires. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
| options | [TiffOptions](../tiffoptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 **Exception**
 
| Error | Condition |
| --- | --- |
| NotSupportedException | Si vous essayez d’enregistrer un fichier chiffré dans un format non Office 2007-2010 |
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (OutputStream, int, [Html5Options](../html5options)) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié avec des options supplémentaires. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
| options | [Html5Options](../html5options) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 **Exception**
 
| Error | Condition |
| --- | --- |
| NotSupportedException | Si vous essayez d’enregistrer un fichier chiffré dans un format non Office 2007-2010 |
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (OutputStream, int, [XpsOptions](../xpsoptions)) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié avec des options supplémentaires. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
| options | [XpsOptions](../xpsoptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 **Exception**
 
| Error | Condition |
| --- | --- |
| NotSupportedException | Si vous essayez d’enregistrer un fichier chiffré dans un format non Office 2007-2010 |
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (OutputStream, int, [SaveOptions](../saveoptions)) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié avec des options supplémentaires. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
| options | [SaveOptions](../saveoptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 **Exception**
 
| Error | Condition |
| --- | --- |
| NotSupportedException | Si vous essayez d’enregistrer un fichier chiffré dans un format non Office 2007-2010 |
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (OutputStream, int, [GifOptions](../gifoptions)) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié avec des options supplémentaires. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
| options | [GifOptions](../gifoptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 **Exception**
 
| Error | Condition |
| --- | --- |
| NotSupportedException | Si vous essayez d’enregistrer un fichier chiffré dans un format non Office 2007-2010 |
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (OutputStream, int, [PptxOptions](../pptxoptions)) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié avec des options supplémentaires. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
| options | [PptxOptions](../pptxoptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 **Exception**
 
| Error | Condition |
| --- | --- |
| NotSupportedException | Si vous essayez d’enregistrer un fichier chiffré dans un format non Office 2007-2010 |
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save ([XamlOptions](../xamloptions)) | Enregistre toutes les diapositives d’une présentation dans un ensemble de fichiers représentant le balisage XAML. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| options | [XamlOptions](../xamloptions) | Les options de format XAML. |
 
 **Retour :**
void
 
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (String, int[], int) | Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format spécifié tout en conservant le numéro de page. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
 
 **Retour :**
void
 
 **Exception**
 
| Error | Condition |
| --- | --- |
| InvalidOperationException | Lorsqu’un SaveFormat non pris en charge est utilisé, par ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (String, int[], int, [RenderingOptions](../renderingoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format spécifié tout en conservant le numéro de page. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [RenderingOptions](../renderingoptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (String, int[], int, [PptOptions](../pptoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format spécifié tout en conservant le numéro de page. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [PptOptions](../pptoptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (String, int[], int, [XamlOptions](../xamloptions)) | Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format spécifié tout en conservant le numéro de page. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [XamlOptions](../xamloptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (String, int[], int, [SVGOptions](../svgoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format spécifié tout en conservant le numéro de page. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [SVGOptions](../svgoptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (String, int[], int, [MarkdownSaveOptions](../markdownsaveoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format spécifié tout en conservant le numéro de page. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [MarkdownSaveOptions](../markdownsaveoptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (String, int[], int, [HtmlOptions](../htmloptions)) | Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format spécifié tout en conservant le numéro de page. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [HtmlOptions](../htmloptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (String, int[], int, [PdfOptions](../pdfoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format spécifié tout en conservant le numéro de page. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [PdfOptions](../pdfoptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (String, int[], int, [SwfOptions](../swfoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format spécifié tout en conservant le numéro de page. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [SwfOptions](../swfoptions) | Options de format supplémentaires. |
 
 **Retour :**
void
 
 
 
---
 
### save {#save}
 
| Name | Description |
| --- | --- |
| save (String, int[], int, [TiffOptions](../tiffoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format spécifié tout en conservant le numéro de page. |
 
 **Paramètres :**
 
| Name | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [TiffOptions](../tiffoptions) | Options de format supplémentaires. |
 
 **Retour :**
void
| save (String, int[], int, [Html5Options](../html5options)) | Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [Html5Options](../html5options) | Options de format supplémentaires. |

 **Retourne:**
void


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int[], int, [XpsOptions](../xpsoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [XpsOptions](../xpsoptions) | Options de format supplémentaires. |

 **Retourne:**
void


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int[], int, [SaveOptions](../saveoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [SaveOptions](../saveoptions) | Options de format supplémentaires. |

 **Retourne:**
void


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int[], int, [GifOptions](../gifoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [GifOptions](../gifoptions) | Options de format supplémentaires. |

 **Retourne:**
void


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int[], int, [PptxOptions](../pptxoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [PptxOptions](../pptxoptions) | Options de format supplémentaires. |

 **Retourne:**
void


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int[], int) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |

 **Retourne:**
void


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int[], int, [RenderingOptions](../renderingoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [RenderingOptions](../renderingoptions) | Options de format supplémentaires. |

 **Retourne:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Lorsqu’un SaveFormat non supporté est utilisé, p. ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int[], int, [PptOptions](../pptoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [PptOptions](../pptoptions) | Options de format supplémentaires. |

 **Retourne:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Lorsqu’un SaveFormat non supporté est utilisé, p. ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int[], int, [XamlOptions](../xamloptions)) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [XamlOptions](../xamloptions) | Options de format supplémentaires. |

 **Retourne:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Lorsqu’un SaveFormat non supporté est utilisé, p. ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int[], int, [SVGOptions](../svgoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [SVGOptions](../svgoptions) | Options de format supplémentaires. |

 **Retourne:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Lorsqu’un SaveFormat non supporté est utilisé, p. ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int[], int, [MarkdownSaveOptions](../markdownsaveoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [MarkdownSaveOptions](../markdownsaveoptions) | Options de format supplémentaires. |

 **Retourne:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Lorsqu’un SaveFormat non supporté est utilisé, p. ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int[], int, [HtmlOptions](../htmloptions)) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [HtmlOptions](../htmloptions) | Options de format supplémentaires. |

 **Retourne:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Lorsqu’un SaveFormat non supporté est utilisé, p. ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int[], int, [PdfOptions](../pdfoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [PdfOptions](../pdfoptions) | Options de format supplémentaires. |

 **Retourne:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Lorsqu’un SaveFormat non supporté est utilisé, p. ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int[], int, [SwfOptions](../swfoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [SwfOptions](../swfoptions) | Options de format supplémentaires. |

 **Retourne:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Lorsqu’un SaveFormat non supporté est utilisé, p. ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int[], int, [TiffOptions](../tiffoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [TiffOptions](../tiffoptions) | Options de format supplémentaires. |

 **Retourne:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Lorsqu’un SaveFormat non supporté est utilisé, p. ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int[], int, [Html5Options](../html5options)) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [Html5Options](../html5options) | Options de format supplémentaires. |

 **Retourne:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Lorsqu’un SaveFormat non supporté est utilisé, p. ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int[], int, [XpsOptions](../xpsoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [XpsOptions](../xpsoptions) | Options de format supplémentaires. |

 **Retourne:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Lorsqu’un SaveFormat non supporté est utilisé, p. ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int[], int, [SaveOptions](../saveoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [SaveOptions](../saveoptions) | Options de format supplémentaires. |

 **Retourne:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Lorsqu’un SaveFormat non supporté est utilisé, p. ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---

### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int[], int, [GifOptions](../gifoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué tout en conservant le numéro de page. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [GifOptions](../gifoptions) | Options de format supplémentaires. |

 **Retourne:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Lorsqu’un SaveFormat non supporté est utilisé, p. ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---

### save {#save}

| Nom | Description |
| --- | --- |

| save (OutputStream, int[], int, [PptxOptions](../pptxoptions)) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué tout en conservant le numéro de page. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux de sortie. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [PptxOptions](../pptxoptions) | Options de format supplémentaires. |

**Retour :**  
void

**Exception**

| Error | Condition |
| --- | --- |
| InvalidOperationException | Lorsqu’un SaveFormat non pris en charge est utilisé, par ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

---

### setCurrentDateTime {#setCurrentDateTime}

| Nom | Description |
| --- | --- |
| setCurrentDateTime (Date) | Renvoie ou définit la date et l'heure qui remplaceront le contenu des champs datetime. Heure de création de cet objet Presentation par défaut. Lecture/écriture java.util.Date. |

**Retour :**  
void

---

### setFirstSlideNumber {#setFirstSlideNumber}

| Nom | Description |
| --- | --- |
| setFirstSlideNumber (int) | Représente le numéro de la première diapositive dans la présentation |

**Retour :**  
void

---

### setVbaProject {#setVbaProject}

| Nom | Description |
| --- | --- |
| setVbaProject ([VbaProject](../vbaproject)) | Obtient ou définit le projet VBA avec les macros de la présentation. Lecture/écriture IVbaProject. |

**Retour :**  
void

---