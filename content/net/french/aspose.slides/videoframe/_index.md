---
title: VideoFrame
second_title: Aspose.Sildes pour .NET Référence API
description: Représente un clip vidéo sur une diapositive.
type: docs
weight: 11720
url: /fr/aspose.slides/videoframe/
---
## VideoFrame classe

Représente un clip vidéo sur une diapositive.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Retourne une collection des valeurs d’ajustement de la forme. Lecture seule [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retourne ou définit le texte alternatif associé à une forme. Lecture/écriture Chaîne. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retourne ou définit le titre du texte alternatif associé à une forme. Lecture/écriture Chaîne. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. Lecture/écriture [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Obtient la collection des sous-titres fermés associés au cadre vidéo. Cette propriété est en lecture seule et retourne un [`ICaptionsCollection`](../icaptionscollection) contenant toutes les pistes de sous-titres. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retourne le nombre de sites de connexion sur la forme. Lecture seule Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retourne les données personnalisées de la forme. Lecture seule [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retourne l'objet EffectFormat qui contient les effets pixel appliqués à une forme. Remarque : peut retourner null pour certains types de formes qui n’ont pas de propriétés d’effet. Lecture seule [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Retourne ou définit l’objet vidéo intégré. Lecture/écriture [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retourne l'objet FillFormat qui contient les propriétés de format de remplissage pour une forme. Remarque : peut retourner null pour certains types de formes qui n’ont pas de propriétés de remplissage. Lecture seule [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retourne ou définit les propriétés du cadre de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Détermine si une vidéo est affichée en mode plein écran. Lecture/écriture Booléen. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Obtient ou définit la hauteur de la forme, mesurée en points. Lecture/écriture Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est masquée. Lecture/écriture Booléen. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Détermine si un VideoFrame est masqué. Lecture/écriture Booléen. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retourne ou définit le lien hypertexte défini pour le clic de souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retourne le gestionnaire de lien hypertexte. Lecture seule [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retourne ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Détermine si le PictureFrame est un objet Cameo ou non. Lecture seule Booléen. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtient ou définit l'option 'Marquer comme décoratif'. Lecture/écriture Booléen. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seule Booléen. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est TextHolder_PPT. Lecture seule Booléen. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retourne l'objet LineFormat qui contient les propriétés de format de ligne pour une forme. Remarque : peut retourner null pour certains types de formes qui n’ont pas de propriétés de ligne. Lecture seule [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Retourne ou définit le nom d’un fichier vidéo lié à un VideoFrame. Lecture/écriture Chaîne. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retourne ou définit le nom d’une forme. Doit être non nul. Utilisez une chaîne vide si nécessaire. Lecture/écriture Chaîne. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Retourne un identifiant unique limité à la diapositive qui reste constant pendant toute la durée de vie de la forme et permet à PowerPoint ou au code d’interop de référencer la forme de façon fiable depuis n’importe où dans le document. Lecture seule UInt32. Voir aussi [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retourne l'objet GroupShape parent si la forme est groupée. Sinon retourne null. Lecture seule [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Retourne l'objet PictureFillFormat pour un cadre d’image. Lecture seule [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Retourne les verrous de la forme. Lecture seule [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retourne l’espace réservé d’une forme. Retourne null si la forme n’a pas d’espace réservé. Lecture seule [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Détermine si une vidéo est en boucle. Lecture/écriture Booléen. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Retourne ou définit le mode de lecture vidéo. Lecture/écriture [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retourne la présentation parent d’une diapositive. Lecture seule [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retourne ou définit les propriétés brutes du cadre de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Retourne ou définit l’échelle de la hauteur (relative à la taille originale de l’image) du cadre d’image. La valeur 1,0 correspond à 100 %. Lecture/écriture Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Retourne ou définit l’échelle de la largeur (relative à la taille originale de l’image) du cadre d’image. La valeur 1,0 correspond à 100 %. Lecture/écriture Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Détermine si une vidéo est automatiquement rembobinée au départ dès que le film a fini de jouer. Lecture/écriture Booléen. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retourne ou définit le nombre de degrés de rotation de la forme spécifiée autour de l’axe z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation anti-horaire. Lecture/écriture Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Retourne les verrous de la forme. Lecture seule [`IPictureFrameLock`](../ipictureframelock). (2 propriétés) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Retourne l’objet style de la forme. Lecture seule [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Retourne ou définit le type AutoShape pour un PictureFrame. Tous les éléments autorisés du jeu [`ShapeType`](../shapetype) sont disponibles, à l’exception de toutes les sortes de lignes : |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retourne la diapositive parent d’une forme. Lecture seule [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retourne l'objet ThreeDFormat qui contient les propriétés d’effet 3D pour une forme. Remarque : peut retourner null pour certains types de formes qui n’ont pas de propriétés 3D. Lecture seule [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Rogner fin [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Rogner début [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Retourne un identifiant interne limité à la présentation destiné à être utilisé par des compléments ou autre code. Parce que cette valeur peut être réassignée par l’utilisateur ou programmatiquement, elle ne doit pas être traitée comme une clé unique persistante. Lecture seule UInt32. Voir aussi [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Retourne ou définit le volume audio. Lecture/écriture [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Obtient ou définit la largeur de la forme, mesurée en points. Lecture/écriture Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retourne la position d’une forme dans l’ordre z. Shapes[0] renvoie la forme à l’arrière de l’ordre z, et Shapes[Shapes.Count - 1] renvoie la forme à l’avant de l’ordre z. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouvel espace réservé s’il n’existe pas et définit les propriétés de l’espace réservé à un spécifié. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Crée et renvoie un tableau des éléments de la forme. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retourne une forme d’espace réservé basique (forme provenant de la disposition et/ou de la diapositive maîtresse dont la forme actuelle hérite). Null est retourné si la forme actuelle n’est pas héritée. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Retourne une copie du chemin de la forme géométrique. Les coordonnées sont relatives au coin supérieur gauche de la forme. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retourne la miniature de la forme. Le type ShapeThumbnailBounds.Shape des limites de la miniature de forme est utilisé par défaut. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retourne la miniature de la forme. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n’est pas un espace réservé. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Met à jour la géométrie de la forme à partir de l’objet [`IGeometryPath`](../igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Change le type de la forme ([`ShapeType`](../geometryshape/shapetype)) en Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Met à jour la géométrie de la forme à partir d’un tableau de [`IGeometryPath`](../igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Change le type de la forme ([`ShapeType`](../geometryshape/shapetype)) en Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Enregistre le contenu de la forme en tant que fichier SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Enregistre le contenu de la forme en tant que fichier SVG. |

### Voir aussi

* classe [PictureFrame](../pictureframe)
* interface [IVideoFrame](../ivideoframe)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->