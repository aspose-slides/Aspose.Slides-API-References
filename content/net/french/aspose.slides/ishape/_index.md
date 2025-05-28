---
title: IShape
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une forme sur une diapositive.
type: docs
weight: 6400
url: /fr/aspose.slides/ishape/
---
## IShape interface

Représente une forme sur une diapositive.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Renvoie ou définit le texte alternatif associé à une forme. Lecture/écritureString . |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écritureString . |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Permet d'obtenir l'interface IHyperlinkContainer de base. Lecture seule[`IHyperlinkContainer`](../ihyperlinkcontainer) . |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Permet d'obtenir l'interface ISlideComponent de base. Lecture seule[`ISlideComponent`](../islidecomponent) . |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | La propriété spécifie comment une forme sera rendue en mode d'affichage en noir et blanc.. Lecture/écriture[`BlackWhiteMode`](../blackwhitemode) . |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Renvoie le nombre de sites de connexion sur la forme. Lecture seuleInt32 . |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Renvoie les données personnalisées de la forme. Lecture seule[`ICustomData`](../icustomdata) . |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Renvoie l'objet EffectFormat qui contient les effets de pixel appliqués à une forme. Lecture seule[`IEffectFormat`](../ieffectformat) . |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Renvoie l'objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme. En lecture seule[`IFillFormat`](../ifillformat) . |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Renvoie ou définit les propriétés du cadre de forme. Lecture/écriture[`IShapeFrame`](../ishapeframe) . |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Renvoie ou définit la hauteur de la forme. Lecture/écritureSingle . |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Détermine si la forme est masquée. Lecture/écritureBoolean . |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seuleBoolean . |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Détermine si la forme est TextHolder. Lecture seuleBoolean . |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Renvoie l'objet LineFormat qui contient les propriétés de mise en forme des lignes pour une forme. En lecture seule[`ILineFormat`](../ilineformat) . |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Renvoie ou définit le nom d'une forme. Lecture/écritureString . |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Obtient un identifiant de forme unique dans la portée de la diapositive. Lecture seuleUInt32 . Voir aussi[`UniqueId`](./uniqueid) pour obtenir un identifiant de forme unique dans la portée de la présentation. |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon renvoie null. Lecture seule[`IGroupShape`](../igroupshape) . |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Renvoie l'espace réservé pour une forme. Lecture seule[`IPlaceholder`](../iplaceholder) . |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Renvoie ou définit les propriétés du cadre de forme brute. Lecture/écriture[`IShapeFrame`](../ishapeframe) . |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe z. Une valeur positive indique une rotation dans le sens des aiguilles d'une montre ; une valeur négative indique une rotation dans le sens inverse des aiguilles d'une montre. Lecture/écritureSingle . |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Renvoie les verrous de la forme. Lecture seule[`IBaseShapeLock`](../ibaseshapelock) . |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Renvoie l'objet ThreeDFormat qui contient les propriétés de mise en forme des lignes pour une forme. En lecture seule[`IThreeDFormat`](../ithreedformat) . |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Obtient un identifiant de forme unique dans la portée de la présentation. Lecture seuleUInt32 . Voir aussi[`OfficeInteropShapeId`](./officeinteropshapeid) pour obtenir un identifiant de forme unique dans la portée de la diapositive. |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Renvoie ou définit la largeur de la forme. Lecture/écritureSingle . |
| [X](../../aspose.slides/ishape/x) { get; set; } | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme. Lecture/écritureSingle . |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme. Lecture/écritureSingle . |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Renvoie la position d'une forme dans l'ordre z. Shapes[0] renvoie la forme à l'arrière de l'ordre z, et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre z- commande. Lecture seuleInt32 . |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Ajoute un nouvel espace réservé s'il n'y en a pas et définit les propriétés de l'espace réservé sur celles spécifiées. |
| [GetThumbnail](../../aspose.slides/ishape/getthumbnail#getthumbnail)() | Renvoie la miniature de la forme. ShapeThumbnailBounds.Le type de limite de la miniature de la forme est utilisé par défaut. |
| [GetThumbnail](../../aspose.slides/ishape/getthumbnail#getthumbnail_1)(ShapeThumbnailBounds, float, float) | Renvoie la vignette de la forme. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Définit que cette forme n'est pas un espace réservé. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Enregistre le contenu de Shape en tant que fichier SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Enregistre le contenu de Shape en tant que fichier SVG. |

### Voir également

* interface [IHyperlinkContainer](../ihyperlinkcontainer)
* interface [ISlideComponent](../islidecomponent)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
