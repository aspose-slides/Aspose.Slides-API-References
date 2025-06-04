---
title: Presentation
second_title: Aspose.Sildes pour .NET API Reference
description: Représente une présentation Microsoft PowerPoint.
type: docs
weight: 9320
url: /fr/aspose.slides/presentation/
---

## Classe Presentation

Représente une présentation Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Presentation](presentation#constructor)() | Ce constructeur crée une nouvelle présentation à partir de zéro. La présentation créée a une diapositive vide. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Ce constructeur crée une nouvelle présentation à partir de zéro. La présentation créée a une diapositive vide. |
| [Presentation](presentation#constructor_2)(Stream) | Ce constructeur est le mécanisme principal pour lire une présentation existante. |
| [Presentation](presentation#constructor_4)(string) | Ce constructeur obtient un chemin de fichier source à partir duquel le contenu de la présentation est lu. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Ce constructeur est le mécanisme principal pour lire une présentation existante. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Ce constructeur obtient un chemin de fichier source à partir duquel le contenu de la présentation est lu. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Renvoie toutes les parties de données personnalisées dans la présentation. Lecture seule [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Renvoie la collection de tous les fichiers audio intégrés dans la présentation. Lecture seule [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Renvoie la collection des auteurs de commentaires. Lecture seule [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Renvoie ou définit la date et l'heure qui remplaceront le contenu des champs datetime. Heure de création de cet objet Presentation par défaut. Lecture/écriture DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Renvoie les données personnalisées de la présentation. Lecture seule [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Renvoie le style de texte par défaut pour les formes. Lecture seule [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Renvoie la collection de signatures utilisées pour signer la présentation. Lecture seule [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Renvoie l'objet DocumentProperties qui contient les propriétés de document standard et personnalisées. Lecture seule [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Représente le numéro de la première diapositive dans la présentation |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Renvoie le gestionnaire de polices. Lecture seule [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Renvoie le gestionnaire actuel de HeaderFooter. Lecture seule [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Fournit un accès facile à tous les hyperliens contenus dans toutes les diapositives de la présentation (pas dans le maître, la mise en page, les diapositives de notes). Lecture seule [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Renvoie la collection de toutes les images dans la présentation. Lecture seule [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Renvoie une liste de toutes les diapositives de mise en page qui sont définies dans la présentation. Lecture seule [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Renvoie le gestionnaire de main des diapositives. Lecture seule [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Renvoie le gestionnaire de notes maître. Lecture seule [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Renvoie une liste de toutes les diapositives maîtresses qui sont définies dans la présentation. Lecture seule [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Renvoie le thème maître. Lecture seule [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Renvoie l'objet de taille de diapositive de notes. Lecture seule [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Obtient le gestionnaire des autorisations pour cette présentation. Lecture seule [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Renvoie une liste de toutes les sections de diapositives qui sont définies dans la présentation. Lecture seule [`ISectionCollection`](../isectioncollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Renvoie une liste de toutes les diapositives qui sont définies dans la présentation. Lecture seule [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Renvoie les paramètres du diaporama pour la présentation. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Renvoie l'objet de taille de diapositive. Lecture seule [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Renvoie des informations sur le format à partir duquel la présentation a été chargée. Lecture seule [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Obtient ou définit le projet VBA avec les macros de la présentation. Lecture/écriture [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Renvoie la collection de tous les fichiers vidéo intégrés dans la présentation. Lecture seule [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Obtient les propriétés de vue à l'échelle de la présentation. Lecture seule [`IViewProperties`](../iviewproperties). |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Libère toutes les ressources utilisées par cet objet Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Renvoie des objets Image pour toutes les diapositives d'une présentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Renvoie des objets Image Miniature pour les diapositives spécifiées d'une présentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Renvoie des objets Image Miniature pour toutes les diapositives d'une présentation avec une taille spécifiée. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Renvoie des objets Image Miniature pour toutes les diapositives d'une présentation avec un redimensionnement personnalisé. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Renvoie des objets Image Miniature pour les diapositives spécifiées d'une présentation avec une taille spécifiée. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Renvoie des objets Image Miniature pour les diapositives spécifiées d'une présentation avec un redimensionnement personnalisé. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Renvoie une Diapositive, MasterSlide ou LayoutSlide par Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Surligne toutes les correspondances de l'expression régulière avec la couleur spécifiée. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Surligne toutes les correspondances du texte échantillon avec la couleur spécifiée. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Surligne toutes les correspondances du texte échantillon avec la couleur spécifiée. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Joint les portions avec le même formatage dans tous les paragraphes de toutes les formes acceptables dans toutes les diapositives. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Remplace toutes les occurrences du texte spécifié par un autre texte spécifié. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Enregistre toutes les diapositives d'une présentation dans un ensemble de fichiers représentant le balisage XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Enregistre toutes les diapositives d'une présentation dans un fichier avec le format spécifié. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié avec conservation de la numérotation des pages. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié et avec des options supplémentaires. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Enregistre les diapositives spécifiées d'une présentation dans un fichier avec le format spécifié avec conservation de la numérotation des pages. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié avec conservation de la numérotation des pages. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Enregistre les diapositives spécifiées d'une présentation dans un fichier avec le format spécifié avec conservation de la numérotation des pages. |

### Exemples

L'exemple suivant montre comment créer une présentation PowerPoint.

```csharp
[C#]
// Instancier un objet Presentation qui représente un fichier de présentation
using (Presentation presentation = new Presentation())
{
    // Obtenir la première diapositive
    ISlide slide = presentation.Slides[0];
    // Ajouter une forme automatique de type ligne
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
    // Enregistrer le fichier de présentation.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

L'exemple suivant montre comment ouvrir et enregistrer une présentation.

```csharp
[C#]
// Charger tout fichier pris en charge dans la présentation e.g. ppt, pptx, odp etc.
using (Presentation presentation = new Presentation("Sample.odp"))
{
    // Enregistrer le fichier de présentation.
    presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* interface [IPresentation](../ipresentation)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->