---
title: VideoFrame
second_title: Aspose.Sildes pour la référence API .NET
description: Représente un clip vidéo sur une diapositive.
type: docs
weight: 11410
url: /fr/aspose.slides/videoframe/
---

## Classe VideoFrame

Représente un clip vidéo sur une diapositive.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Renvoie une collection des valeurs d'ajustement de la forme. Lecture seule [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Renvoie ou définit le texte alternatif associé à une forme. Lecture/écriture String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. Lecture/écriture [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Renvoie la collection de sous-titres du vidéo. Lecture seule [`ICaptionsCollection`](../icaptionscollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Renvoie le nombre de sites de connexion sur la forme. Lecture seule Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Renvoie les données personnalisées de la forme. Lecture seule [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Renvoie l'objet EffectFormat qui contient les effets de pixel appliqués à une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Renvoie ou définit l'objet vidéo intégré. Lecture/écriture [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Renvoie l'objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de remplissage. Lecture seule [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Renvoie ou définit les propriétés du cadre de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Détermine si une vidéo est affichée en mode plein écran. Lecture/écriture Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Renvoie ou définit la hauteur de la forme. Lecture/écriture Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est cachée. Lecture/écriture Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Détermine si un VideoFrame est caché. Lecture/écriture Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Renvoie ou définit l'hyperlien défini pour le clic de souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Renvoie le gestionnaire d'hyperliens. Lecture seule [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Renvoie ou définit l'hyperlien défini pour le survol de la souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Détermine si le PictureFrame est un objet Cameo ou non. Lecture seule Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtient ou définit l'option 'Marquer comme décoratif' Lecture/écriture Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seule Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est TextHolder_PPT. Lecture seule Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Renvoie l'objet LineFormat qui contient les propriétés de formatage de ligne pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de ligne. Lecture seule [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Renvoie ou définit le nom d'un fichier vidéo qui est lié à un VideoFrame. Lecture/écriture String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Renvoie ou définit le nom d'une forme. Ne doit pas être null. Utilisez une valeur de chaîne vide si nécessaire. Lecture/écriture String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtient l'identifiant de forme unique dans le contexte de la diapositive. Lecture seule UInt32. Voir également [`UniqueId`](../shape/uniqueid) pour obtenir l'identifiant de forme unique dans le contexte de la présentation. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon, renvoie null. Lecture seule [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Renvoie l'objet PictureFillFormat pour un cadre d'image. Lecture seule [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Renvoie le modèle de remplacement pour une forme. Renvoie null si la forme n'a pas de modèle de remplacement. Lecture seule [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Détermine si une vidéo est répétée. Lecture/écriture Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Renvoie ou définit le mode de lecture de la vidéo. Lecture/écriture [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Renvoie la présentation parent d'une diapositive. Lecture seule [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Renvoie ou définit les propriétés du cadre brut de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Renvoie ou définit l'échelle de la hauteur (relative à la taille d'image originale) du cadre d'image. Une valeur de 1.0 correspond à 100%. Lecture/écriture Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Renvoie ou définit l'échelle de la largeur (relative à la taille d'image originale) du cadre d'image. Une valeur de 1.0 correspond à 100%. Lecture/écriture Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Détermine si une vidéo est automatiquement rembobinée pour commencer dès que le film a fini de jouer. Lecture/écriture Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Renvoie ou définit le nombre de degrés par lesquels la forme spécifiée est tourné autour de l'axe z. Une valeur positive indique une rotation dans le sens des aiguilles d'une montre ; une valeur négative indique une rotation dans le sens inverse des aiguilles d'une montre. Lecture/écriture Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IPictureFrameLock`](../ipictureframelock). (2 propriétés) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Renvoie l'objet de style de la forme. Lecture seule [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Renvoie ou définit le type AutoShape pour un PictureFrame. Tous les éléments du jeu [`ShapeType`](../shapetype) sont autorisés, excepté tous les types de lignes : |
| [Slide](../../aspose.slides/shape/slide) { get; } | Renvoie la diapositive parent d'une forme. Lecture seule [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Renvoie l'objet ThreeDFormat qui contient les propriétés d'effet 3D pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés 3D. Lecture seule [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Couper la fin [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Couper le début [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtient l'identifiant de forme unique dans le contexte de la présentation. Lecture seule UInt32. Voir également [`OfficeInteropShapeId`](../shape/officeinteropshapeid) pour obtenir l'identifiant de forme unique dans le contexte de la diapositive. |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Renvoie ou définit le volume audio. Lecture/écriture [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Renvoie ou définit la largeur de la forme. Lecture/écriture Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme. Lecture/écriture Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme. Lecture/écriture Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Renvoie la position d'une forme dans l'ordre z. Shapes[0] renvoie la forme à l'arrière de l'ordre z, et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre z. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouveau modèle de remplacement s'il n'en existe pas et définit les propriétés du modèle de remplacement à une spécifiée. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Crée et renvoie un tableau des éléments de la forme. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Renvoie une forme de modèle de remplacement de base (forme provenant de la mise en page et/ou de la diapositive maître dont hérite la forme actuelle). Null est renvoyé si la forme actuelle n'est pas héritée. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Renvoie la copie du chemin de la forme géométrique. Les coordonnées sont relatives au coin supérieur gauche de la forme. |
| [GetImage](../../aspose.slides/shape/getimage)() | Renvoie la miniature de la forme. ShapeThumbnailBounds.Shape type est utilisé par défaut pour les bornes de miniature de forme. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Renvoie la miniature de la forme. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n'est pas un modèle de remplacement. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Met à jour la géométrie de la forme à partir de l'objet [`IGeometryPath`](../igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Change le type de la forme ([`ShapeType`](../geometryshape/shapetype)) en Personnalisé. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Met à jour la géométrie de la forme à partir d'un tableau de [`IGeometryPath`](../igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Change le type de la forme ([`ShapeType`](../geometryshape/shapetype)) en Personnalisé. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Enregistre le contenu de la forme en tant que fichier SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Enregistre le contenu de la forme en tant que fichier SVG. |

### Voir aussi

* classe [PictureFrame](../pictureframe)
* interface [IVideoFrame](../ivideoframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->