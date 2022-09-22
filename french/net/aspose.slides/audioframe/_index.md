---
title: AudioFrame
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente un clip audio sur une diapositive.
type: docs
weight: 770
url: /fr/net/aspose.slides/audioframe/
---
## AudioFrame class

Représente un clip audio sur une diapositive.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Renvoie une collection de valeurs d'ajustement de forme. Lecture seule[`IAdjustValueCollection`](../iadjustvaluecollection) . |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Renvoie ou définit le texte alternatif associé à une forme. Lecture/écritureString . |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écritureString . |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Renvoie ou définit un dernier index de piste Lecture/écritureInt32 . |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Renvoie ou définit un temps de dernière piste. Lecture/écritureInt32 . |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Renvoie ou définit un index de début de piste. Lecture/écritureInt32 . |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Renvoie ou définit une heure de début de piste. Lecture/écritureInt32 . |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propriété spécifie comment une forme sera rendue en mode d'affichage en noir et blanc.. Lecture/écriture[`BlackWhiteMode`](../blackwhitemode) . |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Renvoie le nombre de sites de connexion sur la forme. Lecture seuleInt32 . |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Renvoie les données personnalisées de la forme. Lecture seule[`ICustomData`](../icustomdata) . |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Renvoie l'objet EffectFormat qui contient les effets de pixel appliqués à une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule[`IEffectFormat`](../ieffectformat) . |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Détermine si un son est intégré à une présentation. Lecture seuleBoolean . |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Renvoie ou définit l'objet audio intégré. Lecture/écriture[`IAudio`](../iaudio) . |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Renvoie l'objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme. Remarque : peut renvoyer la valeur null pour certains types de formes qui n'ont pas de propriétés de remplissage. Lecture seule[`IFillFormat`](../ifillformat) . |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Renvoie ou définit les propriétés du cadre de forme. Lecture/écriture[`IShapeFrame`](../ishapeframe) . |
| [Height](../../aspose.slides/shape/height) { get; set; } | Renvoie ou définit la hauteur de la forme. Lecture/écritureSingle . |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est masquée. Lecture/écritureBoolean . |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Détermine si une AudioFrame est masquée. Lecture/écritureBoolean . |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le clic de souris. Lecture/écriture[`IHyperlink`](../ihyperlink) . |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Renvoie le gestionnaire de liens hypertexte. Lecture seule[`IHyperlinkManager`](../ihyperlinkmanager) . |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture[`IHyperlink`](../ihyperlink) . |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seuleBoolean . |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est TextHolder_PPT. Lecture seuleBoolean . |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Renvoie l'objet LineFormat qui contient les propriétés de mise en forme des lignes pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de ligne. Lecture seule[`ILineFormat`](../ilineformat) . |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Renvoie ou définit le nom d'un fichier audio qui est lié à un AudioFrame. Lecture/écritureString . |
| [Name](../../aspose.slides/shape/name) { get; set; } | Renvoie ou définit le nom d'une forme. Doit être non nul. Utilisez une valeur de chaîne vide si nécessaire. Lecture/écritureString . |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtient un identifiant de forme unique dans la portée de la diapositive. Lecture seuleUInt32 . Voir aussi[`UniqueId`](../shape/uniqueid) pour obtenir un identifiant de forme unique dans la portée de la présentation. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon renvoie null. Lecture seule[`IGroupShape`](../igroupshape) . |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Renvoie l'objet PictureFillFormat pour un cadre d'image. Lecture seule[`IPictureFillFormat`](../ipicturefillformat) . |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Renvoie les verrous de la forme. Lecture seule[`IPictureFrameLock`](../ipictureframelock) . |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Renvoie l'espace réservé pour une forme. Renvoie null si la forme n'a pas d'espace réservé. Lecture seule[`IPlaceholder`](../iplaceholder) . |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Détermine si l'audio est lu sur les diapositives. Lecture/écritureBoolean . |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Détermine si un audio est mis en boucle. Lecture/écritureBoolean . |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Renvoie ou définit le mode de lecture audio. Lecture/écriture[`AudioPlayModePreset`](../audioplaymodepreset) . |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Renvoie la présentation parent d'une diapositive. Lecture seule[`IPresentation`](../ipresentation) . |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Renvoie ou définit les propriétés du cadre de forme brute. Lecture/écriture[`IShapeFrame`](../ishapeframe) . |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Renvoie ou définit l'échelle de hauteur (par rapport à la taille de l'image d'origine) du cadre de l'image. La valeur 1.0 correspond à 100%. Lecture/écritureSingle . |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Renvoie ou définit l'échelle de largeur (par rapport à la taille de l'image d'origine) du cadre de l'image. La valeur 1.0 correspond à 100%. Lecture/écritureSingle . |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Détermine si l'audio est automatiquement rembobiné pour démarrer après la lecture. Lecture/écritureBoolean . |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe z. Une valeur positive indique une rotation dans le sens des aiguilles d'une montre ; une valeur négative indique une rotation dans le sens inverse des aiguilles d'une montre. Lecture/écritureSingle . |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Renvoie les verrous de la forme. Lecture seule[`IPictureFrameLock`](../ipictureframelock) . (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Renvoie l'objet style de la forme. Lecture seule[`IShapeStyle`](../ishapestyle) . |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Renvoie ou définit le type de forme automatique pour un PictureFrame. Tous les éléments de l'ensemble sont autorisés[`ShapeType`](../shapetype), sauf toutes sortes de lignes : |
| [Slide](../../aspose.slides/shape/slide) { get; } | Renvoie la diapositive parent d'une forme. Lecture seule[`IBaseSlide`](../ibaseslide) . |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Renvoie l'objet ThreeDFormat qui applique les propriétés d'effet 3D à une forme. Remarque : peut renvoyer la valeur null pour certains types de formes qui n'ont pas de propriétés 3D. Lecture seule[`IThreeDFormat`](../ithreedformat) . |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtient un identifiant de forme unique dans la portée de la présentation. Lecture seuleUInt32 . Voir aussi[`OfficeInteropShapeId`](../shape/officeinteropshapeid) pour obtenir un identifiant de forme unique dans la portée de la diapositive. |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Renvoie ou définit le volume audio. Lecture/écriture[`AudioVolumeMode`](../audiovolumemode) . |
| [Width](../../aspose.slides/shape/width) { get; set; } | Renvoie ou définit la largeur de la forme. Lecture/écritureSingle . |
| [X](../../aspose.slides/shape/x) { get; set; } | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme. Lecture/écritureSingle . |
| [Y](../../aspose.slides/shape/y) { get; set; } | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme. Lecture/écritureSingle . |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Renvoie la position d'une forme dans l'ordre z. Shapes[0] renvoie la forme à l'arrière de l'ordre z, et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre z- commande. Lecture seuleInt32 . |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouvel espace réservé s'il n'y en a pas et définit les propriétés de l'espace réservé sur celles spécifiées. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Crée et renvoie un tableau d'éléments de forme. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Renvoie la copie du chemin de la forme géométrique. Les coordonnées sont relatives au coin supérieur gauche de la forme. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | Renvoie la miniature de la forme. ShapeThumbnailBounds.Le type de limite de la miniature de la forme est utilisé par défaut. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | Renvoie la vignette de la forme. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n'est pas un espace réservé. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Met à jour la géométrie de la forme à partir de[`IGeometryPath`](../igeometrypath) objet. Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Modifie le type de la forme ([`ShapeType`](../geometryshape/shapetype) ) àCustom . |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Met à jour la géométrie de la forme à partir du tableau de[`IGeometryPath`](../igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Modifie le type de la forme ([`ShapeType`](../geometryshape/shapetype) ) àCustom . |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Enregistre le contenu de Shape en tant que fichier SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Enregistre le contenu de Shape en tant que fichier SVG. |

### Voir également

* class [PictureFrame](../pictureframe)
* interface [IAudioFrame](../iaudioframe)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
