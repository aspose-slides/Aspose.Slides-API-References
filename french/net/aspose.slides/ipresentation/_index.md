---
title: IPresentation
second_title: Référence de l'API Aspose.Slides pour .NET
description: Document de présentation
type: docs
weight: 6220
url: /fr/net/aspose.slides/ipresentation/
---
## IPresentation interface

Document de présentation

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Renvoie toutes les parties de données personnalisées dans la présentation. Lecture seule[`ICustomXmlPart`](../icustomxmlpart) []. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Renvoie IInterface jetable. Lecture seuleIDisposable . |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Permet d'obtenir l'interface IPresentationComponent de base. Lecture seule[`IPresentationComponent`](../ipresentationcomponent) . |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Renvoie la collection de tous les fichiers audio intégrés dans la présentation. Lecture seule[`IAudioCollection`](../iaudiocollection) . |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Renvoie la collection des auteurs de commentaires. Lecture seule[`ICommentAuthorCollection`](../icommentauthorcollection) . |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Renvoie ou définit la date et l'heure qui remplaceront le contenu des champs datetime. Heure de création de cet objet Presentation par défaut. Lecture/écritureDateTime . |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Renvoie les données personnalisées de la présentation. Lecture seule[`ICustomData`](../icustomdata) . |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Renvoie le style de texte par défaut pour les formes. Lecture seule[`ITextStyle`](../itextstyle) . |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Renvoie la collection de signatures utilisées pour signer la présentation. Lecture seule[`IDigitalSignatureCollection`](../idigitalsignaturecollection) . |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Renvoie l'objet DocumentProperties qui contient les propriétés de document standard et personnalisées. Lecture seule[`IDocumentProperties`](../idocumentproperties) . |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Représente le numéro de la première diapositive de la présentation. Lecture/écritureInt32 . |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Renvoie le gestionnaire de polices. Lecture seule[`IFontsManager`](../ifontsmanager) . |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Renvoie HeaderFooter gestionnaire de la présentation. Lecture seule[`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager) . |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Fournit un accès facile à tous les hyperliens contenus dans toutes les diapositives de présentation (pas dans le masque, la mise en page, les diapositives de notes). En lecture seule[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Renvoie la collection de toutes les images de la présentation. Lecture seule[`IImageCollection`](../iimagecollection) . |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Renvoie une liste de toutes les diapositives de mise en page définies dans la présentation. Lecture seule[`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection) . |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Renvoie le gestionnaire principal du document. Lecture seule[`IMasterHandoutSlideManager`](../imasterhandoutslidemanager) . |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Renvoie le gestionnaire principal des notes. Lecture seule[`IMasterNotesSlideManager`](../imasternotesslidemanager) . |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Renvoie une liste de toutes les diapositives principales définies dans la présentation. Lecture seule[`IMasterSlideCollection`](../imasterslidecollection) . |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Renvoie le thème principal de la présentation. Lecture seule[`IMasterTheme`](../../aspose.slides.theme/imastertheme) . |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Renvoie un objet de taille de diapositive de notes. En lecture seule[`INotesSize`](../inotessize) . |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Obtient le gestionnaire des autorisations pour cette présentation. Lecture seule[`IProtectionManager`](../iprotectionmanager) . |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Renvoie une liste de toutes les sections de diapositives définies dans la présentation. Lecture seule[`ISectionCollection`](../isectioncollection) . |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Renvoie une liste de toutes les diapositives définies dans la présentation. Lecture seule[`ISlideCollection`](../islidecollection) . |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Renvoie l'objet de taille de diapositive. Lecture seule[`ISlideSize`](../islidesize) . |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Renvoie des informations sur le format à partir duquel la présentation a été chargée. Lecture seule[`SourceFormat`](./sourceformat) . |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Obtient le projet VBA avec les macros de présentation. Lecture/écriture[`IVbaProject`](../../aspose.slides.vba/ivbaproject) . |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Renvoie la collection de tous les fichiers vidéo intégrés dans la présentation. Lecture seule[`IVideoCollection`](../ivideocollection) . |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Obtient les propriétés de la vue large de la présentation. Lecture seule[`IViewProperties`](../iviewproperties) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Renvoie une Slide, MasterSlide ou LayoutSlide par Id. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_6)(IRenderingOptions) | Renvoie un objet Thumbnail Bitmap pour toutes les diapositives d'une présentation. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_7)(IRenderingOptions, int[]) | Renvoie un objet Thumbnail Bitmap pour les diapositives spécifiées d'une présentation. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_11)(IRenderingOptions, Size) | Renvoie un objet Thumbnail Bitmap pour toutes les diapositives d'une présentation avec la taille spécifiée. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_10)(IRenderingOptions, float, float) | Renvoie un objet Thumbnail Bitmap pour toutes les diapositives d'une présentation avec une mise à l'échelle personnalisée. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_9)(IRenderingOptions, int[], Size) | Renvoie un objet Thumbnail Bitmap pour les diapositives spécifiées d'une présentation avec la taille spécifiée. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_8)(IRenderingOptions, int[], float, float) | Renvoie des objets Thumbnail Bitmap pour les diapositives spécifiées d'une présentation avec une mise à l'échelle personnalisée. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Les jointures s'exécutent avec le même formatage dans tous les paragraphes dans toutes les formes acceptables dans toutes les diapositives. |
| [Print](../../aspose.slides/ipresentation/print#print)() | Imprime toute la présentation sur l'imprimante par défaut. |
| [Print](../../aspose.slides/ipresentation/print#print_1)(PrinterSettings) | Imprime la présentation en fonction des paramètres d'imprimante spécifiés, à l'aide du contrôleur d'impression standard (pas d'interface utilisateur). |
| [Print](../../aspose.slides/ipresentation/print#print_3)(string) | Imprimer toute la présentation sur l'imprimante spécifiée, en utilisant le contrôleur d'impression standard (pas d'interface utilisateur). |
| [Print](../../aspose.slides/ipresentation/print#print_2)(PrinterSettings, string) | Imprime le document conformément aux paramètres d'imprimante spécifiés, en utilisant le contrôleur d'impression standard (pas d'interface utilisateur) et un nom de présentation. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Enregistre toutes les diapositives d'une présentation dans un ensemble de fichiers représentant le balisage XAML. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Enregistre toutes les diapositives d'une présentation dans un fichier au format spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié et avec des options supplémentaires. |
| [Save](../../aspose.slides/ipresentation/save#save_9)(string, int[], SaveFormat) | Enregistre les diapositives spécifiées d'une présentation dans un fichier au format spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Enregistre toutes les diapositives d'une présentation dans un fichier au format spécifié et avec des options supplémentaires. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save_10)(string, int[], SaveFormat, ISaveOptions) | Enregistre les diapositives spécifiées d'une présentation dans un fichier au format spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, SaveFormat, HttpResponse, bool) | Envoie la présentation au navigateur client. Cette méthode est absente des versions ClientProfile d'Aspose.Slide. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, SaveFormat, ISaveOptions, HttpResponse, bool) | Envoie la présentation au navigateur client. Cette méthode est absente des versions ClientProfile d'Aspose.Slide. |

### Voir également

* interface [IPresentationComponent](../ipresentationcomponent)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
