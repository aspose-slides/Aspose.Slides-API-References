---
title: ITable
second_title: Aspose.Slides pour la référence API .NET
description: Représente une table sur une diapositive.
type: docs
weight: 7010
url: /fr/aspose.slides/itable/
---

## Interface ITable

Représente une table sur une diapositive.

```csharp
public interface ITable : IBulkTextFormattable, IGraphicalObject
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIBulkTextFormattable](../../aspose.slides/itable/asibulktextformattable) { get; } | Permet d'obtenir l'interface de base IBulkTextFormattable. En lecture seule [`IBulkTextFormattable`](../ibulktextformattable). |
| [AsIGraphicalObject](../../aspose.slides/itable/asigraphicalobject) { get; } | Permet d'obtenir l'interface de base IGraphicalObject. En lecture seule [`IGraphicalObject`](../igraphicalobject). |
| [Columns](../../aspose.slides/itable/columns) { get; } | Renvoie la collection de colonnes. En lecture seule [`IColumnCollection`](../icolumncollection). |
| [FirstCol](../../aspose.slides/itable/firstcol) { get; set; } | Détermine si la première colonne d'une table doit être dessinée avec un formatage spécial. Lecture/écriture Booléen. |
| [FirstRow](../../aspose.slides/itable/firstrow) { get; set; } | Détermine si la première rangée d'une table doit être dessinée avec un formatage spécial. Lecture/écriture Booléen. |
| [HorizontalBanding](../../aspose.slides/itable/horizontalbanding) { get; set; } | Détermine si les rangées paires doivent être dessinées avec un formatage différent. Lecture/écriture Booléen. |
| [Item](../../aspose.slides/itable/item) { get; } | Renvoie la cellule aux index de colonne et de rangée spécifiés. En lecture seule [`ICell`](../icell). |
| [LastCol](../../aspose.slides/itable/lastcol) { get; set; } | Détermine si la dernière colonne d'une table doit être dessinée avec un formatage spécial. Lecture/écriture Booléen. |
| [LastRow](../../aspose.slides/itable/lastrow) { get; set; } | Détermine si la dernière rangée d'une table doit être dessinée avec un formatage spécial. Lecture/écriture Booléen. |
| [RightToLeft](../../aspose.slides/itable/righttoleft) { get; set; } | Détermine si la table a un ordre de lecture de droite à gauche. Lecture/écriture Booléen. |
| [Rows](../../aspose.slides/itable/rows) { get; } | Renvoie la collection de rangées. En lecture seule [`IRowCollection`](../irowcollection). |
| [StylePreset](../../aspose.slides/itable/stylepreset) { get; set; } | Obtient ou définit le style de table intégré. Lecture/écriture [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/itable/tableformat) { get; } | Renvoie l'objet TableFormat qui contient les propriétés de formatage pour cette table. En lecture seule [`ITableFormat`](../itableformat). |
| [VerticalBanding](../../aspose.slides/itable/verticalbanding) { get; set; } | Détermine si les colonnes paires doivent être dessinées avec un formatage différent. Lecture/écriture Booléen. |

## Méthodes

| Nom | Description |
| --- | --- |
| [MergeCells](../../aspose.slides/itable/mergecells)(ICell, ICell, bool) | Fusionne les cellules voisines. |

### Voir aussi

* interface [IBulkTextFormattable](../ibulktextformattable)
* interface [IGraphicalObject](../igraphicalobject)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->