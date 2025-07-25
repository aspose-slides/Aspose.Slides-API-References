---
title: IParagraphFormat
second_title: Référence API Aspose.Slides pour .NET
description: Cette classe contient les propriétés de formatage de paragraphe. Contrairement à IParagraphFormatEffectiveData./iparagraphformateffectivedata, toutes les propriétés de cette classe sont modifiables.
type: docs
weight: 6390
url: /fr/aspose.slides/iparagraphformat/
---

## IParagraphFormat interface

Cette classe contient les propriétés de formatage de paragraphe. Contrairement à [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), toutes les propriétés de cette classe sont modifiables.

```csharp
public interface IParagraphFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Renvoie ou définit l'alignement du texte dans un paragraphe sans héritage. Lecture/écriture [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Renvoie le format de puce du paragraphe. Lecture seule [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Renvoie le format de portion par défaut d'un paragraphe. Aucun héritage appliqué. Lecture seule [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Renvoie ou définit la taille de tabulation par défaut sans hérité. Lecture/écriture Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Renvoie ou définit la profondeur du paragraphe. La valeur 0 signifie valeur indéfinie. Lecture/écriture Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Détermine si la rupture de ligne asiatique de l'Est est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Renvoie ou définit un alignement de police dans un paragraphe sans héritage. Lecture/écriture [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Renvoie ou définit le retrait de la première ligne/redoublement d'un paragraphe sans hérité. Le retrait suspendu peut être défini avec des valeurs négatives. Lecture/écriture Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Détermine si la rupture de ligne latine est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Renvoie ou définit la marge gauche dans un paragraphe sans héritage. Lecture/écriture Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Renvoie ou définit la marge droite dans un paragraphe sans héritage. Lecture/écriture Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Renvoie ou définit la quantité d'espace après la dernière ligne d'un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de la police que devrait avoir l'espace blanc. Une valeur négative spécifie la taille de l'espace blanc en points. Lecture/écriture Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Renvoie ou définit la quantité d'espace avant la première ligne d'un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de la police que devrait avoir l'espace blanc. Une valeur négative spécifie la taille de l'espace blanc en points. Lecture/écriture Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Renvoie ou définit la quantité d'espace entre les lignes de base dans un paragraphe. Valeur positive signifie pourcentage, négative - taille en points. Aucun héritage appliqué. Lecture/écriture Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Renvoie les tabulations d'un paragraphe. Aucun héritage appliqué. Lecture seule [`ITabCollection`](../itabcollection). |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Obtient les données de formatage de paragraphe efficaces avec l'héritage appliqué. |

### Remarques

Cette classe est utilisée pour retourner et manipuler les propriétés de formatage de paragraphe définies pour le paragraphe particulier. Cela signifie qu'aucun héritage n'est appliqué lors de l'obtention des valeurs, donc dans la majorité des cas, vous obtiendrez des valeurs signifiant "indéfini".

Pour obtenir les valeurs des paramètres de formatage effectif, y compris celles héritées, vous devez utiliser la méthode [`GetEffective`](./geteffective) qui renvoie une instance de [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Voir aussi

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->