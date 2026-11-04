---
title: IParagraphFormat
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Cette classe contient les propriétés de mise en forme de paragraphe. Contrairement à IParagraphFormatEffectiveData./iparagraphformateffectivedata, toutes les propriétés de cette classe sont modifiables.
type: docs
weight: 6610
url: /fr/aspose.slides/iparagraphformat/
---
## IParagraphFormat interface

Cette classe contient les propriétés de mise en forme de paragraphe. Contrairement à [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), toutes les propriétés de cette classe sont modifiables.

```csharp
public interface IParagraphFormat
```

## Propriétés

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Retourne ou définit l’alignement du texte dans un paragraphe sans héritage. Lecture/écriture [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Retourne le format de puce du paragraphe. Lecture seule [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Retourne le format de portion par défaut d’un paragraphe. Aucun héritage appliqué. Lecture seule [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Retourne ou définit la taille de tabulation par défaut sans héritage. Lecture/écriture Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Retourne ou définit la profondeur du paragraphe. La valeur 0 indique une valeur non définie. Lecture/écriture Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Détermine si le retour à la ligne asiatique de l’Est est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Retourne ou définit l’alignement de police dans un paragraphe sans héritage. Lecture/écriture [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Retourne ou définit le retrait de la première ligne / retrait pendu du paragraphe sans héritage. Le retrait pendu peut être défini avec des valeurs négatives. Lecture/écriture Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Détermine si le retour à la ligne latin est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Retourne ou définit la marge gauche dans un paragraphe sans héritage. Lecture/écriture Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Retourne ou définit la marge droite dans un paragraphe sans héritage. Lecture/écriture Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Détermine si l’écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Retourne ou définit l’espace après la dernière ligne d’un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de police que l’espace blanc doit occuper. Une valeur négative spécifie la taille de l’espace blanc en points. Lecture/écriture Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Retourne ou définit l’espace avant la première ligne d’un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de police que l’espace blanc doit occuper. Une valeur négative spécifie la taille de l’espace blanc en points. Lecture/écriture Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Retourne ou définit l’espace entre les lignes de base d’un paragraphe. Une valeur positive indique un pourcentage, négative – taille en points. Aucun héritage appliqué. Lecture/écriture Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Retourne les tabulations d’un paragraphe. Aucun héritage appliqué. Lecture seule [`ITabCollection`](../itabcollection). |

## Méthodes

| Name | Description |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Obtient les données de mise en forme de paragraphe effectives avec l’héritage appliqué. |

### Remarques

Cette classe est utilisée pour renvoyer et manipuler les propriétés de mise en forme de paragraphe définies pour le paragraphe particulier. Cela signifie qu’aucun héritage n’est appliqué lors de la récupération des valeurs, si bien que dans la plupart des cas vous obtiendrez des valeurs signifiant « non définies ».

Pour obtenir les valeurs de paramètres de mise en forme effectives incluant l’héritage, vous devez utiliser la méthode [`GetEffective`](./geteffective) qui renvoie une instance [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Voir aussi

* espace de noms [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->