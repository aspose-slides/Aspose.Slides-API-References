---
title: IShape
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Représente une forme sur une diapositive.
type: docs
weight: 6970
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
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Renvoie ou définit le texte alternatif associé à une forme. Lecture/écriture String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Permet d'obtenir l'interface de base IHyperlinkContainer. Lecture seule [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Permet d'obtenir l'interface de base ISlideComponent. Lecture seule [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. Lecture/écriture [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Renvoie le nombre de points de connexion sur la forme. Lecture seule Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Renvoie les données personnalisées de la forme. Lecture seule [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Renvoie l'objet EffectFormat qui contient les effets de pixel appliqués à une forme. Lecture seule [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Renvoie l'objet FillFormat qui contient les propriétés de format de remplissage pour une forme. Lecture seule [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Renvoie ou définit les propriétés du cadre de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Renvoie ou définit la hauteur de la forme, mesurée en points. Lecture/écriture Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Détermine si la forme est masquée. Lecture/écriture Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Renvoie ou définit l'option 'Mark as decorative'. Lecture/écriture Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seule Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Détermine si la forme est TextHolder. Lecture seule Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Renvoie l'objet LineFormat qui contient les propriétés de format de ligne pour une forme. Lecture seule [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Renvoie ou définit le nom d'une forme. Lecture/écriture String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code d'interopérabilité de référencer la forme de manière fiable depuis n'importe où dans le document. Lecture seule UInt32. Voir aussi [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Renvoie l'objet parent GroupShape si la forme est groupée. Sinon, renvoie null. Lecture seule [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Renvoie le placeholder d'une forme. Lecture seule [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Renvoie ou définit les propriétés brutes du cadre de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe z. Une valeur positive indique une rotation dans le sens horaire ; une valeur négative indique une rotation dans le sens antihoraire. Lecture/écriture Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Renvoie l'objet ThreeDFormat qui contient les propriétés de format de ligne pour une forme. Lecture seule [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Renvoie un identifiant interne limité à la présentation destiné à être utilisé par les modules complémentaires ou autre code. Parce que cette valeur peut être réassignée par l'utilisateur ou par programme, elle ne doit pas être considérée comme une clé unique persistante. Lecture seule UInt32. Voir aussi [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Renvoie ou définit la largeur de la forme, mesurée en points. Lecture/écriture Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Renvoie la position d'une forme dans l'ordre Z. Shapes[0] renvoie la forme à l'arrière de l'ordre Z, et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre Z. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Ajoute un nouveau placeholder s'il n'en existe pas et définit les propriétés du placeholder sur celui spécifié. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Renvoie une forme placeholder de base (forme provenant de la mise en page et/ou de la diapositive maîtresse dont la forme actuelle hérite). Null est renvoyé si la forme actuelle n'hérite pas. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Renvoie la miniature de la forme. Le type ShapeThumbnailBounds.Shape est utilisé par défaut pour les limites de la miniature. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Renvoie la miniature de la forme. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Définit que cette forme n'est pas un placeholder. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Enregistre le contenu de la forme en fichier SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Enregistre le contenu de la forme en fichier SVG. |

### Voir aussi

* interface [IHyperlinkContainer](../ihyperlinkcontainer)
* interface [ISlideComponent](../islidecomponent)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->