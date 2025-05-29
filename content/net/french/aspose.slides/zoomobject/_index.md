---
title: ZoomObject
second_title: Référence API Aspose.Slides pour .NET
description: Représente un objet Zoom dans une diapositive.
type: docs
weight: 11560
url: /fr/aspose.slides/zoomobject/
---

## Classe ZoomObject

Représente un objet Zoom dans une diapositive.

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retourne ou définit le texte alternatif associé à une forme. Lecture/écriture String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retourne ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. Lecture/écriture [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retourne le nombre de sites de connexion sur la forme. Lecture seule Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retourne les données personnalisées de la forme. Lecture seule [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retourne l'objet EffectFormat qui contient les effets de pixels appliqués à une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retourne l'objet FillFormat qui contient les propriétés de format de remplissage pour une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés de remplissage. Lecture seule [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retourne ou définit les propriétés du cadre de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Retourne les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Retourne ou définit la hauteur de la forme. Lecture/écriture Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est cachée. Lecture/écriture Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retourne ou définit l'hyperlien défini pour le clic de souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retourne le gestionnaire d'hyperliens. Lecture seule [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retourne ou définit l'hyperlien défini pour le survol de souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Obtient ou définit le type d'image d'un objet zoom. Lecture/écriture [`ZoomImageType`](../zoomimagetype). Valeur par défaut : Aperçu |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtient ou définit l'option "Marquer comme décoratif". Lecture/écriture Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seule Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est un TextHolder_PPT. Lecture seule Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retourne l'objet LineFormat qui contient les propriétés de format de ligne pour une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés de ligne. Lecture seule [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retourne ou définit le nom d'une forme. Ne doit pas être nul. Utilisez une chaîne vide si nécessaire. Lecture/écriture String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtient l'identifiant unique de la forme dans le cadre de la diapositive. Lecture seule UInt32. Voir également [`UniqueId`](../shape/uniqueid) pour obtenir l'identifiant unique de la forme dans le cadre de la présentation. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retourne l'objet GroupShape parent si la forme est groupée. Sinon, retourne null. Lecture seule [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retourne le modèle d'une forme. Retourne null si la forme n'a pas de modèle. Lecture seule [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retourne la présentation parente d'une diapositive. Lecture seule [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retourne ou définit les propriétés du cadre brut de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Obtient ou définit le comportement de navigation dans le diaporama. Lecture/écriture Boolean. Valeur par défaut : false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retourne ou définit le nombre de degrés par lesquels la forme spécifiée est tournée autour de l'axe z. Une valeur positive indique une rotation dans le sens des aiguilles d'une montre ; une valeur négative indique une rotation dans le sens inverse. Lecture/écriture Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Retourne les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 propriétés) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Obtient ou définit la valeur qui spécifie si le Zoom utilisera l'arrière-plan de la diapositive de destination. Lecture/écriture Boolean. Valeur par défaut : true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retourne la diapositive parente d'une forme. Lecture seule [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retourne l'objet ThreeDFormat qui contient les propriétés d'effet 3D pour une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés 3D. Lecture seule [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Obtient ou définit la durée de la transition entre le Zoom et la diapositive. Lecture/écriture Single. Valeur par défaut : 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtient l'identifiant unique de la forme dans le cadre de la présentation. Lecture seule UInt32. Voir également [`OfficeInteropShapeId`](../shape/officeinteropshapeid) pour obtenir l'identifiant unique de la forme dans le cadre de la diapositive. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Retourne ou définit la largeur de la forme. Lecture/écriture Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Retourne ou définit la coordonnée x du coin supérieur gauche de la forme. Lecture/écriture Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Retourne ou définit la coordonnée y du coin supérieur gauche de la forme. Lecture/écriture Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Obtient ou définit l'image pour l'objet zoom. Lecture/écriture [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retourne la position d'une forme dans l'ordre z. Shapes[0] retourne la forme à l'arrière de l'ordre z, et Shapes[Shapes.Count - 1] retourne la forme à l'avant de l'ordre z. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouveau modèle s'il n'y en a pas, et définit les propriétés du modèle à celui spécifié. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retourne une forme de modèle de base (forme du modèle et/ou de la diapositive maître dont la forme actuelle est héritée). Un null est retourné si la forme actuelle n'est pas héritée. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retourne la miniature de la forme. Le type ShapeThumbnailBounds.Shape est utilisé par défaut. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retourne la miniature de la forme. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n'est pas un modèle. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Enregistre le contenu de la forme au format SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Enregistre le contenu de la forme au format SVG. |

### Voir aussi

* classe [GraphicalObject](../graphicalobject)
* interface [IZoomObject](../izoomobject)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->