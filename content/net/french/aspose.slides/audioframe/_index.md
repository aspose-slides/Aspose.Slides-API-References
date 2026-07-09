---
title: AudioFrame
second_title: Référence API Aspose.Sildes pour .NET
description: Représente un clip audio sur une diapositive.
type: docs
weight: 870
url: /fr/aspose.slides/audioframe/
---
## AudioFrame classe

Représente un clip audio sur une diapositive.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Renvoie une collection des valeurs d'ajustement de la forme. Lecture seule [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Renvoie ou définit le texte alternatif associé à une forme. Lecture/écriture String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Renvoie ou définit l'indice de la dernière piste. Lecture/écriture Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Renvoie ou définit le temps de la dernière piste. Lecture/écriture Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Renvoie ou définit l'indice de la piste de départ. Lecture/écriture Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Renvoie ou définit le temps de la piste de départ. Lecture/écriture Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. Lecture/écriture [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | Obtient la collection des sous-titres fermés associés à la trame audio. Cette propriété est lecture seule et renvoie un [`ICaptionsCollection`](../icaptionscollection) contenant toutes les pistes de sous-titres. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Renvoie le nombre de points de connexion sur la forme. Lecture seule Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Renvoie les données personnalisées de la forme. Lecture seule [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Renvoie l'objet EffectFormat qui contient les effets de pixel appliqués à une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Détermine si un son est intégré à une présentation. Lecture seule Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Renvoie ou définit l'objet audio intégré. Lecture/écriture [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Spécifie la durée en millisecondes du fondu d'entrée initial du média. Lecture/écriture Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Spécifie la durée en millisecondes du fondu de sortie final du média. Lecture/écriture Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Renvoie l'objet FillFormat qui contient les propriétés de format de remplissage d'une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de remplissage. Lecture seule [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Renvoie ou définit les propriétés du cadre de forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Obtient ou définit la hauteur de la forme, mesurée en points. Lecture/écriture Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est masquée. Lecture/écriture Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Détermine si un AudioFrame est masqué. Lecture/écriture Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le clic de souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Renvoie le gestionnaire de liens hypertexte. Lecture seule [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Détermine si le PictureFrame est un objet Cameo ou non. Lecture seule Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtient ou définit l'option 'Marquer comme décoratif'. Lecture/écriture Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seule Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est TextHolder_PPT. Lecture seule Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Renvoie l'objet LineFormat qui contient les propriétés de format de ligne d'une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de ligne. Lecture seule [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Renvoie ou définit le nom d'un fichier audio lié à un AudioFrame. Lecture/écriture String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Renvoie ou définit le nom d'une forme. Doit être non nul. Utilisez une chaîne vide si nécessaire. Lecture/écriture String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Renvoie un identifiant unique valable pour la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code d'interopérabilité de référencer de façon fiable la forme depuis n'importe où dans le document. Lecture seule UInt32. Voir aussi [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon renvoie null. Lecture seule [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Renvoie l'objet PictureFillFormat d'un cadre image. Lecture seule [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Renvoie l'espace réservé d'une forme. Renvoie null si la forme n'a pas d'espace réservé. Lecture seule [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Détermine si l'audio est lu à travers les diapositives. Lecture/écriture Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Détermine si un audio est en boucle. Lecture/écriture Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Renvoie ou définit le mode de lecture audio. Lecture/écriture [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Renvoie la présentation parente d'une diapositive. Lecture seule [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Renvoie ou définit les propriétés brutes du cadre de forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Renvoie ou définit l'échelle de la hauteur (relative à la taille originale de l'image) du cadre image. La valeur 1.0 correspond à 100 %. Lecture/écriture Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Renvoie ou définit l'échelle de la largeur (relative à la taille originale de l'image) du cadre image. La valeur 1.0 correspond à 100 %. Lecture/écriture Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Détermine si l'audio revient automatiquement au début après la lecture. Lecture/écriture Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation anti-horaire. Lecture/écriture Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IPictureFrameLock`](../ipictureframelock). (2 propriétés) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Renvoie l'objet style de la forme. Lecture seule [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Renvoie ou définit le type AutoShape d'un PictureFrame. Tous les éléments autorisés de l'ensemble [`ShapeType`](../shapetype) sont acceptés, à l'exception de toutes les sortes de lignes : |
| [Slide](../../aspose.slides/shape/slide) { get; } | Renvoie la diapositive parente d'une forme. Lecture seule [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Renvoie l'objet ThreeDFormat qui contient les propriétés d'effet 3D d'une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés 3D. Lecture seule [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Spécifie la durée à retirer de la fin du média pendant la lecture, en millisecondes. Lecture/écriture Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Spécifie la durée à retirer du début du média pendant la lecture, en millisecondes. Lecture/écriture Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Renvoie un identifiant interne valable pour la présentation destiné à être utilisé par des modules complémentaires ou autre code. Comme cette valeur peut être réassignée par l'utilisateur ou programmée, elle ne doit pas être considérée comme une clé unique persistante. Lecture seule UInt32. Voir aussi [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Renvoie ou définit le volume audio. Lecture/écriture [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Renvoie ou définit le volume audio en pourcentages. Lecture/écriture Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Obtient ou définit la largeur de la forme, mesurée en points. Lecture/écriture Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Renvoie la position d'une forme dans l'ordre Z. Shapes[0] renvoie la forme à l'arrière de l'ordre Z, et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre Z. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouveau espace réservé s'il n'existe pas et définit les propriétés de l'espace réservé à celui spécifié. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Crée et renvoie un tableau des éléments de la forme. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Renvoie une forme espace réservé de base (forme provenant de la disposition et/ou de la diapositive maîtresse dont la forme actuelle hérite). Retourne null si la forme actuelle n'hérite pas. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Renvoie la copie du tracé de la forme géométrique. Les coordonnées sont relatives au coin supérieur gauche de la forme. |
| [GetImage](../../aspose.slides/shape/getimage)() | Renvoie la miniature de la forme. Le type ShapeThumbnailBounds.Shape des limites de la miniature est utilisé par défaut. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Renvoie la miniature de la forme. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n'est pas un espace réservé. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Met à jour la géométrie de la forme à partir de l'objet [`IGeometryPath`](../igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Change le type de la forme ([`ShapeType`](../geometryshape/shapetype)) en Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Met à jour la géométrie de la forme à partir d'un tableau de [`IGeometryPath`](../igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Change le type de la forme ([`ShapeType`](../geometryshape/shapetype)) en Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Enregistre le contenu de la forme en fichier SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Enregistre le contenu de la forme en fichier SVG. |

### Exemples

Les exemples suivants montrent comment modifier les options de lecture audio.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // Obtient la forme AudioFrame
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Définit le mode de lecture sur clic
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Définit le volume sur Faible
    audioFrame.Volume = AudioVolumeMode.Low;
    // Définit l'audio pour qu'il joue sur toutes les diapositives
    audioFrame.PlayAcrossSlides = true;
    // Désactive la lecture en boucle de l'audio
    audioFrame.PlayLoopMode = false;
    // Masque l'AudioFrame pendant le diaporama
    audioFrame.HideAtShowing = true;
    // Rembobine l'audio au début après la lecture
    audioFrame.RewindAudio = true;
    // Enregistre le fichier PowerPoint sur le disque
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* classe [PictureFrame](../pictureframe)
* interface [IAudioFrame](../iaudioframe)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->