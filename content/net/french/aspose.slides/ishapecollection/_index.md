---
title: IShapeCollection
second_title: Référence API Aspose.Slides pour .NET
description: Représente une collection de formes.
type: docs
weight: 6760
url: /fr/aspose.slides/ishapecollection/
---

## Interface IShapeCollection

Représente une collection de formes.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Obtient l'élément à l'index spécifié. En lecture seule [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Retourne l'objet GroupShape parent pour une collection de formes. En lecture seule [`IGroupShape`](../igroupshape). |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Ajoute un AudioFrame avec CD à la fin de la collection. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Ajoute un nouveau cadre audio avec fichier audio intégré à la fin d'une collection. Il utilise le fichier audio de la liste Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Ajoute un nouveau cadre audio avec fichier audio intégré à la fin d'une collection. Le fichier audio intégré peut être un WAV uniquement. Il ajoute un nouvel audio à la liste Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Ajoute un nouveau cadre audio avec fichier audio lié à la fin d'une collection. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Crée une nouvelle AutoShape, la personnalise à partir du modèle par défaut et l'ajoute à la fin de la collection. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Crée une nouvelle AutoShape et l'ajoute à la fin de la collection. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Crée un nouveau graphique, l'initialise avec des données de séries d'échantillons et des paramètres, et l'ajoute à la fin de la collection. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Crée un nouveau graphique et l'ajoute à la fin de la collection. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Ajoute une copie d'une forme spécifiée à la fin de la collection. X, Y, Largeur et Hauteur de la nouvelle forme sont égaux à X, Y, Largeur et Hauteur de la *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Ajoute une copie d'une forme spécifiée à la fin de la collection. Largeur et Hauteur de la nouvelle forme sont égales à la Largeur et la Hauteur de la *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Ajoute une copie d'une forme spécifiée à la fin de la collection. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Crée un nouveau connecteur, le personnalise à partir du modèle par défaut et l'ajoute à la fin de la collection. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Crée un nouveau connecteur et l'ajoute à la fin de la collection. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Crée un nouveau GroupShape et l'ajoute à la fin de la collection. La taille et la position du cadre GroupShape seront ajustées au contenu lorsque la nouvelle forme sera ajoutée dans le GroupShape. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Crée un nouveau GroupShape, le remplit avec des formes converties à partir d'un SVG et l'ajoute à la fin de la collection. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Crée une nouvelle AutoShape de type Rectangle pour accueillir du contenu mathématique à l'intérieur et l'ajoute à la fin de la collection. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Ajoute un nouvel objet OLE à la fin d'une collection. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Ajoute un nouvel objet OLE à la fin d'une collection. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Crée un nouveau PictureFrame et l'ajoute à la fin de la collection. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Ajoute un nouvel objet Section Zoom à la fin d'une collection. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Ajoute un nouvel objet Section Zoom à la fin d'une collection avec une image prédéfinie. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Ajoute un diagramme SmartArt. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Ajoute un nouvel objet Summary Zoom à la fin d'une collection. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Crée une nouvelle Table et l'ajoute à la fin de la collection. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Ajoute un nouveau cadre vidéo à la fin d'une collection. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Ajoute un nouveau cadre vidéo à la fin d'une collection. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Ajoute un nouvel objet Zoom à la fin d'une collection. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Ajoute un nouvel objet Zoom à la fin d'une collection. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Supprime toutes les formes de la collection. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Retourne l'index de la première occurrence d'une forme dans la collection (basé sur zéro). |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Insérer un AudioFrame avec CD. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Insère un AudioFrame avec fichier audio intégré. Il utilise le fichier audio de la liste Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Insère un AudioFrame avec fichier audio intégré. Le son du fichier audio intégré peut être un WAV uniquement. Il ajoute un nouvel audio à la liste Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Crée un nouveau cadre audio avec fichier audio lié et l'insère dans une collection à l'index spécifié. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Crée une nouvelle AutoShape, la personnalise à partir du modèle par défaut et l'insère dans la collection à l'index spécifié. Remarque : le type de la forme sera déterminé par le paramètre shapeType. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Crée une nouvelle AutoShape et l'insère dans la collection à l'index spécifié. Remarque : le type de la forme sera déterminé par le paramètre shapeType. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Crée un nouveau graphique, l'initialise avec des données de séries d'échantillons et des paramètres, et l'insère à la position spécifiée dans la collection. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Crée un nouveau graphique et l'insère à la position spécifiée dans la collection. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Insère une copie d'une forme spécifiée à la position spécifiée de la collection. X, Y, Largeur et Hauteur de la nouvelle forme sont égaux à X, Y, Largeur et Hauteur de la *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Insère une copie d'une forme spécifiée à la position spécifiée de la collection. Largeur et Hauteur de la nouvelle forme sont égales à la Largeur et la Hauteur de la *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Insère une copie d'une forme spécifiée à la position spécifiée de la collection. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Crée un nouveau connecteur, le personnalise à partir du modèle par défaut et l'insère dans la collection à l'index spécifié. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Crée un nouveau connecteur et l'insère dans la collection à l'index spécifié. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Crée un nouveau GroupShape et l'insère dans la collection à l'index spécifié. La taille et la position du cadre GroupShape seront ajustées au contenu lorsque la nouvelle forme sera ajoutée dans le GroupShape. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Crée un nouvel objet OLE et l'insère dans une collection à l'index spécifié. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Crée un nouvel objet OLE et l'insère dans une collection à l'index spécifié. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Crée un nouveau PictureFrame et l'insère dans la collection à l'index spécifié. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Crée un nouvel objet Section Zoom et l'insère dans une collection à l'index spécifié. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Crée un nouvel objet Section Zoom et l'insère dans une collection à l'index spécifié. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Crée un nouvel objet Summary Zoom et l'insère dans une collection à l'index spécifié. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Crée une nouvelle Table et l'insère dans la collection à l'index spécifié. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Crée un nouveau cadre vidéo et l'insère dans une collection à l'index spécifié. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Crée un nouvel objet Zoom et l'insère dans une collection à l'index spécifié. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Crée un nouvel objet Zoom et l'insère dans une collection à l'index spécifié. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Supprime la première occurrence d'une forme spécifique de la collection. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Supprime l'élément à l'index spécifié de la collection. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Déplace une forme de la collection à la position spécifiée. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Déplace des formes de la collection à la position spécifiée. Les formes seront placées à partir de l'index dans l'ordre où elles apparaissent dans la liste. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Crée et retourne un tableau avec toutes les formes qu'il contient. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Crée et retourne un tableau avec toutes les formes de la plage spécifiée. |

### Voir Aussi

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [IShape](../ishape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->