---
title: IPresentation
second_title: Référence de l'API Aspose.Slides pour .NET
description: Document de présentation
type: docs
weight: 6550
url: /fr/aspose.slides/ipresentation/
---

## Interface IPresentation

Document de présentation

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Retourne toutes les parties de données personnalisées dans la présentation. Lecture seule [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Retourne l'interface IDisposable. Lecture seule IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. Lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Retourne la collection de tous les fichiers audio intégrés dans la présentation. Lecture seule [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Retourne la collection des auteurs de commentaires. Lecture seule [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Retourne ou définit la date et l'heure qui remplaceront le contenu des champs de date et d'heure. Heure de création de cet objet de présentation par défaut. Lecture/écriture DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Retourne les données personnalisées de la présentation. Lecture seule [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Retourne le style de texte par défaut pour les formes. Lecture seule [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Retourne la collection de signatures utilisées pour signer la présentation. Lecture seule [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Retourne l'objet DocumentProperties qui contient les propriétés document standard et personnalisées. Lecture seule [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Représente le numéro de la première diapositive dans la présentation. Lecture/écriture Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Retourne le gestionnaire de polices. Lecture seule [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Retourne le gestionnaire d'en-têtes et de pieds de page de la présentation. Lecture seule [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Fournit un accès facile à tous les hyperliens contenus dans toutes les diapositives de la présentation (pas dans la diapositive maître, la mise en page, les diapositives de notes). Lecture seule [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Retourne la collection de toutes les images dans la présentation. Lecture seule [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Retourne une liste de toutes les diapositives de mise en page qui sont définies dans la présentation. Lecture seule [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Retourne le gestionnaire de modèles de distribution. Lecture seule [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Retourne le gestionnaire de notes de maître. Lecture seule [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Retourne une liste de toutes les diapositives maîtresses qui sont définies dans la présentation. Lecture seule [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Retourne le thème maître de la présentation. Lecture seule [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Retourne l'objet de taille des notes. Lecture seule [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Obtient le gestionnaire des autorisations pour cette présentation. Lecture seule [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Retourne une liste de toutes les sections de diapositives qui sont définies dans la présentation. Lecture seule [`ISectionCollection`](../isectioncollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Retourne une liste de toutes les diapositives qui sont définies dans la présentation. Lecture seule [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Retourne l'objet de taille de diapositive. Lecture seule [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Retourne des informations sur le format à partir duquel la présentation a été chargée. Lecture seule [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Obtient le projet VBA avec des macros de présentation. Lecture/écriture [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Retourne la collection de tous les fichiers vidéo intégrés dans la présentation. Lecture seule [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Obtient les propriétés de vue étendues de la présentation. Lecture seule [`IViewProperties`](../iviewproperties). |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Retourne des objets d'image miniature pour toutes les diapositives d'une présentation. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Retourne des objets de bitmap miniature pour des diapositives spécifiées d'une présentation. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Retourne des objets de miniature d'image pour toutes les diapositives d'une présentation avec une taille spécifiée. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Retourne des objets de miniature d'image pour toutes les diapositives d'une présentation avec un redimensionnement personnalisé. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Retourne des objets de miniature d'image pour des diapositives spécifiées d'une présentation avec une taille spécifiée. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Retourne des objets de miniature d'image pour des diapositives spécifiées d'une présentation avec un redimensionnement personnalisé. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Retourne une diapositive, MasterSlide ou LayoutSlide par ID. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Met en surbrillance toutes les occurrences de l'expression régulière avec la couleur spécifiée. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Met en surbrillance toutes les occurrences du texte de l'exemple avec la couleur spécifiée. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Met en surbrillance toutes les occurrences du texte de l'exemple avec la couleur spécifiée. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Joint les segments avec le même formatage dans tous les paragraphes de toutes les formes acceptables dans toutes les diapositives. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Remplace toutes les occurrences de l'expression régulière par la chaîne spécifiée. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Remplace toutes les occurrences du texte spécifié par un autre texte spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Enregistre toutes les diapositives d'une présentation dans un ensemble de fichiers représentant le balisage XAML. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Enregistre toutes les diapositives d'une présentation dans un fichier avec le format spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié et avec des options supplémentaires. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Enregistre les diapositives spécifiées d'une présentation dans un fichier avec le format spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Enregistre toutes les diapositives d'une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Enregistre les diapositives spécifiées d'une présentation dans un fichier avec le format spécifié. |

### Voir aussi

* interface [IPresentationComponent](../ipresentationcomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->