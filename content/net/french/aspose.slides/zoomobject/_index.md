---
title: ZoomObject
second_title: Référence API Aspose.Sildes pour .NET
description: Représente un objet Zoom dans une diapositive.
type: docs
weight: 11870
url: /fr/aspose.slides/zoomobject/
---
## ZoomObject classe

Représente un objet Zoom dans une diapositive.

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Renvoie ou définit le texte alternatif associé à une forme. Lecture/écriture String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propriété spécifie comment une forme sera rendue en mode d’affichage noir et blanc.. Lecture/écriture [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Renvoie le nombre de points de connexion sur la forme. Lecture seule Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Renvoie les données personnalisées de la forme. Lecture seule [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Renvoie l’objet EffectFormat qui contient les effets pixélisés appliqués à une forme. Remarque : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés d’effet. Lecture seule [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Renvoie l’objet FillFormat qui contient les propriétés de format de remplissage pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés de remplissage. Lecture seule [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Renvoie ou définit les propriétés du cadre de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Obtient ou définit la hauteur de la forme, mesurée en points. Lecture/écriture Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est masquée. Lecture/écriture Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le clic de la souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Renvoie le gestionnaire de lien hypertexte. Lecture seule [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Obtient ou définit le type d’image d’un objet Zoom. Lecture/écriture [`ZoomImageType`](../zoomimagetype). Valeur par défaut : Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtient ou définit l’option 'Mark as decorative'. Lecture/écriture Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seule Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est TextHolder_PPT. Lecture seule Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Renvoie l’objet LineFormat qui contient les propriétés de format de ligne pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés de ligne. Lecture seule [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Renvoie ou définit le nom d’une forme. Doit être non nul. Utiliser une chaîne vide si nécessaire. Lecture/écriture String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Renvoie un identifiant unique à l’échelle de la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code interop de référencer la forme de manière fiable depuis n’importe quel endroit du document. Lecture seule UInt32. Voir aussi [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Renvoie l’objet GroupShape parent si la forme est groupée. Sinon, renvoie null. Lecture seule [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Renvoie l’espace réservé d’une forme. Renvoie null si la forme n’a pas d’espace réservé. Lecture seule [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Renvoie la présentation parente d’une diapositive. Lecture seule [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Renvoie ou définit les propriétés brutes du cadre de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Obtient ou définit le comportement de navigation dans le diaporama. Lecture/écriture Boolean. Valeur par défaut : false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l’axe z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation anti-horaire. Lecture/écriture Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 propriétés) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Obtient ou définit la valeur qui indique si le Zoom utilisera l’arrière-plan de la diapositive de destination. Lecture/écriture Boolean. Valeur par défaut : true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Renvoie la diapositive parente d’une forme. Lecture seule [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Renvoie l’objet ThreeDFormat qui contient les propriétés d’effet 3D pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés 3D. Lecture seule [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Obtient ou définit la durée de la transition entre le Zoom et la diapositive. Lecture/écriture Single. Valeur par défaut : 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Renvoie un identifiant interne à l’échelle de la présentation destiné à être utilisé par des modules complémentaires ou d’autres code. Comme cette valeur peut être réaffectée par l’utilisateur ou programme, elle ne doit pas être considérée comme une clé unique persistante. Lecture seule UInt32. Voir aussi [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Obtient ou définit la largeur de la forme, mesurée en points. Lecture/écriture Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Obtient ou définit l’image pour l’objet Zoom. Lecture/écriture [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Renvoie la position d’une forme dans l’ordre z. Shapes[0] renvoie la forme à l’arrière de l’ordre z, et Shapes[Shapes.Count - 1] renvoie la forme à l’avant de l’ordre z. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouvel espace réservé s’il n’en existe pas et définit les propriétés de l’espace réservé sur une spécifiée. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Renvoie une forme espace réservé de base (forme provenant de la disposition et/ou de la diapositive maître dont la forme actuelle est héritée). Retourne null si la forme actuelle n’est pas héritée. |
| [GetImage](../../aspose.slides/shape/getimage)() | Renvoie la miniature de la forme. Le type ShapeThumbnailBounds.Shape de limites de miniature de forme est utilisé par défaut. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Renvoie la miniature de la forme. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n’est pas un espace réservé. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Enregistre le contenu de la forme en tant que fichier SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Enregistre le contenu de la forme en tant que fichier SVG. |

### Voir aussi

* classe [GraphicalObject](../graphicalobject)
* interface [IZoomObject](../izoomobject)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->