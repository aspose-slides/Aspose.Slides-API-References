---
title: IShapeCollection
second_title: Référence API Aspose.Sildes pour .NET
description: Représente une collection de formes.
type: docs
weight: 6980
url: /fr/aspose.slides/ishapecollection/
---
## IShapeCollection interface

Représente une collection de formes.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Obtient l'élément à l'index spécifié. Lecture seule [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Obtient l'objet de forme de groupe parent pour la collection de formes. Lecture seule [`IGroupShape`](../igroupshape). |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Crée un nouveau cadre audio lié à une piste CD et l'ajoute à la fin de la collection de formes. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Crée un nouveau cadre audio et l'ajoute à la fin de la collection de formes en utilisant un objet audio existant provenant de la liste Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Crée un nouveau cadre audio avec un fichier WAV intégré et l'ajoute à la fin de la collection de formes. L'audio intégré est ajouté à la collection Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Crée un nouveau cadre audio lié à un fichier audio externe et l'ajoute à la fin de la collection de formes. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Crée une nouvelle forme auto avec un formatage par défaut et l'ajoute à la fin de la collection de formes. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Crée une nouvelle forme auto et l'ajoute à la fin de la collection de formes, en l'initialisant éventuellement avec le formatage de modèle par défaut. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Crée un nouveau diagramme, l'initialise avec des données d'exemple de séries et des paramètres, et l'ajoute à la fin de la collection de formes. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Crée un nouveau diagramme, l'initialise avec des données d'exemple de séries et des paramètres, et l'ajoute à la fin de la collection de formes. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille de l'original. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de la *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Crée une nouvelle forme de connexion avec le style de modèle par défaut et l'ajoute à la fin de la collection de formes. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Crée une nouvelle forme de connexion et l'ajoute à la fin de la collection de formes, en appliquant éventuellement le style de modèle par défaut. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Crée une nouvelle forme de groupe vide et l'ajoute à la fin de la collection de formes. Le cadre du groupe s'ajustera automatiquement pour contenir toutes les formes ajoutées. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Crée une nouvelle forme de groupe, convertit l'image SVG spécifiée en formes individuelles, et ajoute le groupe résultant à la fin de la collection de formes. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Crée une nouvelle forme auto rectangle pour contenir du contenu mathématique et l'ajoute à la fin de la collection de formes. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Crée un nouveau cadre d'objet OLE et l'ajoute à la fin de la collection de formes. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Crée un nouveau cadre d'objet OLE et l'ajoute à la fin de la collection de formes. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Crée un nouveau cadre image contenant l'image spécifiée et l'ajoute à la fin de la collection de formes. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Crée un nouveau cadre de zoom de section et l'ajoute à la fin de la collection de formes. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Crée un nouveau cadre de zoom de section avec une image prédéfinie et l'ajoute à la fin de la collection de formes. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Crée un diagramme SmartArt et l'ajoute à la fin de la collection de formes. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Crée un nouveau cadre de zoom de résumé et l'ajoute à la fin de la collection de formes. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Crée un nouveau tableau et l'ajoute à la fin de la collection de formes. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Crée un nouveau cadre vidéo et l'ajoute à la fin de la collection de formes. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Crée un nouveau cadre vidéo et l'ajoute à la fin de la collection de formes. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Crée un nouveau cadre Zoom et l'ajoute à la fin de la collection de formes. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Crée un nouveau cadre Zoom et l'ajoute à la fin de la collection de formes. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Supprime toutes les formes de la collection de formes. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Renvoie l'index zéro-base de la première occurrence de la forme spécifiée dans la collection. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Crée un nouveau cadre audio lié à une piste CD et l'insère dans la collection de formes à l'index spécifié. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Crée un nouveau cadre audio et l'insère dans la collection de formes à l'index spécifié en utilisant un objet audio existant de la liste Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Crée un nouveau cadre audio avec un fichier WAV intégré et l'insère dans la collection de formes à l'index spécifié. L'audio intégré est ajouté à la collection Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Crée un nouveau cadre audio lié à un fichier audio externe et l'insère dans la collection de formes à l'index spécifié. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Crée une nouvelle forme auto et l'insère dans la collection de formes à l'index spécifié, en appliquant le formatage de modèle par défaut. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Crée une nouvelle forme auto et l'insère dans la collection de formes à l'index spécifié, en l'initialisant éventuellement avec le style de modèle par défaut. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Crée un nouveau diagramme, l'initialise avec des données d'exemple de séries et des paramètres, et l'insère dans la collection de formes à l'index spécifié. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Crée un nouveau diagramme, l'initialise avec des données d'exemple de séries et des paramètres, et l'insère dans la collection de formes à l'index spécifié. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié. La forme clonée conserve la position et la taille de l'original. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié. La nouvelle forme conserve la largeur et la hauteur de la *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Crée une nouvelle forme de connexion et l'insère dans la collection de formes à l'index spécifié, en appliquant le style de modèle par défaut. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Crée une nouvelle forme de connexion et l'insère dans la collection de formes à l'index spécifié, en appliquant éventuellement le style de modèle par défaut. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Crée une nouvelle forme de groupe vide et l'insère dans la collection de formes à l'index spécifié. Le cadre du groupe s'ajustera automatiquement pour contenir toutes les formes ajoutées. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Crée un nouveau cadre image contenant l'image spécifiée et l'insère dans la collection de formes à l'index spécifié. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Crée un nouveau cadre de zoom de section et l'insère dans la collection de formes à l'index spécifié. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Crée un nouveau cadre de zoom de section avec une image prédéfinie et l'insère dans la collection de formes à l'index spécifié. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Crée un nouveau cadre de zoom de résumé et l'insère dans la collection de formes à l'index spécifié. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Crée un nouveau tableau et l'insère dans la collection de formes à l'index spécifié. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Crée un nouveau cadre vidéo et l'insère dans la collection de formes à l'index spécifié. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Crée un nouveau cadre Zoom et l'insère dans la collection de formes à l'index spécifié. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Crée un nouveau cadre Zoom avec une image prédéfinie et l'insère dans la collection de formes à l'index spécifié. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Supprime la forme à l'index spécifié de la collection de formes. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Déplace les formes spécifiées dans la collection de formes, en les plaçant à partir de l'index indiqué. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Crée et renvoie un tableau contenant toutes les formes. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Crée et renvoie un tableau contenant toutes les formes dans la plage spécifiée. |

### Voir aussi

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [IShape](../ishape)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->