---
title: IParagraphFormat
second_title: Référence API Aspose.Sildes pour .NET
description: Cette classe contient les propriétés de mise en forme des paragraphes. Contrairement à IParagraphFormatEffectiveData./iparagraphformateffectivedata, toutes les propriétés de cette classe sont modifiables.
type: docs
weight: 6590
url: /fr/aspose.slides/iparagraphformat/
---
## IParagraphFormat interface

Cette classe contient les propriétés de mise en forme des paragraphes. Contrairement [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), toutes les propriétés de cette classe sont modifiables.

```csharp
public interface IParagraphFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Renvoie ou définit l’alignement du texte dans un paragraphe sans héritage. Lecture/écriture [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Renvoie le format de puce du paragraphe. Lecture seule [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Renvoie le format de portion par défaut d’un paragraphe. Aucun héritage appliqué. Lecture seule [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Renvoie ou définit la taille d’onglet par défaut sans héritage. Lecture/écriture Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Renvoie ou définit la profondeur du paragraphe. La valeur 0 signifie valeur indéfinie. Lecture/écriture Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Détermine si le saut de ligne est-asiatique est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Renvoie ou définit l’alignement de police dans un paragraphe sans héritage. Lecture/écriture [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Détermine si la ponctuation en suspension est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Renvoie ou définit le retrait de première ligne/retrait suspendu du paragraphe sans héritage. Le retrait suspendu peut être défini avec des valeurs négatives. Lecture/écriture Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Détermine si le saut de ligne latin est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Renvoie ou définit la marge gauche dans un paragraphe sans héritage. Lecture/écriture Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Renvoie ou définit la marge droite dans un paragraphe sans héritage. Lecture/écriture Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Détermine si l’écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Renvoie ou définit la quantité d’espace après la dernière ligne d’un paragraphe sans héritage. Une valeur positive indique le pourcentage de la taille de la police que doit occuper l’espace blanc. Une valeur négative indique la taille de l’espace blanc en points. Lecture/écriture Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Renvoie ou définit la quantité d’espace avant la première ligne d’un paragraphe sans héritage. Une valeur positive indique le pourcentage de la taille de la police que doit occuper l’espace blanc. Une valeur négative indique la taille de l’espace blanc en points. Lecture/écriture Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Renvoie ou définit la quantité d’espace entre les lignes de base d’un paragraphe. Une valeur positive indique un pourcentage, une valeur négative indique une taille en points. Aucun héritage appliqué. Lecture/écriture Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Renvoie les tabulations d’un paragraphe. Aucun héritage appliqué. Lecture seule [`ITabCollection`](../itabcollection). |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Obtient les données de mise en forme de paragraphe effectives avec l’héritage appliqué. |

### Remarques

Cette classe est utilisée pour renvoyer et manipuler les propriétés de mise en forme du paragraphe définies pour le paragraphe spécifique. Cela signifie qu’aucun héritage n’est appliqué lors de la récupération des valeurs, de sorte que dans la majorité des cas vous obtiendrez des valeurs signifiant « indéfini ».

Pour obtenir les valeurs effectives des paramètres de mise en forme, y compris celles héritées, vous devez utiliser la méthode [`GetEffective`](./geteffective) qui renvoie une instance [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Voir aussi

* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->