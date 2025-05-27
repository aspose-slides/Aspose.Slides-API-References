---
title: Hyperlien
second_title: Référence API Aspose.Slides pour .NET
description: Représente un hyperlien.
type: docs
weight: 4920
url: /fr/aspose.slides/hyperlink/
---

## Classe Hyperlien

Représente un hyperlien.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Crée une instance d'un hyperlien qui pointe vers une diapositive spécifique. Remarque : l'hyperlien créé doit être attribué à un objet de la même présentation, sinon le lien sera enregistré comme NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Crée une instance d'un hyperlien. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Crée une instance d'un hyperlien en utilisant un autre hyperlien comme source, en remplaçant les propriétés secondaires. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Renvoie un hyperlien qui termine le diaporama. Lecture seule [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Renvoie un hyperlien vers la première diapositive de la présentation. Lecture seule [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Renvoie un hyperlien vers la dernière diapositive de la présentation. Lecture seule [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Renvoie un hyperlien vers la dernière diapositive visualisée. Lecture seule [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Renvoie un hyperlien spécial "lire le fichier média". Utilisé dans AudioFrame et VideoFrame. Lecture seule [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Renvoie un hyperlien vers la diapositive suivante. Lecture seule [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Renvoie un hyperlien spécial "ne rien faire". Lecture seule [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Renvoie un hyperlien vers la diapositive précédente. Lecture seule [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Renvoie le type d'action de l'hyperlien. Lecture seule [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. Lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Représente la source de couleur de l'hyperlien - soit des styles soit un format de portion. Lecture/écriture [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Spécifie l'URL externe. Chaîne en lecture seule. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Représente un hyperlien qui est défini pour cette portion sans tenir compte du contenu réel de la portion. PowerPoint se comporte spécifiquement pour les liens et leur texte correspondant dans une portion. Cela permet de créer un texte pour l'hyperlien sous la forme d'une URL valide, différente de l'adresse réelle du lien. Dans ce cas, lorsque vous visualisez le lien dans la fenêtre d'édition, il sera changé pour correspondre au texte de la portion. Cette propriété représente la valeur originale de l'hyperlien. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Détermine si l'hyperlien doit être surligné au clic. Lecture/écriture Booléen. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Détermine si le cible de l'hyperlien parent doit être ajoutée à une liste d'hyperliens visualisés lorsqu'il est invoqué. Lecture/écriture Booléen. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Représente le son joué de l'hyperlien. Lecture/écriture [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Détermine si le son doit être arrêté lors du clic sur l'hyperlien. Lecture/écriture Booléen. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Renvoie la fenêtre dans le cadre HTML parent pour la cible de l'hyperlien parent lorsqu'il existe. Lecture/écriture Chaîne. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Si l'hyperlien cible une diapositive spécifique, renvoie cette diapositive. Lecture seule [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Renvoie la chaîne qui peut être affichée dans une interface utilisateur comme associée à l'hyperlien parent. Lecture/écriture Chaîne. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Détermine si les deux instances d'hyperlien sont égales. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Détermine si les deux instances d'hyperlien sont égales. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Sert de fonction de hachage pour un type particulier, adapté à l'utilisation dans des algorithmes de hachage et des structures de données comme une table de hachage. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Teste l'égalité de deux hyperliens. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Teste l'inégalité de deux hyperliens. |

### Voir Aussi

* classe [PVIObject](../pviobject)
* interface [IHyperlink](../ihyperlink)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->