---
title: Hyperlink
second_title: Aspose.Sildes pour la référence de l'API .NET
description: Représente un hyperlien.
type: docs
weight: 5120
url: /fr/aspose.slides/hyperlink/
---
## classe Hyperlink

Représente un hyperlien.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Crée une instance d'un hyperlien qui pointe vers une diapositive spécifique. Remarque : l'hyperlien créé doit être assigné à un objet de la même présentation, sinon le lien sera enregistré comme NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Crée une instance d'un hyperlien. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Crée une instance d'un hyperlien en utilisant un autre hyperlien comme source, en remplaçant les propriétés secondaires. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Renvoie un hyperlien qui termine le diaporama. Lecture seule [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Renvoie un hyperlien vers la première diapositive de la présentation. Lecture seule [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Renvoie un hyperlien vers la dernière diapositive de la présentation. Lecture seule [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Renvoie un hyperlien vers la dernière diapositive visualisée. Lecture seule [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Renvoie un hyperlien spécial « play mediafile ». Utilisé dans AudioFrame et VideoFrame. Lecture seule [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Renvoie un hyperlien vers la diapositive suivante. Lecture seule [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Renvoie un hyperlien spécial « do nothing ». Lecture seule [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Renvoie un hyperlien vers la diapositive précédente. Lecture seule [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Renvoie le type d'action de Hyperlink. Lecture seule [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. Lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Représente la source de la couleur du hyperlien – soit les styles, soit le format de la portion. Lecture/écriture [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Spécifie l'URL externe. Lecture seule String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Représente un hyperlien qui est défini pour cette portion sans tenir compte du contenu réel de la portion. PowerPoint se comporte spécifiquement pour les liens et le texte correspondant dans une portion. Il permet de créer le texte du hyperlien sous la forme d'une URL valide, différente de l'adresse réelle du lien. Dans ce cas, lorsque vous visualisez le lien dans la fenêtre d'édition, il sera modifié pour correspondre à la portion de texte. Cette propriété représente la valeur originale du hyperlien. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Détermine si le hyperlien doit être mis en évidence lors du clic. Lecture/écriture Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Détermine si la cible du hyperlien parent doit être ajoutée à une liste de hyperliens visualisés lorsqu'elle est invoquée. Lecture/écriture Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Représente le son joué par le hyperlien. Lecture/écriture [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Détermine si le son doit être arrêté lors du clic sur le hyperlien. Lecture/écriture Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Renvoie le cadre dans le frameset HTML parent pour la cible du hyperlien parent lorsqu'il existe. Lecture/écriture String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Si le Hyperlink cible une diapositive spécifique, renvoie cette diapositive. Lecture seule [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Renvoie la chaîne qui peut être affichée dans une interface utilisateur comme associée au hyperlien parent. Lecture/écriture String. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Détermine si les deux instances de Hyperlink sont égales. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Détermine si les deux instances de Hyperlink sont égales. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Fonctionne comme fonction de hachage pour un type particulier, adaptée à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Teste deux hyperliens pour l'égalité. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Teste deux hyperliens pour l'inégalité. |

### Voir aussi

* classe [PVIObject](../pviobject)
* interface [IHyperlink](../ihyperlink)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->