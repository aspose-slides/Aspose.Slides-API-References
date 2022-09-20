---
title: Presentation
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une présentation Microsoft PowerPoint.
type: docs
weight: 8890
url: /fr/net/aspose.slides/presentation/
---
## Presentation class

Représente une présentation Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Presentation](presentation#constructor)() | Ce constructeur crée une nouvelle présentation à partir de zéro. La présentation créée a une diapositive vide. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Ce constructeur crée une nouvelle présentation à partir de zéro. La présentation créée a une diapositive vide. |
| [Presentation](presentation#constructor_2)(Stream) | Ce constructeur est le principal mécanisme de lecture d'une présentation existante. |
| [Presentation](presentation#constructor_4)(string) | Ce constructeur obtient un chemin de fichier source à partir duquel le contenu de la présentation est lu. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Ce constructeur est le principal mécanisme de lecture d'une présentation existante. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Ce constructeur obtient un chemin de fichier source à partir duquel le contenu de la présentation est lu. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Renvoie toutes les parties de données personnalisées dans la présentation. Lecture seule[`ICustomXmlPart`](../icustomxmlpart) []. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Renvoie la collection de tous les fichiers audio intégrés dans la présentation. Lecture seule[`IAudioCollection`](../iaudiocollection) . |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Renvoie la collection des auteurs de commentaires. Lecture seule[`ICommentAuthorCollection`](../icommentauthorcollection) . |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Renvoie ou définit la date et l'heure qui remplaceront le contenu des champs datetime. Heure de création de cet objet Presentation par défaut. Lecture/écritureDateTime . |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Renvoie les données personnalisées de la présentation. Lecture seule[`ICustomData`](../icustomdata) . |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Renvoie le style de texte par défaut pour les formes. Lecture seule[`ITextStyle`](../itextstyle) . |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Renvoie la collection de signatures utilisées pour signer la présentation. Lecture seule[`IDigitalSignatureCollection`](../idigitalsignaturecollection) . |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Renvoie l'objet DocumentProperties qui contient les propriétés de document standard et personnalisées. Lecture seule[`IDocumentProperties`](../idocumentproperties) . |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Représente le premier numéro de diapositive dans la présentation |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Renvoie le gestionnaire de polices. Lecture seule[`IFontsManager`](../ifontsmanager) . |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Renvoie le gestionnaire HeaderFooter réel. Lecture seule[`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager) . |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Fournit un accès facile à tous les hyperliens contenus dans toutes les diapositives de présentation (pas dans le masque, la mise en page, les diapositives de notes). En lecture seule[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| [Images](../../aspose.slides/presentation/images) { get; } | Renvoie la collection de toutes les images de la présentation. Lecture seule[`IImageCollection`](../iimagecollection) . |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Renvoie une liste de toutes les diapositives de mise en page définies dans la présentation. Lecture seule[`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection) . |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Renvoie le gestionnaire principal du document. Lecture seule[`IMasterHandoutSlideManager`](../imasterhandoutslidemanager) . |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Renvoie le gestionnaire principal des notes. Lecture seule[`IMasterNotesSlideManager`](../imasternotesslidemanager) . |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Renvoie une liste de toutes les diapositives principales définies dans la présentation. Lecture seule[`IMasterSlideCollection`](../imasterslidecollection) . |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Renvoie le thème principal. Lecture seule[`IMasterTheme`](../../aspose.slides.theme/imastertheme) . |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Renvoie un objet de taille de diapositive de notes. En lecture seule[`INotesSize`](../inotessize) . |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Obtient le gestionnaire des autorisations pour cette présentation. Lecture seule[`IProtectionManager`](../iprotectionmanager) . |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Renvoie une liste de toutes les sections de diapositives définies dans la présentation. Lecture seule[`ISectionCollection`](../isectioncollection) . |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Renvoie une liste de toutes les diapositives définies dans la présentation. Lecture seule[`ISlideCollection`](../islidecollection) . |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Renvoie les paramètres du diaporama pour la présentation. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Renvoie l'objet de taille de diapositive. Lecture seule[`ISlideSize`](../islidesize) . |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Renvoie des informations sur le format à partir duquel la présentation a été chargée. Lecture seule[`SourceFormat`](../sourceformat) . |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Obtient ou définit le projet VBA avec des macros de présentation. Lecture/écriture[`IVbaProject`](../../aspose.slides.vba/ivbaproject) . |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Renvoie la collection de tous les fichiers vidéo intégrés dans la présentation. Lecture seule[`IVideoCollection`](../ivideocollection) . |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Obtient les propriétés de la vue large de la présentation. Lecture seule[`IViewProperties`](../iviewproperties) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Libère toutes les ressources utilisées par cet objet de présentation. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Renvoie une Slide, MasterSlide ou LayoutSlide par Id. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_6)(IRenderingOptions) | Renvoie un objet Thumbnail Bitmap pour toutes les diapositives d'une présentation. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_7)(IRenderingOptions, int[]) | Renvoie un objet Thumbnail Bitmap pour les diapositives spécifiées d'une présentation. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_11)(IRenderingOptions, Size) | Renvoie un objet Thumbnail Bitmap pour toutes les diapositives d'une présentation avec la taille spécifiée. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_10)(IRenderingOptions, float, float) | Renvoie un objet Thumbnail Bitmap pour toutes les diapositives d'une présentation avec une mise à l'échelle personnalisée. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_9)(IRenderingOptions, int[], Size) | Renvoie un objet Thumbnail Bitmap pour les diapositives spécifiées d'une présentation avec la taille spécifiée. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_8)(IRenderingOptions, int[], float, float) | Renvoie des objets Thumbnail Bitmap pour les diapositives spécifiées d'une présentation avec une mise à l'échelle personnalisée. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Les jointures s'exécutent avec le même formatage dans tous les paragraphes dans toutes les formes acceptables dans toutes les diapositives. |
| [Print](../../aspose.slides/presentation/print#print)() | Imprime toute la présentation sur l'imprimante par défaut. |
| [Print](../../aspose.slides/presentation/print#print_1)(PrinterSettings) | Imprime la présentation en fonction des paramètres d'imprimante spécifiés, à l'aide du contrôleur d'impression standard (pas d'interface utilisateur). |
| [Print](../../aspose.slides/presentation/print#print_3)(string) | Imprimer toute la présentation sur l'imprimante spécifiée, en utilisant le contrôleur d'impression standard (pas d'interface utilisateur). |
| [Print](../../aspose.slides/presentation/print#print_2)(PrinterSettings, string) | Imprime le document conformément aux paramètres d'imprimante spécifiés, en utilisant le contrôleur d'impression standard (pas d'interface utilisateur) et un nom de présentation. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Enregistre toutes les diapositives d'une présentation dans un ensemble de fichiers représentant le balisage XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Enregistre toutes les diapositives d'une présentation dans un fichier au format spécifié. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié en conservant le numéro de page. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié et avec des options supplémentaires. |
| [Save](../../aspose.slides/presentation/save#save_9)(string, int[], SaveFormat) | Enregistre les diapositives spécifiées d'une présentation dans un fichier au format spécifié en conservant le numéro de page. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) | Enregistre toutes les diapositives d'une présentation dans un fichier au format spécifié et avec des options supplémentaires. |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié en conservant le numéro de page. |
| [Save](../../aspose.slides/presentation/save#save_10)(string, int[], SaveFormat, ISaveOptions) | Enregistre les diapositives spécifiées d'une présentation dans un fichier au format spécifié en conservant le numéro de page. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, SaveFormat, HttpResponse, bool) | Envoie la présentation au navigateur client. Cette méthode est absente des versions ClientProfile d'Aspose.Slide. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, SaveFormat, ISaveOptions, HttpResponse, bool) | Envoie la présentation au navigateur client. Cette méthode est absente des versions ClientProfile d'Aspose.Slide. |

### Voir également

* interface [IPresentation](../ipresentation)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
