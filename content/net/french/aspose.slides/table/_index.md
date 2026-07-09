---
title: Table
second_title: Aspose.Sildes pour la référence API .NET
description: Représente une table sur une diapositive.
type: docs
weight: 10860
url: /fr/aspose.slides/table/
---
## classe Table

Représente une table sur une diapositive.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Renvoie ou définit le texte de remplacement associé à une forme. Lecture/écriture String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Renvoie ou définit le titre du texte de remplacement associé à une forme. Lecture/écriture String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Cette propriété indique comment une forme sera rendue en mode d’affichage noir et blanc. Lecture/écriture [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Renvoie la collection de colonnes. Lecture seule [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Renvoie le nombre de points de connexion de la forme. Lecture seule Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Renvoie les données personnalisées de la forme. Lecture seule [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Renvoie l’objet EffectFormat qui contient les effets de pixel appliqués à une forme. Note : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés d’effet. Lecture seule [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Renvoie un objet TableFormat.FillFormat contenant le format de remplissage pour la Table. Lecture seule [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Détermine si la première colonne d’une table doit être dessinée avec un format spécial. Lecture/écriture Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Détermine si la première ligne d’une table doit être dessinée avec un format spécial. Lecture/écriture Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Renvoie ou définit les propriétés du cadre de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Renvoie ou définit la hauteur de la forme, mesurée en points. Lecture/écriture Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est masquée. Lecture/écriture Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Détermine si les lignes paires doivent être dessinées avec un format différent. Lecture/écriture Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le clic de souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Renvoie le gestionnaire de liens hypertexte. Lecture seule [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Renvoie ou définit l’option « Marquer comme décoratif ». Lecture/écriture Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seule Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est TextHolder_PPT. Lecture seule Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Renvoie la cellule aux index de colonne et de ligne spécifiés. Lecture seule [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Détermine si la dernière colonne d’une table doit être dessinée avec un format spécial. Lecture/écriture Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Détermine si la dernière ligne d’une table doit être dessinée avec un format spécial. Lecture/écriture Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Renvoie l’objet LineFormat qui contient les propriétés de format de ligne pour une forme. Note : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés de ligne. Lecture seule [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Renvoie ou définit le nom d’une forme. Doit être non nul. Utilisez une chaîne vide si nécessaire. Lecture/écriture String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code interop de référencer la forme de façon fiable depuis n’importe où dans le document. Lecture seule UInt32. Voir aussi [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Renvoie l’objet parent GroupShape si la forme est groupée. Sinon renvoie null. Lecture seule [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Renvoie le texte de remplacement (placeholder) d’une forme. Renvoie null si la forme n’a aucun texte de remplacement. Lecture seule [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Renvoie la présentation parente d’une diapositive. Lecture seule [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Renvoie ou définit les propriétés brutes du cadre de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Détermine si la table a un sens de lecture de droite à gauche. Lecture/écriture Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l’axe z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation anti-horaire. Lecture/écriture Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Renvoie la collection de lignes. Lecture seule [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 propriétés) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Renvoie la diapositive parent d’une forme. Lecture seule [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Renvoie ou définit le style de tableau intégré. Lecture/écriture [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Renvoie l’objet TableFormat qui contient les propriétés de formatage pour ce tableau. Lecture seule [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Renvoie l’objet ThreeDFormat qui contient les propriétés d’effet 3D pour une forme. Note : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés 3D. Lecture seule [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Renvoie un identifiant interne, limité à la présentation, destiné à être utilisé par les modules complémentaires ou autre code. Comme cette valeur peut être réaffectée par l’utilisateur ou programmatiquement, elle ne doit pas être considérée comme une clé unique persistante. Lecture seule UInt32. Voir aussi [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Détermine si les colonnes paires doivent être dessinées avec un format différent. Lecture/écriture Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Renvoie ou définit la largeur de la forme, mesurée en points. Lecture/écriture Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Renvoie la position d’une forme dans l’ordre Z. Shapes[0] renvoie la forme au fond de l’ordre Z, et Shapes[Shapes.Count - 1] renvoie la forme à l’avant de l’ordre Z. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouveau texte de remplacement s’il n’en existe pas et définit les propriétés du texte de remplacement à un spécifié. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Renvoie une forme de texte de remplacement de base (forme provenant de la disposition et/ou de la diapositive maîtresse dont la forme actuelle hérite). Null est renvoyé si la forme actuelle n’hérite pas. |
| [GetImage](../../aspose.slides/shape/getimage)() | Renvoie la vignette de la forme. Le type ShapeThumbnailBounds.Shape est utilisé par défaut pour les limites de la vignette. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Renvoie la vignette de la forme. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Renvoie les limites visuelles de la forme calculées à partir de son contenu rendu. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Fusionne les cellules voisines. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n’est pas un texte de remplacement. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Applique les propriétés de format de paragraphe définies à tous les paragraphes des cellules du tableau. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Applique les propriétés de format de portion définies à toutes les portions des cellules du tableau. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Applique les propriétés de format de cadre texte définies à tous les cadres texte des cellules du tableau. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Enregistre le contenu de la forme en fichier SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Enregistre le contenu de la forme en fichier SVG. |

### Voir aussi

* classe [GraphicalObject](../graphicalobject)
* interface [ITable](../itable)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->