---
title: IShape
second_title: Référence API Aspose.Slides pour .NET
description: Représente une forme sur une diapositive.
type: docs
weight: 6730
url: /fr/aspose.slides/ishape/
---

## Interface IShape

Représente une forme sur une diapositive.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Renvoie ou définit le texte alternatif associé à une forme. Lecture/écriture String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Permet d'obtenir l'interface de base IHyperlinkContainer. Lecture seule [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Permet d'obtenir l'interface de base ISlideComponent. Lecture seule [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | La propriété spécifie comment une forme sera rendue en mode d'affichage en noir et blanc. Lecture/écriture [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Renvoie le nombre de points de connexion sur la forme. Lecture seule Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Renvoie les données personnalisées de la forme. Lecture seule [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Renvoie l'objet EffectFormat qui contient des effets de pixels appliqués à une forme. Lecture seule [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Renvoie l'objet FillFormat qui contient des propriétés de formatage de remplissage pour une forme. Lecture seule [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Renvoie ou définit les propriétés du cadre de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Renvoie ou définit la hauteur de la forme. Lecture/écriture Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Détermine si la forme est cachée. Lecture/écriture Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Obtient ou définit l'option 'Marquer comme décoratif' Lecture/écriture Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seule Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Détermine si la forme est un TextHolder. Lecture seule Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Renvoie l'objet LineFormat qui contient des propriétés de formatage de ligne pour une forme. Lecture seule [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Renvoie ou définit le nom d'une forme. Lecture/écriture String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Obtient l'identifiant unique de la forme dans le contexte de la diapositive. Lecture seule UInt32. Voir aussi [`UniqueId`](./uniqueid) pour obtenir l'identifiant unique de la forme dans le contexte de la présentation. |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon, renvoie null. Lecture seule [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Renvoie le placeholder pour une forme. Lecture seule [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Renvoie ou définit les propriétés du cadre brut de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Renvoie ou définit le nombre de degrés auxquels la forme spécifiée est tournée autour de l'axe z. Une valeur positive indique une rotation dans le sens des aiguilles d'une montre ; une valeur négative indique une rotation dans le sens inverse des aiguilles d'une montre. Lecture/écriture Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Renvoie l'objet ThreeDFormat qui contient des propriétés de formatage de ligne pour une forme. Lecture seule [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Obtient l'identifiant unique de la forme dans le contexte de la présentation. Lecture seule UInt32. Voir aussi [`OfficeInteropShapeId`](./officeinteropshapeid) pour obtenir l'identifiant unique de la forme dans le contexte de la diapositive. |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Renvoie ou définit la largeur de la forme. Lecture/écriture Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme. Lecture/écriture Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme. Lecture/écriture Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Renvoie la position d'une forme dans l'ordre z. Shapes[0] renvoie la forme à l'arrière de l'ordre z, et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre z. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Ajoute un nouveau placeholder s'il n'existe pas et définit les propriétés du placeholder à celles spécifiées. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Renvoie une forme de placeholder de base (forme provenant de la disposition et/ou de la diapositive maître dont la forme actuelle hérite). Un null est renvoyé si la forme actuelle n'est pas héritée. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Renvoie la miniature de la forme. ShapeThumbnailBounds.Shape type de limites de miniature de forme est utilisé par défaut. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Renvoie la miniature de la forme. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Définit que cette forme n'est pas un placeholder. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Enregistre le contenu de la forme en tant que fichier SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Enregistre le contenu de la forme en tant que fichier SVG. |

### Voir aussi

* interface [IHyperlinkContainer](../ihyperlinkcontainer)
* interface [ISlideComponent](../islidecomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->