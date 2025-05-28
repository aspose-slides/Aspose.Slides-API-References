---
title: SummaryZoomSection
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente un objet Section Zoom Résumé dans un cadre de Zoom Résumé.
type: docs
weight: 10470
url: /fr/aspose.slides/summaryzoomsection/
---

## Classe SummaryZoomSection

Représente un objet Section Zoom Résumé dans un cadre de Zoom Résumé.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Renvoie ou définit le texte alternatif associé à une forme. Lecture/écriture String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. Lecture/écriture [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Renvoie le nombre de points de connexion sur la forme. Lecture seule Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Renvoie les données personnalisées de la forme. Lecture seule [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | Renvoie la description textuelle de l'objet Section Zoom Résumé. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Renvoie l'objet EffectFormat qui contient des effets pixel appliqués à une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Renvoie l'objet FillFormat qui contient des propriétés de formatage de remplissage pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de remplissage. Lecture seule [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Renvoie ou définit les propriétés du cadre de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Renvoie ou définit la hauteur de la forme. Lecture/écriture Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est cachée. Lecture/écriture Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Renvoie ou définit l'hyperlien défini pour le clic de souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Renvoie le gestionnaire d'hyperliens. Lecture seule [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Renvoie ou définit l'hyperlien défini pour le survol de la souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Obtient ou définit le type d'image d'un objet de zoom. Lecture/écriture [`ZoomImageType`](../zoomimagetype). Valeur par défaut : Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtient ou définit l'option 'Marquer comme décoratif' Lecture/écriture Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seule Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est un TextHolder_PPT. Lecture seule Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Renvoie l'objet LineFormat qui contient des propriétés de formatage de ligne pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de ligne. Lecture seule [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Renvoie ou définit le nom d'une forme. Ne doit pas être null. Utiliser une valeur de chaîne vide si nécessaire. Lecture/écriture String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtient l'identifiant unique de la forme dans le contexte de la diapositive. Lecture seule UInt32. Voir aussi [`UniqueId`](../shape/uniqueid) pour obtenir l'identifiant unique de la forme dans le contexte de la présentation. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Renvoie l'objet GroupShape parente si la forme est groupée. Sinon, renvoie null. Lecture seule [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Renvoie le placeholder pour une forme. Renvoie null si la forme n'a pas de placeholder. Lecture seule [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Renvoie la présentation parente d'une diapositive. Lecture seule [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Renvoie ou définit les propriétés du cadre brut de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Obtient ou définit le comportement de navigation dans le diaporama. Lecture/écriture Boolean. Valeur par défaut : false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire. Lecture/écriture Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 propriétés) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Obtient ou définit la valeur qui spécifie si le Zoom utilisera l'arrière-plan de la diapositive de destination. Lecture/écriture Boolean. Valeur par défaut : true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Renvoie la diapositive parente d'une forme. Lecture seule [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Obtient ou définit l'objet section auquel l'objet Section Zoom est lié. Lecture/écriture [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Renvoie l'objet ThreeDFormat qui contient les propriétés d'effet 3D pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés 3D. Lecture seule [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | Renvoie le titre textuel de l'objet Section Zoom Résumé. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Obtient ou définit la durée de la transition entre le Zoom et la diapositive. Lecture/écriture Single. Valeur par défaut : 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtient l'identifiant unique de la forme dans le contexte de la présentation. Lecture seule UInt32. Voir aussi [`OfficeInteropShapeId`](../shape/officeinteropshapeid) pour obtenir l'identifiant unique de la forme dans le contexte de la diapositive. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Renvoie ou définit la largeur de la forme. Lecture/écriture Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme. Lecture/écriture Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme. Lecture/écriture Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Obtient ou définit l'image pour l'objet de zoom. Lecture/écriture [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Renvoie la position d'une forme dans l'ordre z. Shapes[0] renvoie la forme à l'arrière de l'ordre z, et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre z. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouveau placeholder s'il n'y en a pas et définit les propriétés du placeholder à celle spécifiée. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Renvoie une forme de placeholder de base (forme provenant de la disposition et/ou de la diapositive maître dont la forme actuelle est héritée). Un null est renvoyé si la forme actuelle n'est pas héritée. |
| [GetImage](../../aspose.slides/shape/getimage)() | Renvoie la miniature de la forme. Le type de dimensions de miniature de forme `ShapeThumbnailBounds.Shape` est utilisé par défaut. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Renvoie la miniature de la forme. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n'est pas un placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Enregistre le contenu de la forme sous forme de fichier SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Enregistre le contenu de la forme sous forme de fichier SVG. |

### Voir aussi

* class [SectionZoomFrame](../sectionzoomframe)
* interface [ISummaryZoomSection](../isummaryzoomsection)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)