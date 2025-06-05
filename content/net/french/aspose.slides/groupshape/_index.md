---
title: GroupShape
second_title: Aspose.Slides pour la référence API .NET
description: Représente un groupe de formes sur une diapositive.
type: docs
weight: 4890
url: /fr/aspose.slides/groupshape/
---

## Classe GroupShape

Représente un groupe de formes sur une diapositive.

```csharp
public class GroupShape : Shape, IGroupShape
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retourne ou définit le texte alternatif associé à une forme. Lecture/écriture String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retourne ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String. |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | Permet d'obtenir l'interface de base IShape. Lecture seule [`IShape`](../ishape). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Propriété spécifiant comment une forme sera rendue en mode d'affichage en noir et blanc. Lecture/écriture [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retourne le nombre de sites de connexion sur la forme. Lecture seule Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retourne les données personnalisées de la forme. Lecture seule [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retourne l'objet EffectFormat qui contient les effets de pixel appliqués à une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retourne l'objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés de remplissage. Lecture seule [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retourne ou définit les propriétés du cadre de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | Retourne les verrouillages de la forme. Lecture seule [`IGroupShapeLock`](../igroupshapelock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Retourne ou définit la hauteur de la forme. Lecture/écriture Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est masquée. Lecture/écriture Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retourne ou définit l'hyperlien défini pour le clic de la souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retourne le gestionnaire d'hyperliens. Lecture seule [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retourne ou définit l'hyperlien défini pour le survol de la souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtient ou définit l'option 'Marquer comme décoratif' Lecture/écriture Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seule Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est TextHolder_PPT. Lecture seule Boolean. |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | Retourne l'objet LineFormat qui contient les propriétés de formatage de ligne pour une forme. Remarque : Retourne null pour les objets GroupShape car ils n'ont pas de propriétés de ligne. Lecture seule [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retourne ou définit le nom d'une forme. Ne doit pas être nul. Utilisez une valeur de chaîne vide si nécessaire. Lecture/écriture String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtient l'identifiant unique de la forme dans la portée de la diapositive. Lecture seule UInt32. Voir aussi [`UniqueId`](../shape/uniqueid) pour obtenir l'identifiant unique de la forme dans la portée de la présentation. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retourne l'objet GroupShape parent si la forme est groupée. Sinon, retourne null. Lecture seule [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retourne le substitut pour une forme. Retourne null si la forme n'a pas de substitut. Lecture seule [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retourne la présentation parente d'une diapositive. Lecture seule [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retourne ou définit les propriétés du cadre brut de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retourne ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe z. Une valeur positive indique une rotation dans le sens des aiguilles d'une montre ; une valeur négative indique une rotation dans le sens inverse. Lecture/écriture Single. |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | Retourne les verrouillages de la forme. Lecture seule [`IGroupShapeLock`](../igroupshapelock). (2 propriétés) |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | Retourne la collection de formes à l'intérieur du groupe. Lecture seule [`IShapeCollection`](../ishapecollection). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retourne la diapositive parente d'une forme. Lecture seule [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retourne l'objet ThreeDFormat qui contient les propriétés d'effet 3d pour une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés 3d. Lecture seule [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtient l'identifiant unique de la forme dans la portée de la présentation. Lecture seule UInt32. Voir aussi [`OfficeInteropShapeId`](../shape/officeinteropshapeid) pour obtenir l'identifiant unique de la forme dans la portée de la diapositive. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Retourne ou définit la largeur de la forme. Lecture/écriture Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Retourne ou définit la coordonnée x du coin supérieur gauche de la forme. Lecture/écriture Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Retourne ou définit la coordonnée y du coin supérieur gauche de la forme. Lecture/écriture Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retourne la position d'une forme dans l'ordre z. Shapes[0] retourne la forme à l'arrière de l'ordre z, et Shapes[Shapes.Count - 1] retourne la forme à l'avant de l'ordre z. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouveau substitut s'il n'y en a pas et définit les propriétés du substitut sur un spécifié. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retourne une forme substitut de base (forme du modèle et/ou de la diapositive maître dont la forme actuelle est héritée). Null est retourné si la forme actuelle n'est pas héritée. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retourne la miniature de la forme. ShapeThumbnailBounds.Shape type des limites de la miniature de forme est utilisé par défaut. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retourne la miniature de la forme. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n'est pas un substitut. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Enregistre le contenu de la forme en tant que fichier SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Enregistre le contenu de la forme en tant que fichier SVG. |

### Voir aussi

* classe [Shape](../shape)
* interface [IGroupShape](../igroupshape)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->