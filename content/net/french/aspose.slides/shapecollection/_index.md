---
title: ShapeCollection
second_title: Aspose.Sildes pour .NET Référence d'API
description: Représente une collection de formes.
type: docs
weight: 9880
url: /fr/aspose.slides/shapecollection/
---
## ShapeCollection classe

Représente une collection de formes.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Obtient l'élément à l'index spécifié. Lecture seule [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Obtient l'objet de forme de groupe parent pour la collection de formes. Lecture seule [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Renvoie une racine de synchronisation. Lecture seule Object. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Crée une nouvelle trame audio liée à une piste CD et l'ajoute à la fin de la collection de formes. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Crée une nouvelle trame audio et l'ajoute à la fin de la collection de formes en utilisant un objet audio existant de la liste Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Crée une nouvelle trame audio avec un fichier WAV intégré et l'ajoute à la fin de la collection de formes. L'audio intégré est ajouté à la collection Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Crée une nouvelle trame audio liée à un fichier audio externe et l'ajoute à la fin de la collection de formes. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Crée une nouvelle forme auto avec un formatage par défaut et l'ajoute à la fin de la collection de formes. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Crée une nouvelle forme auto et l'ajoute à la fin de la collection de formes, en option l'initialisant avec le formatage de modèle par défaut. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Crée un nouveau graphique, l'initialise avec des données et paramètres d'exemple de série, et l'ajoute à la fin de la collection de formes. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Crée un nouveau graphique, l'initialise avec des données et paramètres d'exemple de série, et l'ajoute à la fin de la collection de formes. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille de l'original. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur du *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Crée une nouvelle forme de connecteur avec le style de modèle par défaut et l'ajoute à la fin de la collection de formes. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Crée une nouvelle forme de connecteur et l'ajoute à la fin de la collection de formes, en option appliquant le style de modèle par défaut. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Crée une nouvelle forme de groupe vide et l'ajoute à la fin de la collection de formes. Le cadre du groupe s'ajustera automatiquement pour contenir les formes ajoutées. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Crée une nouvelle forme de groupe, convertit l'image SVG spécifiée en formes individuelles, et ajoute le groupe résultant à la fin de la collection de formes. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Crée une nouvelle forme auto rectangle pour héberger du contenu mathématique et l'ajoute à la fin de la collection de formes. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Crée une nouvelle trame d'objet OLE et l'ajoute à la fin de la collection de formes. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Crée une nouvelle trame d'objet OLE et l'ajoute à la fin de la collection de formes. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Crée une nouvelle trame d'image contenant l'image spécifiée et l'ajoute à la fin de la collection de formes. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Crée une nouvelle trame Section Zoom et l'ajoute à la fin de la collection de formes. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Crée une nouvelle trame Section Zoom avec une image prédéfinie et l'ajoute à la fin de la collection de formes. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Crée un diagramme SmartArt et l'ajoute à la fin de la collection de formes. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Crée une nouvelle trame Summary Zoom et l'ajoute à la fin de la collection de formes. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Crée une nouvelle table et l'ajoute à la fin de la collection de formes. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Crée une nouvelle trame vidéo et l'ajoute à la fin de la collection de formes. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Crée une nouvelle trame vidéo et l'ajoute à la fin de la collection de formes. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Crée une nouvelle trame Zoom et l'ajoute à la fin de la collection de formes. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Crée une nouvelle trame Zoom et l'ajoute à la fin de la collection de formes. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Supprime toutes les formes de la collection de formes. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Renvoie l'index basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Crée une nouvelle trame audio liée à une piste CD et l'insère dans la collection de formes à l'index spécifié. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Crée une nouvelle trame audio et l'insère dans la collection de formes à l'index spécifié en utilisant un objet audio existant de la liste Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Crée une nouvelle trame audio avec un fichier WAV intégré et l'insère dans la collection de formes à l'index spécifié. L'audio intégré est ajouté à la collection Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Crée une nouvelle trame audio liée à un fichier audio externe et l'insère dans la collection de formes à l'index spécifié. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Crée une nouvelle forme auto et l'insère dans la collection de formes à l'index spécifié, en appliquant le formatage de modèle par défaut. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Crée une nouvelle forme auto et l'insère dans la collection de formes à l'index spécifié, en option l'initialisant avec le style de modèle par défaut. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Crée un nouveau graphique, l'initialise avec des données et paramètres d'exemple de série, et l'insère dans la collection de formes à l'index spécifié. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Crée un nouveau graphique, l'initialise avec des données et paramètres d'exemple de série, et l'insère dans la collection de formes à l'index spécifié. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié. La forme clonée conserve la position et la taille de l'original. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié. La nouvelle forme conserve la largeur et la hauteur du *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Crée une nouvelle forme de connecteur et l'insère dans la collection de formes à l'index spécifié, en appliquant le style de modèle par défaut. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Crée une nouvelle forme de connecteur et l'insère dans la collection de formes à l'index spécifié, en option appliquant le style de modèle par défaut. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Crée une nouvelle forme de groupe vide et l'insère dans la collection de formes à l'index spécifié. Le cadre du groupe s'ajustera automatiquement pour contenir les formes ajoutées. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Crée une nouvelle trame d'objet OLE et l'insère dans la collection de formes à l'index spécifié. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Crée une nouvelle trame d'objet OLE et l'insère dans la collection de formes à l'index spécifié. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Crée une nouvelle trame d'image contenant l'image spécifiée et l'insère dans la collection de formes à l'index spécifié. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Crée une nouvelle trame Section Zoom et l'insère dans la collection de formes à l'index spécifié. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Crée une nouvelle trame Section Zoom avec une image prédéfinie et l'insère dans la collection de formes à l'index spécifié. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Crée une nouvelle trame Summary Zoom et l'insère dans la collection de formes à l'index spécifié. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Crée une nouvelle table et l'insère dans la collection de formes à l'index spécifié. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Crée une nouvelle trame vidéo et l'insère dans la collection de formes à l'index spécifié. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Crée une nouvelle trame Zoom et l'insère dans la collection de formes à l'index spécifié. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Crée une nouvelle trame Zoom avec une image prédéfinie et l'insère dans la collection de formes à l'index spécifié. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Supprime la forme à l'index spécifié de la collection de formes. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Déplace les formes spécifiées dans la collection de formes, en les plaçant à partir de l'index donné. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Crée et renvoie un tableau contenant toutes les formes. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Crée et renvoie un tableau contenant toutes les formes dans la plage spécifiée. |

### Voir aussi

* classe [DomObject&lt;TParent&gt;](../domobject-1)
* classe [GroupShape](../groupshape)
* interface [IShapeCollection](../ishapecollection)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->