---
title: Shape
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une forme sur une diapositive.
type: docs
weight: 9090
url: /fr/aspose.slides/shape/
---
## Shape class

Représente une forme sur une diapositive.

```csharp
public class Shape : IShape
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Renvoie ou définit le texte alternatif associé à une forme. Lecture/écritureString . |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écritureString . |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propriété spécifie comment une forme sera rendue en mode d'affichage en noir et blanc.. Lecture/écriture[`BlackWhiteMode`](../blackwhitemode) . |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Renvoie le nombre de sites de connexion sur la forme. Lecture seuleInt32 . |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Renvoie les données personnalisées de la forme. Lecture seule[`ICustomData`](../icustomdata) . |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Renvoie l'objet EffectFormat qui contient les effets de pixel appliqués à une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule[`IEffectFormat`](../ieffectformat) . |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Renvoie l'objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme. Remarque : peut renvoyer la valeur null pour certains types de formes qui n'ont pas de propriétés de remplissage. Lecture seule[`IFillFormat`](../ifillformat) . |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Renvoie ou définit les propriétés du cadre de forme. Lecture/écriture[`IShapeFrame`](../ishapeframe) . |
| [Height](../../aspose.slides/shape/height) { get; set; } | Renvoie ou définit la hauteur de la forme. Lecture/écritureSingle . |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est masquée. Lecture/écritureBoolean . |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le clic de souris. Lecture/écriture[`IHyperlink`](../ihyperlink) . |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Renvoie le gestionnaire de liens hypertexte. Lecture seule[`IHyperlinkManager`](../ihyperlinkmanager) . |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture[`IHyperlink`](../ihyperlink) . |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seuleBoolean . |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est TextHolder_PPT. Lecture seuleBoolean . |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Renvoie l'objet LineFormat qui contient les propriétés de mise en forme des lignes pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de ligne. Lecture seule[`ILineFormat`](../ilineformat) . |
| [Name](../../aspose.slides/shape/name) { get; set; } | Renvoie ou définit le nom d'une forme. Doit être non nul. Utilisez une valeur de chaîne vide si nécessaire. Lecture/écritureString . |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtient un identifiant de forme unique dans la portée de la diapositive. Lecture seuleUInt32 . Voir aussi[`UniqueId`](./uniqueid) pour obtenir un identifiant de forme unique dans la portée de la présentation. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon renvoie null. Lecture seule[`IGroupShape`](../igroupshape) . |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Renvoie l'espace réservé pour une forme. Renvoie null si la forme n'a pas d'espace réservé. Lecture seule[`IPlaceholder`](../iplaceholder) . |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Renvoie la présentation parent d'une diapositive. Lecture seule[`IPresentation`](../ipresentation) . |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Renvoie ou définit les propriétés du cadre de forme brute. Lecture/écriture[`IShapeFrame`](../ishapeframe) . |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe z. Une valeur positive indique une rotation dans le sens des aiguilles d'une montre ; une valeur négative indique une rotation dans le sens inverse des aiguilles d'une montre. Lecture/écritureSingle . |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Renvoie les verrous de la forme. Lecture seule[`IBaseShapeLock`](../ibaseshapelock) . |
| [Slide](../../aspose.slides/shape/slide) { get; } | Renvoie la diapositive parent d'une forme. Lecture seule[`IBaseSlide`](../ibaseslide) . |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Renvoie l'objet ThreeDFormat qui applique les propriétés d'effet 3D à une forme. Remarque : peut renvoyer la valeur null pour certains types de formes qui n'ont pas de propriétés 3D. Lecture seule[`IThreeDFormat`](../ithreedformat) . |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtient un identifiant de forme unique dans la portée de la présentation. Lecture seuleUInt32 . Voir aussi[`OfficeInteropShapeId`](./officeinteropshapeid) pour obtenir un identifiant de forme unique dans la portée de la diapositive. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Renvoie ou définit la largeur de la forme. Lecture/écritureSingle . |
| [X](../../aspose.slides/shape/x) { get; set; } | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme. Lecture/écritureSingle . |
| [Y](../../aspose.slides/shape/y) { get; set; } | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme. Lecture/écritureSingle . |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Renvoie la position d'une forme dans l'ordre z. Shapes[0] renvoie la forme à l'arrière de l'ordre z, et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre z- commande. Lecture seuleInt32 . |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouvel espace réservé s'il n'y en a pas et définit les propriétés de l'espace réservé sur celles spécifiées. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail#getthumbnail)() | Renvoie la miniature de la forme. ShapeThumbnailBounds.Le type de limite de la miniature de la forme est utilisé par défaut. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail#getthumbnail_1)(ShapeThumbnailBounds, float, float) | Renvoie la vignette de la forme. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n'est pas un espace réservé. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | Enregistre le contenu de Shape en tant que fichier SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Enregistre le contenu de Shape en tant que fichier SVG. |

### Voir également

* interface [IShape](../ishape)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
