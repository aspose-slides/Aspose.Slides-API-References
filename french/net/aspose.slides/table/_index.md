---
title: Table
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente un tableau sur une diapositive.
type: docs
weight: 10110
url: /fr/net/aspose.slides/table/
---
## Table class

Représente un tableau sur une diapositive.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Renvoie ou définit le texte alternatif associé à une forme. Lecture/écritureString . |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écritureString . |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propriété spécifie comment une forme sera rendue en mode d'affichage en noir et blanc.. Lecture/écriture[`BlackWhiteMode`](../blackwhitemode) . |
| [Columns](../../aspose.slides/table/columns) { get; } | Renvoie la collection de colonnes. Lecture seule[`IColumnCollection`](../icolumncollection) . |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Renvoie le nombre de sites de connexion sur la forme. Lecture seuleInt32 . |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Renvoie les données personnalisées de la forme. Lecture seule[`ICustomData`](../icustomdata) . |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Renvoie l'objet EffectFormat qui contient les effets de pixel appliqués à une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule[`IEffectFormat`](../ieffectformat) . |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Détermine si la première colonne d'un tableau doit être dessinée avec une mise en forme spéciale. Lecture/écritureBoolean . |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Détermine si la première ligne d'un tableau doit être dessinée avec une mise en forme spéciale. Lecture/écritureBoolean . |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Renvoie ou définit les propriétés du cadre de forme. Lecture/écriture[`IShapeFrame`](../ishapeframe) . |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Renvoie les verrous de la forme. Lecture seule[`IGraphicalObjectLock`](../igraphicalobjectlock) . |
| [Height](../../aspose.slides/shape/height) { get; set; } | Renvoie ou définit la hauteur de la forme. Lecture/écritureSingle . |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est masquée. Lecture/écritureBoolean . |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Détermine si les lignes paires doivent être dessinées avec un formatage différent. Lecture/écritureBoolean . |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le clic de souris. Lecture/écriture[`IHyperlink`](../ihyperlink) . |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Renvoie le gestionnaire de liens hypertexte. Lecture seule[`IHyperlinkManager`](../ihyperlinkmanager) . |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture[`IHyperlink`](../ihyperlink) . |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seuleBoolean . |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est TextHolder_PPT. Lecture seuleBoolean . |
| [Item](../../aspose.slides/table/item) { get; } | Renvoie la cellule aux index de colonne et de ligne spécifiés. Lecture seule[`Cell`](../cell) . |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Détermine si la dernière colonne d'un tableau doit être dessinée avec une mise en forme spéciale. Lecture/écritureBoolean . |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Détermine si la dernière ligne d'un tableau doit être dessinée avec une mise en forme spéciale. Lecture/écritureBoolean . |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Renvoie l'objet LineFormat qui contient les propriétés de mise en forme des lignes pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de ligne. Lecture seule[`ILineFormat`](../ilineformat) . |
| [Name](../../aspose.slides/shape/name) { get; set; } | Renvoie ou définit le nom d'une forme. Doit être non nul. Utilisez une valeur de chaîne vide si nécessaire. Lecture/écritureString . |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtient un identifiant de forme unique dans la portée de la diapositive. Lecture seuleUInt32 . Voir aussi[`UniqueId`](../shape/uniqueid) pour obtenir un identifiant de forme unique dans la portée de la présentation. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon renvoie null. Lecture seule[`IGroupShape`](../igroupshape) . |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Renvoie l'espace réservé pour une forme. Renvoie null si la forme n'a pas d'espace réservé. Lecture seule[`IPlaceholder`](../iplaceholder) . |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Renvoie la présentation parent d'une diapositive. Lecture seule[`IPresentation`](../ipresentation) . |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Renvoie ou définit les propriétés du cadre de forme brute. Lecture/écriture[`IShapeFrame`](../ishapeframe) . |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Détermine si la table a un ordre de lecture de droite à gauche. Lecture-écritureBoolean . |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe z. Une valeur positive indique une rotation dans le sens des aiguilles d'une montre ; une valeur négative indique une rotation dans le sens inverse des aiguilles d'une montre. Lecture/écritureSingle . |
| [Rows](../../aspose.slides/table/rows) { get; } | Renvoie la collection de lignes. Lecture seule[`IRowCollection`](../irowcollection) . |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Renvoie les verrous de la forme. Lecture seule[`IGraphicalObjectLock`](../igraphicalobjectlock) . (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Renvoie la diapositive parent d'une forme. Lecture seule[`IBaseSlide`](../ibaseslide) . |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Obtient ou définit le style de tableau intégré. Lecture/écriture[`TableStylePreset`](../tablestylepreset) . |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Renvoie l'objet TableFormat qui contient les propriétés de mise en forme de ce tableau. Lecture seule[`ITableFormat`](../itableformat) . |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Renvoie l'objet ThreeDFormat qui applique les propriétés d'effet 3D à une forme. Remarque : peut renvoyer la valeur null pour certains types de formes qui n'ont pas de propriétés 3D. Lecture seule[`IThreeDFormat`](../ithreedformat) . |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtient un identifiant de forme unique dans la portée de la présentation. Lecture seuleUInt32 . Voir aussi[`OfficeInteropShapeId`](../shape/officeinteropshapeid) pour obtenir un identifiant de forme unique dans la portée de la diapositive. |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Détermine si les colonnes paires doivent être dessinées avec un formatage différent. Lecture/écritureBoolean . |
| [Width](../../aspose.slides/shape/width) { get; set; } | Renvoie ou définit la largeur de la forme. Lecture/écritureSingle . |
| [X](../../aspose.slides/shape/x) { get; set; } | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme. Lecture/écritureSingle . |
| [Y](../../aspose.slides/shape/y) { get; set; } | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme. Lecture/écritureSingle . |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Renvoie la position d'une forme dans l'ordre z. Shapes[0] renvoie la forme à l'arrière de l'ordre z, et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre z- commande. Lecture seuleInt32 . |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouvel espace réservé s'il n'y en a pas et définit les propriétés de l'espace réservé sur celles spécifiées. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | Renvoie la miniature de la forme. ShapeThumbnailBounds.Le type de limite de la miniature de la forme est utilisé par défaut. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | Renvoie la vignette de la forme. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Fusionne les cellules voisines. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n'est pas un espace réservé. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Définit les propriétés de format de paragraphe définies pour tous les paragraphes des cellules du tableau. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Définit les propriétés de format de portion définies sur les portions de toutes les cellules du tableau. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Définit les propriétés de format de cadre de texte définies sur tous les cadres de texte des cellules du tableau. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Enregistre le contenu de Shape en tant que fichier SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Enregistre le contenu de Shape en tant que fichier SVG. |

### Voir également

* class [GraphicalObject](../graphicalobject)
* interface [ITable](../itable)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
