---
title: ShapeCollection
second_title: Aspose.Slides pour .NET Référence de l'API
description: Représente une collection de formes.
type: docs
weight: 9550
url: /fr/aspose.slides/shapecollection/
---

## Classe ShapeCollection

Représente une collection de formes.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Obtient le nombre d'éléments effectivement contenus dans la collection. Lecture seule Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Retourne une valeur indiquant si l'accès à la collection est synchronisé (sécurisé pour les threads). Lecture seule Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Obtient l'élément à l'index spécifié. Lecture seule [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Retourne l'objet GroupShape parent pour une collection de formes. Lecture seule [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Retourne une racine de synchronisation. Lecture seule Object. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Ajoute un AudioFrame avec CD à la fin de la collection. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Ajoute un nouveau cadre audio avec un fichier audio intégré à la fin d'une collection. Il utilise le fichier audio de la liste Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Ajoute un nouveau cadre audio avec un fichier audio intégré à la fin d'une collection. Le fichier audio intégré peut être uniquement un WAV. Il ajoute un nouvel audio à la liste Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Ajoute un nouveau cadre audio avec un fichier audio lié à la fin d'une collection. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Crée une nouvelle AutoShape, l'ajuste depuis le modèle par défaut et l'ajoute à la fin de la collection. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Crée une nouvelle AutoShape et l'ajoute à la fin de la collection. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Crée un nouveau graphique, l'initialise avec des données de série d'exemple et des paramètres et l'ajoute à la fin de la collection. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Crée un nouveau graphique et l'ajoute à la fin de la collection. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Ajoute une copie d'une forme spécifiée à la fin de la collection. X, Y, Width et Height de la nouvelle forme sont égaux à X, Y, Width et Height de la *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Ajoute une copie d'une forme spécifiée à la fin de la collection. Width et Height de la nouvelle forme sont égaux à Width et Height de la *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Ajoute une copie d'une forme spécifiée à la fin de la collection. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Crée un nouveau connecteur, l'ajuste depuis le modèle par défaut et l'ajoute à la fin de la collection. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Crée un nouveau connecteur et l'ajoute à la fin de la collection. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Crée un nouveau GroupShape et l'ajoute à la fin de la collection. La taille et la position du cadre GroupShape seront ajustées au contenu lorsque la nouvelle forme sera ajoutée au GroupShape. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Crée un nouveau GroupShape, le remplit avec des formes converties depuis SVG et l'ajoute à la fin de la collection. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Crée une nouvelle Autoshape ajustée depuis le modèle par défaut pour un contenu mathématique et l'ajoute à la fin de la collection. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Ajoute un nouvel objet OLE à la fin d'une collection. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Ajoute un nouvel objet OLE à la fin d'une collection. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Crée un nouveau cadre d'image et l'ajoute à la fin de la collection. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Ajoute un nouvel objet Section Zoom à la fin d'une collection. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Ajoute un nouvel objet Section Zoom à la fin d'une collection avec une image prédéfinie. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Ajoute un diagramme SmartArt. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Ajoute un nouvel objet Summary Zoom à la fin d'une collection. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Crée une nouvelle Table et l'ajoute à la fin de la collection. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Ajoute un nouveau cadre vidéo à la fin d'une collection. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Ajoute un nouveau cadre vidéo à la fin d'une collection. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Ajoute un nouvel objet Zoom à la fin d'une collection. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Ajoute un nouvel objet Zoom à la fin d'une collection. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Supprime toutes les formes de la collection. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Retourne un énumérateur qui itère à travers la collection. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Retourne l'index basé sur zéro de la première occurrence d'une forme dans la collection. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Insère un AudioFrame avec CD. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Insère un AudioFrame avec un fichier audio intégré. Il utilise le fichier audio de la liste Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Insère un AudioFrame avec un fichier audio intégré. Le son du fichier audio intégré peut être uniquement un WAV. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Crée un nouveau cadre audio avec un fichier audio lié et l'insère dans une collection à l'index spécifié. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Crée une nouvelle AutoShape, l'ajuste depuis le modèle par défaut et l'insère dans la collection à l'index spécifié. Remarque : le type de la forme sera déterminé par le paramètre shapeType. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Crée une nouvelle AutoShape et l'insère dans la collection à l'index spécifié. Remarque : le type de la forme sera déterminé par le paramètre shapeType. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Crée un nouveau graphique, l'initialise avec des données de série d'exemple et des paramètres et l'insère à la position spécifiée dans la collection. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Crée un nouveau graphique et l'insère à la position spécifiée dans la collection. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Insère une copie d'une forme spécifiée à la position spécifiée de la collection. X, Y, Width et Height de la nouvelle forme sont égaux à X, Y, Width et Height de la *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Insère une copie d'une forme spécifiée à la position spécifiée de la collection. Width et Height de la nouvelle forme sont égaux à Width et Height de la *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Insère une copie d'une forme spécifiée à la position spécifiée de la collection. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Crée un nouveau connecteur, l'ajuste depuis le modèle par défaut et l'insère dans la collection à l'index spécifié. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Crée un nouveau connecteur et l'insère dans la collection à l'index spécifié. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Crée un nouveau GroupShape et l'insère dans la collection à l'index spécifié. La taille et la position du cadre GroupShape seront ajustées au contenu lorsque la nouvelle forme sera ajoutée au GroupShape. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Crée un nouvel objet OLE et l'insère dans une collection à l'index spécifié. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Crée un nouvel objet OLE et l'insère dans une collection à l'index spécifié. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Crée un nouveau cadre d'image et l'insère dans la collection à l'index spécifié. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Crée un nouvel objet Section Zoom et l'insère dans une collection à l'index spécifié. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Crée un nouvel objet Section Zoom et l'insère dans une collection à l'index spécifié. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Crée un nouvel objet Summary Zoom et l'insère dans une collection à l'index spécifié. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Crée une nouvelle Table et l'insère dans la collection à l'index spécifié. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Crée un nouveau cadre vidéo et l'insère dans une collection à l'index spécifié. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Crée un nouvel objet Zoom et l'insère dans une collection à l'index spécifié. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Crée un nouvel objet Zoom et l'insère dans une collection à l'index spécifié. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Supprime la première occurrence d'une forme spécifique de la collection. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Supprime l'élément à l'index spécifié de la collection. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Déplace une forme de la collection à la position spécifiée. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Déplace des formes de la collection à la position spécifiée. Les formes seront placées en commençant par l'index dans l'ordre où elles apparaissent dans la liste. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Crée et retourne un tableau contenant toutes les formes. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Crée et retourne un tableau contenant toutes les formes de la plage spécifiée. Un index de la première forme à retourner. Un nombre de formes à retourner. |

### Voir aussi

* classe [DomObject&lt;TParent&gt;](../domobject-1)
* classe [GroupShape](../groupshape)
* interface [IShapeCollection](../ishapecollection)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->