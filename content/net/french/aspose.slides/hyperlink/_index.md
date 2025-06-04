---
title: Hyperlink
second_title: Aspose.Slides pour la référence API .NET
description: Représente un lien hypertexte.
type: docs
weight: 4920
url: /fr/aspose.slides/hyperlink/
---

## Classe Hyperlink

Représente un lien hypertexte.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Crée une instance d'un lien hypertexte qui pointe vers une diapositive spécifique. Remarque : le lien hypertexte créé doit être attribué à un objet de la même présentation, sinon le lien sera enregistré comme NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Crée une instance d'un lien hypertexte. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Crée une instance d'un lien hypertexte en utilisant un autre lien hypertexte comme source, en remplaçant les propriétés secondaires. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Renvoie un lien hypertexte qui met fin à la présentation. Lecture seule [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Renvoie un lien hypertexte vers la première diapositive de la présentation. Lecture seule [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Renvoie un lien hypertexte vers la dernière diapositive de la présentation. Lecture seule [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Renvoie un lien hypertexte vers la dernière diapositive consultée. Lecture seule [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Renvoie un lien hypertexte spécial "lire le fichier média". Utilisé dans AudioFrame et VideoFrame. Lecture seule [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Renvoie un lien hypertexte vers la diapositive suivante. Lecture seule [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Renvoie un lien hypertexte spécial "ne rien faire". Lecture seule [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Renvoie un lien hypertexte vers la diapositive précédente. Lecture seule [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Renvoie le type d'action du lien hypertexte. Lecture seule [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. Lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Représente la source de la couleur du lien hypertexte - soit des styles soit le format de la portion. Lecture/écriture [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Spécifie l'URL externe. Chaîne en lecture seule. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Représente un lien hypertexte qui est défini pour cette portion sans tenir compte du contenu réel de la portion. PowerPoint se comporte spécifiquement pour les liens et leur texte correspondant dans une portion. Il permet de créer du texte pour le lien hypertexte sous la forme d'une URL valide, différente de l'adresse réelle du lien. Dans ce cas, lorsque vous visualisez le lien dans la fenêtre d'édition, il sera modifié pour correspondre à la portion de texte. Cette propriété représente la valeur originale du lien hypertexte. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Détermine si le lien hypertexte doit être mis en surbrillance au clic. Lecture/écriture Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Détermine si la cible du lien hypertexte parent doit être ajoutée à une liste de liens hypertextes consultés lorsqu'elle est invoquée. Lecture/écriture Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Représente le son joué par le lien hypertexte. Lecture/écriture [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Détermine si le son doit être arrêté au clic sur le lien hypertexte. Lecture/écriture Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Renvoie la frame au sein de l'ensemble de frames HTML parent pour la cible du lien hypertexte parent lorsqu'elle existe. Lecture/écriture String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Si le lien hypertexte cible une diapositive spécifique, renvoie cette diapositive. Lecture seule [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Renvoie la chaîne qui peut être affichée dans une interface utilisateur comme étant associée au lien hypertexte parent. Lecture/écriture String. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Détermine si les deux instances de lien hypertexte sont égales. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Détermine si les deux instances de lien hypertexte sont égales. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Sert de fonction de hachage pour un type particulier, adapté à l'utilisation dans des algorithmes de hachage et des structures de données comme une table de hachage. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Teste l'égalité de deux liens hypertextes. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Teste l'inégalité de deux liens hypertextes. |

### Voir Aussi

* classe [PVIObject](../pviobject)
* interface [IHyperlink](../ihyperlink)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->