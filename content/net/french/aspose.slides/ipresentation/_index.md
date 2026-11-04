---
title: IPresentation
second_title: Référence API Aspose.Sildes pour .NET
description: Document de présentation
type: docs
weight: 6770
url: /fr/aspose.slides/ipresentation/
---
## IPresentation interface

Document de présentation

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Propriétés

| Name | Description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Renvoie toutes les parties de données personnalisées de la présentation. Lecture seule [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Renvoie l'interface IDisposable. Lecture seule IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Permet d'obtenir l'interface IPresentationComponent de base. Lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Renvoie la collection de tous les fichiers audio intégrés dans la présentation. Lecture seule [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Renvoie la collection d'auteurs de commentaires. Lecture seule [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Renvoie ou définit la date et l'heure qui substitueront le contenu des champs datetime. Heure de création de cet objet Presentation par défaut. Lecture/écriture DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Renvoie les données personnalisées de la présentation. Lecture seule [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Renvoie le style de texte par défaut pour les formes. Lecture seule [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Renvoie la collection de signatures utilisées pour signer la présentation. Lecture seule [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Renvoie l'objet DocumentProperties qui contient les propriétés de document standard et personnalisées. Lecture seule [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Représente le numéro de la première diapositive dans la présentation. Lecture/écriture Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Renvoie le gestionnaire de polices. Lecture seule [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Renvoie le gestionnaire d'en-tête/pied de page de la présentation. Lecture seule [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Fournit un accès facile à tous les hyperliens contenus dans toutes les diapositives de la présentation (pas dans les diapositives maître, mise en page, notes). Lecture seule [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Renvoie la collection de toutes les images de la présentation. Lecture seule [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Renvoie une liste de toutes les diapositives de mise en page définies dans la présentation. Lecture seule [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Renvoie le gestionnaire du maître de support. Lecture seule [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Renvoie le gestionnaire du maître de notes. Lecture seule [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Renvoie une liste de toutes les diapositives maîtres définies dans la présentation. Lecture seule [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Renvoie le thème maître de la présentation. Lecture seule [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Renvoie l'objet taille de diapositive de notes. Lecture seule [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Renvoie le gestionnaire des autorisations pour cette présentation. Lecture seule [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Renvoie une liste de toutes les sections de diapositives définies dans la présentation. Lecture seule [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Renvoie la collection d'étiquettes de sensibilité appliquées au document de présentation. Lecture seule [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Renvoie une liste de toutes les diapositives définies dans la présentation. Lecture seule [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Renvoie l'objet taille de diapositive. Lecture seule [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Renvoie des informations sur le format à partir duquel la présentation a été chargée. Lecture seule [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Renvoie le projet VBA avec les macros de la présentation. Lecture/écriture [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Renvoie la collection de tous les fichiers vidéo intégrés dans la présentation. Lecture seule [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Renvoie les propriétés de vue globales de la présentation. Lecture seule [`IViewProperties`](../iviewproperties). |

## Méthodes

| Name | Description |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Renvoie des objets Image miniature pour toutes les diapositives d'une présentation. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Renvoie des objets Bitmap miniature pour les diapositives spécifiées d'une présentation. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Renvoie des objets Image miniature pour toutes les diapositives d'une présentation avec la taille spécifiée. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Renvoie des objets Image miniature pour toutes les diapositives d'une présentation avec un redimensionnement personnalisé. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Renvoie des objets Image miniature pour les diapositives spécifiées d'une présentation avec la taille spécifiée. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Renvoie des objets Image miniature pour les diapositives spécifiées d'une présentation avec un redimensionnement personnalisé. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Renvoie une Slide, MasterSlide ou LayoutSlide par Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Surligne toutes les correspondances de l'expression régulière avec la couleur spécifiée. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Surligne toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Surligne toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Combine les runs avec le même formatage dans tous les paragraphes de toutes les formes admissibles de toutes les diapositives. |
| [RefreshChartsData](../../aspose.slides/ipresentation/refreshchartsdata)(bool) | Recharge les données de tous les graphiques de la présentation à partir de leurs classeurs source. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Remplace toutes les occurrences du texte spécifié par un autre texte spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Enregistre toutes les diapositives d'une présentation dans un ensemble de fichiers représentant le balisage XAML. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Enregistre toutes les diapositives d'une présentation dans un fichier au format spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié avec des options supplémentaires. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Enregistre les diapositives spécifiées d'une présentation dans un fichier au format spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Enregistre toutes les diapositives d'une présentation dans un fichier au format spécifié avec des options supplémentaires. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Enregistre les diapositives spécifiées d'une présentation dans un fichier au format spécifié. |

### Voir aussi

* interface [IPresentationComponent](../ipresentationcomponent)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->