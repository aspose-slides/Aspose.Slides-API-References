---
title: ShapeCollection
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Représente une collection de formes.
type: docs
weight: 9860
url: /fr/aspose.slides/shapecollection/
---
## classe ShapeCollection

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
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Crée un nouveau cadre audio lié à une piste CD et l'ajoute à la fin de la collection de formes. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Crée un nouveau cadre audio et l'ajoute à la fin de la collection de formes en utilisant un objet audio existant de la liste Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Crée un nouveau cadre audio avec un fichier WAV intégré et l'ajoute à la fin de la collection de formes. L'audio intégré est ajouté à la collection Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Crée un nouveau cadre audio lié à un fichier audio externe et l'ajoute à la fin de la collection de formes. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Crée une nouvelle forme auto avec le formatage par défaut et l'ajoute à la fin de la collection de formes. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Crée une nouvelle forme auto et l'ajoute à la fin de la collection de formes, en initialisant éventuellement avec le formatage de modèle par défaut. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Crée un nouveau graphique, l'initialise avec des données d'exemple et des paramètres, puis l'ajoute à la fin de la collection de formes. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Crée un nouveau graphique, l'initialise avec des données d'exemple et des paramètres, puis l'ajoute à la fin de la collection de formes. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme dupliquée conserve la position et la taille de l'originale. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de la *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Crée une nouvelle forme de connexion avec le style de modèle par défaut et l'ajoute à la fin de la collection de formes. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Crée une nouvelle forme de connexion et l'ajoute à la fin de la collection de formes, en appliquant éventuellement le style de modèle par défaut. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Crée un nouveau groupe de formes vide et l'ajoute à la fin de la collection de formes. Le cadre du groupe s'ajuste automatiquement pour contenir toutes les formes qui y sont ajoutées. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Crée un nouveau groupe de formes, convertit l'image SVG spécifiée en formes individuelles et ajoute le groupe résultant à la fin de la collection de formes. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Crée une nouvelle forme auto rectangle pour héberger du contenu mathématique et l'ajoute à la fin de la collection de formes. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Crée un nouveau cadre d'objet OLE et l'ajoute à la fin de la collection de formes. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Crée un nouveau cadre d'objet OLE et l'ajoute à la fin de la collection de formes. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Crée un nouveau cadre image contenant l'image spécifiée et l'ajoute à la fin de la collection de formes. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Crée un nouveau cadre Section Zoom et l'ajoute à la fin de la collection de formes. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Crée un nouveau cadre Section Zoom avec une image prédéfinie et l'ajoute à la fin de la collection de formes. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Crée un diagramme SmartArt et l'ajoute à la fin de la collection de formes. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Crée un nouveau cadre Summary Zoom et l'ajoute à la fin de la collection de formes. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Crée une nouvelle table et l'ajoute à la fin de la collection de formes. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Crée un nouveau cadre vidéo et l'ajoute à la fin de la collection de formes. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Crée un nouveau cadre vidéo et l'ajoute à la fin de la collection de formes. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Crée un nouveau cadre Zoom et l'ajoute à la fin de la collection de formes. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Crée un nouveau cadre Zoom et l'ajoute à la fin de la collection de formes. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Supprime toutes les formes de la collection de formes. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Renvoie l'index basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Crée un nouveau cadre audio lié à une piste CD et l'insère dans la collection de formes à l'index spécifié. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Crée un nouveau cadre audio et l'insère dans la collection de formes à l'index spécifié en utilisant un objet audio existant de la liste Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Crée un nouveau cadre audio avec un fichier WAV intégré et l'insère dans la collection de formes à l'index spécifié. L'audio intégré est ajouté à la collection Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Crée un nouveau cadre audio lié à un fichier audio externe et l'insère dans la collection de formes à l'index spécifié. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Crée une nouvelle forme auto et l'insère dans la collection de formes à l'index spécifié, en appliquant le formatage de modèle par défaut. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Crée une nouvelle forme auto et l'insère dans la collection de formes à l'index spécifié, en initialisant éventuellement avec le style de modèle par défaut. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Crée un nouveau graphique, l'initialise avec des données d'exemple et des paramètres, puis l'insère dans la collection de formes à l'index spécifié. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Crée un nouveau graphique, l'initialise avec des données d'exemple et des paramètres, puis l'insère dans la collection de formes à l'index spécifié. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié. La forme dupliquée conserve la position et la taille de l'originale. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié. La nouvelle forme conserve la largeur et la hauteur de la *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Crée une nouvelle forme de connexion et l'insère dans la collection de formes à l'index spécifié, en appliquant le style de modèle par défaut. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Crée une nouvelle forme de connexion et l'insère dans la collection de formes à l'index spécifié, en appliquant éventuellement le style de modèle par défaut. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Crée un nouveau groupe de formes vide et l'insère dans la collection de formes à l'index spécifié. Le cadre du groupe s'ajuste automatiquement pour contenir toutes les formes qui y sont ajoutées. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Crée un nouveau cadre image contenant l'image spécifiée et l'insère dans la collection de formes à l'index spécifié. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Crée un nouveau cadre Section Zoom et l'insère dans la collection de formes à l'index spécifié. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Crée un nouveau cadre Section Zoom avec une image prédéfinie et l'insère dans la collection de formes à l'index spécifié. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Crée un nouveau cadre Summary Zoom et l'insère dans la collection de formes à l'index spécifié. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Crée une nouvelle table et l'insère dans la collection de formes à l'index spécifié. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Crée un nouveau cadre vidéo et l'insère dans la collection de formes à l'index spécifié. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Crée un nouveau cadre Zoom et l'insère dans la collection de formes à l'index spécifié. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Crée un nouveau cadre Zoom avec une image prédéfinie et l'insère dans la collection de formes à l'index spécifié. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Supprime la forme à l'index spécifié de la collection de formes. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Déplace les formes spécifiées dans la collection de formes, en les plaçant à partir de l'index indiqué. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Crée et renvoie un tableau contenant toutes les formes. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Crée et renvoie un tableau contenant toutes les formes dans la plage spécifiée. |

### Voir aussi

* classe [DomObject&lt;TParent&gt;](../domobject-1)
* classe [GroupShape](../groupshape)
* interface [IShapeCollection](../ishapecollection)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->