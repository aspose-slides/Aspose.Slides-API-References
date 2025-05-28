---
title: IParagraphFormat
second_title: Référence de l'API Aspose.Slides pour .NET
description: Cette classe contient les propriétés de formatage des paragraphes. Contrairement àIParagraphFormatEffectiveData./iparagraphformateffectivedata  toutes les propriétés de cette classe sont accessibles en écriture.
type: docs
weight: 6060
url: /fr/aspose.slides/iparagraphformat/
---
## IParagraphFormat interface

Cette classe contient les propriétés de formatage des paragraphes. Contrairement à[`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) , toutes les propriétés de cette classe sont accessibles en écriture.

```csharp
public interface IParagraphFormat
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Renvoie ou définit l'alignement du texte dans un paragraphe sans héritage. Lecture/écriture[`TextAlignment`](../textalignment) . |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Renvoie le format de puce du paragraphe. Lecture seule[`IBulletFormat`](../ibulletformat) . |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Renvoie le format de portion par défaut d'un paragraphe. Aucun héritage appliqué. Lecture seule[`IPortionFormat`](../iportionformat) . |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Renvoie ou définit la taille de tabulation par défaut sans héritage. Lecture/écritureSingle . |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Renvoie ou définit la profondeur du paragraphe. La valeur 0 signifie une valeur indéfinie. Lecture/écritureInt16 . |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Détermine si le saut de ligne est-asiatique est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Renvoie ou définit un alignement de police dans un paragraphe sans héritage. Lecture/écriture[`FontAlignment`](../fontalignment) . |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Détermine si la ponctuation hors justification est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Renvoie ou définit le paragraphe Retrait de première ligne/Retrait négatif sans héritage. Le retrait suspendu peut être défini avec des valeurs négatives. Lecture/écritureSingle . |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Détermine si le saut de ligne latin est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Renvoie ou définit la marge de gauche dans un paragraphe sans héritage. Lecture/écritureSingle . |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Renvoie ou définit la marge de droite dans un paragraphe sans héritage. Lecture/écritureSingle . |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Renvoie ou définit la quantité d'espace après la dernière ligne d'un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de la police que l'espace blanc doit avoir. Une valeur négative spécifie la taille de l'espace blanc au point size. Lecture/écritureSingle . |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Renvoie ou définit la quantité d'espace avant la première ligne d'un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de la police que l'espace blanc doit avoir. Une valeur négative spécifie la taille de l'espace blanc au point size. Lecture/écritureSingle . |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Renvoie ou définit la quantité d'espace entre les lignes de base dans un paragraphe. Une valeur positive signifie un pourcentage, une valeur négative - une taille en points. Aucun héritage appliqué. Lecture/écritureSingle . |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Renvoie les tabulations d'un paragraphe. Aucun héritage appliqué. Lecture seule[`ITabCollection`](../itabcollection) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Obtient les données de mise en forme de paragraphe effectives avec l'héritage appliqué. |

### Remarques

Cette classe est utilisée pour renvoyer et manipuler les propriétés de formatage de paragraphe définies pour le paragraphe particulier. Cela signifie que aucun héritage n'est appliqué lors de l'obtention de valeurs, donc dans la majorité des cas, vous obtiendrez des valeurs signifiant "indéfini".

Afin d'obtenir les valeurs de paramètre de formatage efficaces, y compris héritées, vous devez utiliser[`GetEffective`](./geteffective) méthode qui renvoie un[`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) exemple.

### Voir également

* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
