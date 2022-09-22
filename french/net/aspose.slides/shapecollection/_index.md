---
title: ShapeCollection
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une collection de formes.
type: docs
weight: 9110
url: /fr/net/aspose.slides/shapecollection/
---
## ShapeCollection class

Représente une collection de formes.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seuleInt32 . |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seuleBoolean . |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Obtient l'élément à l'index spécifié. Lecture seule[`IShape`](../ishape) . |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Renvoie l'objet GroupShape parent d'une collection de formes. Lecture seule[`IGroupShape`](../igroupshape) . |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Renvoie une racine de synchronisation. Lecture seuleObject . |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Ajoute un AudioFrame avec CD à la fin de la collection. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Ajoute une nouvelle image audio avec un fichier audio intégré à la fin d'une collection. Il utilise un fichier audio de la liste Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Ajoute une nouvelle image audio avec un fichier audio intégré à la fin d'une collection. Le fichier audio intégré ne peut être qu'un WAV. Il ajoute un nouvel audio dans la liste Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Ajoute une nouvelle image audio avec un fichier audio lié à la fin d'une collection. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Crée une nouvelle forme automatique, la règle à partir du modèle par défaut et l'ajoute à la fin de la collection. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Crée une nouvelle forme automatique et l'ajoute à la fin de la collection. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Crée un nouveau graphique, l'initialise avec des données et des paramètres de série d'échantillons et l'ajoute à la fin de la collection. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Crée un nouveau graphique et l'ajoute à la fin de la collection. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Ajoute une copie d'une forme spécifiée à la fin de la collection. X, Y, Largeur et Hauteur de la nouvelle forme sont égaux à X, Y, Largeur et Hauteur de la*sourceShape* . |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Ajoute une copie d'une forme spécifiée à la fin de la collection. La largeur et la hauteur de la nouvelle forme sont égales à la largeur et la hauteur de la*sourceShape* . |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Ajoute une copie d'une forme spécifiée à la fin de la collection. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Crée un nouveau connecteur, le règle à partir du modèle par défaut et l'ajoute à la fin de la collection. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Crée un nouveau connecteur et l'ajoute à la fin de la collection. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Crée un nouveau GroupShape et l'ajoute à la fin de la collection. La taille et la position du cadre du GroupShape seront adaptées au contenu lorsqu'une nouvelle forme sera ajoutée au GroupShape. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Crée un nouveau GroupShape, le remplit avec des formes converties à partir de SVG et l'ajoute à la fin de la collection. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Crée une nouvelle forme automatique adaptée du modèle par défaut au contenu mathématique et l'ajoute à la fin de la collection. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Ajoute un nouvel objet OLE à la fin d'une collection. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Ajoute un nouvel objet OLE à la fin d'une collection. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Crée un nouveau PictureFrame et l'ajoute à la fin de la collection. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Ajoute un nouvel objet Section Zoom à la fin d'une collection. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Ajoute un nouvel objet Section Zoom à la fin d'une collection avec une image prédéfinie. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Ajouter un diagramme SmartArt. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Ajoute un nouvel objet Summary Zoom à la fin d'une collection. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Crée une nouvelle table et l'ajoute à la fin de la collection. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Ajoute une nouvelle image vidéo à la fin d'une collection. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Ajoute une nouvelle image vidéo à la fin d'une collection. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Ajoute un nouvel objet Zoom à la fin d'une collection. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Ajoute un nouvel objet Zoom à la fin d'une collection. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Supprime toutes les formes de la collection. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Renvoie l'index de base zéro de la première occurrence d'une forme dans la collection. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Insérer un AudioFrame avec CD. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Insérez un AudioFrame avec un fichier audio intégré. Il utilise un fichier audio de Presentation.Audios list. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Insérez un AudioFrame avec un fichier audio intégré. Le son du fichier audio intégré ne peut être qu'un WAV. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Crée une nouvelle image audio avec un fichier audio lié et l'insère dans une collection à l'index spécifié. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Crée une nouvelle forme automatique, l'ajuste à partir du modèle par défaut et l'insère dans la collection à l'index spécifié. Remarque : le type de la forme sera déterminé par le paramètre shapeType. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Crée une nouvelle forme automatique et l'insère dans la collection à l'index spécifié. Remarque : le type de la forme sera déterminé par le paramètre shapeType. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Crée un nouveau graphique, l'initialise avec des données et des paramètres de série d'échantillons et l'insère à la position spécifiée dans la collection. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Crée un nouveau graphique et l'insère à la position spécifiée dans la collection. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Insère une copie d'une forme spécifiée à la position spécifiée de la collection. X, Y, Largeur et Hauteur de la nouvelle forme sont égales à X, Y, Largeur et Hauteur de la*sourceShape* . |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Insère une copie d'une forme spécifiée à la position spécifiée de la collection. La largeur et la hauteur de la nouvelle forme sont égales à la largeur et la hauteur de la*sourceShape* . |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Insère une copie d'une forme spécifiée à la position spécifiée de la collection. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Crée un nouveau connecteur, le règle à partir du modèle par défaut et l'insère dans la collection à l'index spécifié. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Crée un nouveau connecteur et l'insère dans la collection à l'index spécifié. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Crée un nouveau GroupShape et l'insère dans la collection à l'index spécifié. La taille et la position du cadre de GroupShape seront ajustées au contenu lorsqu'une nouvelle forme sera ajoutée au GroupShape. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Crée un nouvel objet OLE et l'insère dans une collection à l'index spécifié. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Crée un nouvel objet OLE et l'insère dans une collection à l'index spécifié. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Crée un nouveau PictureFrame et l'insère dans la collection à l'index spécifié. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Crée un nouvel objet Section Zoom et l'insère dans une collection à l'index spécifié. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Crée un nouvel objet Section Zoom et l'insère dans une collection à l'index spécifié. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Crée un nouvel objet Summary Zoom et l'insère dans une collection à l'index spécifié. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Crée une nouvelle table et l'insère dans la collection à l'index spécifié. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Crée une nouvelle image vidéo et l'insère dans une collection à l'index spécifié. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Crée un nouvel objet Zoom et l'insère dans une collection à l'index spécifié. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Crée un nouvel objet Zoom et l'insère dans une collection à l'index spécifié. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Supprime la première occurrence d'une forme spécifique de la collection. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Supprime l'élément à l'index spécifié de la collection. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Déplace une forme de la collection vers la position spécifiée. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Déplace les formes de la collection vers la position spécifiée. Les formes seront placées à partir de l'index dans l'ordre dans lequel elles apparaissent dans la liste. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Crée et renvoie un tableau contenant toutes les formes. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Crée et renvoie un tableau contenant toutes les formes de la plage spécifiée. Un index d'une première forme à retourner.Un certain nombre de formes à retourner. |

### Voir également

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [GroupShape](../groupshape)
* interface [IShapeCollection](../ishapecollection)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
