---
title: ParagraphFormat
second_title: Référence de l'API Aspose.Slides pour .NET
description: Cette classe contient les propriétés de formatage des paragraphes. Contrairement àIParagraphFormatEffectiveData./iparagraphformateffectivedata  toutes les propriétés de cette classe sont accessibles en écriture.
type: docs
weight: 8610
url: /fr/net/aspose.slides/paragraphformat/
---
## ParagraphFormat class

Cette classe contient les propriétés de formatage des paragraphes. Contrairement à[`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) , toutes les propriétés de cette classe sont accessibles en écriture.

```csharp
public class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Initialise une nouvelle instance de[`ParagraphFormat`](../paragraphformat) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Renvoie ou définit l'alignement du texte dans un paragraphe sans héritage. Lecture/écriture[`TextAlignment`](../textalignment) . |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface IPresentationComponent de base. Lecture seule[`IPresentationComponent`](../ipresentationcomponent) . |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Renvoie ou définit la taille de tabulation par défaut sans héritage. Lecture/écritureSingle . |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Détermine si le saut de ligne est-asiatique est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Renvoie ou définit un alignement de police dans un paragraphe sans héritage. Lecture/écriture[`FontAlignment`](../fontalignment) . |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Détermine si la ponctuation hors justification est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Renvoie ou définit le paragraphe Retrait de première ligne/Retrait négatif sans héritage. Le retrait suspendu peut être défini avec des valeurs négatives. Lecture/écritureSingle . |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Détermine si le saut de ligne latin est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Renvoie ou définit la marge de gauche dans un paragraphe sans héritage. Lecture/écritureSingle . |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Renvoie ou définit la marge de droite dans un paragraphe sans héritage. Lecture/écritureSingle . |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Renvoie ou définit la quantité d'espace après la dernière ligne d'un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de la police que l'espace blanc doit avoir. Une valeur négative spécifie la taille de l'espace blanc au point size. Lecture/écritureSingle . |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Renvoie ou définit la quantité d'espace avant la première ligne d'un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de la police que l'espace blanc doit avoir. Une valeur négative spécifie la taille de l'espace blanc au point size. Lecture/écritureSingle . |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Renvoie ou définit la quantité d'espace entre les lignes de base dans un paragraphe. Une valeur positive signifie un pourcentage, une valeur négative - une taille en points. Aucun héritage appliqué. Lecture/écritureSingle . |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Renvoie les tabulations d'un paragraphe. Aucun héritage appliqué. Lecture seule[`ITabCollection`](../itabcollection) . |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Obtient les données de mise en forme de paragraphe effectives avec l'héritage appliqué. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Renvoie le code de hachage. |

### Remarques

Cette classe est utilisée pour renvoyer et manipuler les propriétés de formatage de paragraphe définies pour le paragraphe particulier. Cela signifie que aucun héritage n'est appliqué lors de l'obtention de valeurs, donc dans la majorité des cas, vous obtiendrez des valeurs signifiant "indéfini".

Afin d'obtenir les valeurs de paramètre de formatage efficaces, y compris héritées, vous devez utiliser[`GetEffective`](./geteffective) méthode qui renvoie un[`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) exemple.

### Voir également

* class [PVIObject](../pviobject)
* interface [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interface [IParagraphFormat](../iparagraphformat)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
