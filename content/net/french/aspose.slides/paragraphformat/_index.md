---
title: ParagraphFormat
second_title: Référence de l'API Aspose.Slides pour .NET
description: Cette classe contient les propriétés de mise en forme des paragraphes. Contrairement à IParagraphFormatEffectiveData, toutes les propriétés de cette classe sont modifiables.
type: docs
weight: 9040
url: /fr/aspose.slides/paragraphformat/
---

## Classe ParagraphFormat

Cette classe contient les propriétés de mise en forme des paragraphes. Contrairement à [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), toutes les propriétés de cette classe sont modifiables.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Initialise une nouvelle instance de la classe [`ParagraphFormat`](../paragraphformat). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Retourne ou définit l'alignement du texte dans un paragraphe sans héritage. Lecture/écriture [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. Lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Retourne ou définit la taille de tabulation par défaut sans héritage. Lecture/écriture Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Détermine si le saut de ligne est utilisé en Asie de l'Est dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Retourne ou définit un alignement de police dans un paragraphe sans héritage. Lecture/écriture [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Retourne ou définit l'indentation de la première ligne/indentation suspendue d'un paragraphe sans héritage. L'indentation suspendue peut être définie avec des valeurs négatives. Lecture/écriture Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Détermine si le saut de ligne latin est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Retourne ou définit la marge gauche d'un paragraphe sans héritage. Lecture/écriture Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Retourne ou définit la marge droite d'un paragraphe sans héritage. Lecture/écriture Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Retourne ou définit la quantité d'espace après la dernière ligne d'un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de la police que devrait avoir l'espace blanc. Une valeur négative spécifie la taille de l'espace blanc en points. Lecture/écriture Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Retourne ou définit la quantité d'espace avant la première ligne d'un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de la police que devrait avoir l'espace blanc. Une valeur négative spécifie la taille de l'espace blanc en points. Lecture/écriture Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Retourne ou définit la quantité d'espace entre les lignes de base dans un paragraphe. Une valeur positive signifie pourcentage, négative - taille en points. Aucun héritage appliqué. Lecture/écriture Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Retourne les tabulations d'un paragraphe. Aucun héritage appliqué. Lecture seule [`ITabCollection`](../itabcollection). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Obtient les données de mise en forme de paragraphe effectives avec l'héritage appliqué. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retourne le code de hachage. |

### Remarques

Cette classe est utilisée pour retourner et manipuler les propriétés de mise en forme des paragraphes définies pour un paragraphe particulier. Cela signifie qu'aucun héritage n'est appliqué lors de l'obtention des valeurs, donc pour la majorité des cas, vous obtiendrez des valeurs signifiant "indéfini".

Afin d'obtenir les valeurs des paramètres de mise en forme effectifs, y compris les hérités, vous devez utiliser la méthode [`GetEffective`](./geteffective) qui retourne une instance de [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Voir aussi

* classe [PVIObject](../pviobject)
* interface [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interface [IParagraphFormat](../iparagraphformat)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->