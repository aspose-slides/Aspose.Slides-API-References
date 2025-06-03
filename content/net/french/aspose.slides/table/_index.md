---
title: Table
second_title: Référence API Aspose.Slides pour .NET
description: Représente un tableau sur une diapositive.
type: docs
weight: 10550
url: /fr/aspose.slides/table/
---

## Classe Table

Représente un tableau sur une diapositive.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retourne ou définit le texte alternatif associé à une forme. Lecture/écriture String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retourne ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. Lecture/écriture [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Retourne la collection de colonnes. Lecture seule [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retourne le nombre de sites de connexion sur la forme. Lecture seule Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retourne les données personnalisées de la forme. Lecture seule [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retourne l'objet EffectFormat qui contient les effets de pixels appliqués à une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Retourne un objet TableFormat.FillFormat contenant le formatage de remplissage pour le tableau. Lecture seule [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Détermine si la première colonne d'un tableau doit être dessinée avec un formatage spécial. Lecture/écriture Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Détermine si la première ligne d'un tableau doit être dessinée avec un formatage spécial. Lecture/écriture Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retourne ou définit les propriétés du cadre de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Retourne les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Retourne ou définit la hauteur de la forme. Lecture/écriture Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est cachée. Lecture/écriture Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Détermine si les lignes paires doivent être dessinées avec un formatage différent. Lecture/écriture Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retourne ou définit le lien hypertexte défini pour le clic de souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retourne le gestionnaire de liens hypertexte. Lecture seule [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retourne ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtient ou définit l'option 'Marquer comme décoratif'. Lecture/écriture Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seule Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est un TextHolder_PPT. Lecture seule Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Retourne la cellule aux indices de colonne et de ligne spécifiés. Lecture seule [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Détermine si la dernière colonne d'un tableau doit être dessinée avec un formatage spécial. Lecture/écriture Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Détermine si la dernière ligne d'un tableau doit être dessinée avec un formatage spécial. Lecture/écriture Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retourne l'objet LineFormat qui contient les propriétés de formatage de ligne pour une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés de ligne. Lecture seule [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retourne ou définit le nom d'une forme. Ne doit pas être null. Utilisez une valeur de chaîne vide si nécessaire. Lecture/écriture String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtient l'identifiant unique de la forme dans le contexte de la diapositive. Lecture seule UInt32. Voir également [`UniqueId`](../shape/uniqueid) pour obtenir l'identifiant unique de la forme dans le contexte de la présentation. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retourne l'objet GroupShape parent si la forme est groupée. Sinon, retourne null. Lecture seule [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retourne le placeholder pour une forme. Retourne null si la forme n'a pas de placeholder. Lecture seule [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retourne la présentation parent d'une diapositive. Lecture seule [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retourne ou définit les propriétés du cadre brut de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Détermine si le tableau a un ordre de lecture de droite à gauche. Lecture/écriture Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retourne ou définit le nombre de degrés par lesquels la forme spécifiée est tournée autour de l'axe z. Une valeur positive indique une rotation dans le sens des aiguilles d'une montre ; une valeur négative indique une rotation dans le sens inverse des aiguilles d'une montre. Lecture/écriture Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Retourne la collection de lignes. Lecture seule [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Retourne les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 propriétés) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retourne la diapositive parent d'une forme. Lecture seule [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Obtient ou définit le style de tableau intégré. Lecture/écriture [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Retourne l'objet TableFormat qui contient les propriétés de formatage pour ce tableau. Lecture seule [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retourne l'objet ThreeDFormat qui contient les propriétés d'effet 3D pour une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés 3D. Lecture seule [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtient l'identifiant unique de la forme dans le contexte de la présentation. Lecture seule UInt32. Voir également [`OfficeInteropShapeId`](../shape/officeinteropshapeid) pour obtenir l'identifiant unique de la forme dans le contexte de la diapositive. |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Détermine si les colonnes paires doivent être dessinées avec un formatage différent. Lecture/écriture Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Retourne ou définit la largeur de la forme. Lecture/écriture Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Retourne ou définit la coordonnée x du coin supérieur gauche de la forme. Lecture/écriture Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Retourne ou définit la coordonnée y du coin supérieur gauche de la forme. Lecture/écriture Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retourne la position d'une forme dans l'ordre z. Shapes[0] retourne la forme à l'arrière de l'ordre z, et Shapes[Shapes.Count - 1] retourne la forme à l'avant de l'ordre z. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouveau placeholder s'il n'y en a pas et définit les propriétés du placeholder à un spécifié. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retourne une forme de placeholder basique (forme provenant de la mise en page et/ou de la diapositive maître dont la forme actuelle est héritée). Un null est retourné si la forme actuelle n'est pas héritée. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retourne la miniature de la forme. La forme ShapeThumbnailBounds.Shape points de type miniature est utilisée par défaut. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retourne la miniature de la forme. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Fusionne les cellules voisines. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n'est pas un placeholder. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Définit les propriétés du format de paragraphe définies à tous les paragraphes des cellules du tableau. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Définit les propriétés du format de portion définies à toutes les portions des cellules du tableau. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Définit les propriétés de format de cadre de texte définies à tous les cadres de texte des cellules du tableau. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Enregistre le contenu de la forme en tant que fichier SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Enregistre le contenu de la forme en tant que fichier SVG. |

### Voir aussi

* classe [GraphicalObject](../graphicalobject)
* interface [ITable](../itable)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)