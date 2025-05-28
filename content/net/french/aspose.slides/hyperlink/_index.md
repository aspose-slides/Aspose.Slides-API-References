---
title: Hyperlink
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente un lien hypertexte.
type: docs
weight: 4670
url: /fr/aspose.slides/hyperlink/
---
## Hyperlink class

Représente un lien hypertexte.

```csharp
public class Hyperlink : PVIObject, IHyperlink
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Crée une instance d'un lien hypertexte qui pointe vers une diapositive spécifique. Remarque : le lien hypertexte créé doit être attribué à un objet de la même présentation, sinon le lien sera enregistré en tant que NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Crée une instance d'un lien hypertexte. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Crée une instance d'un lien hypertexte en utilisant un autre lien hypertexte comme source, remplaçant les propriétés secondaires. |

## Propriétés

| Nom | La description |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Renvoie un lien hypertexte qui termine le show. Lecture seule[`Hyperlink`](../hyperlink) . |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Renvoie un lien hypertexte vers la première diapositive de la présentation. Lecture seule[`Hyperlink`](../hyperlink) . |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Renvoie un lien hypertexte vers la dernière diapositive de la présentation. Lecture seule[`Hyperlink`](../hyperlink) . |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Renvoie un lien hypertexte vers la dernière diapositive visualisée. Lecture seule[`Hyperlink`](../hyperlink) . |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Renvoie un lien hypertexte spécial "play mediafile". Utilisé dans AudioFrame et VideoFrame. Lecture seule[`Hyperlink`](../hyperlink) . |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Renvoie un lien hypertexte vers la diapositive suivante. Lecture seule[`Hyperlink`](../hyperlink) . |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Renvoie un lien hypertexte spécial "ne rien faire". Lecture seule[`Hyperlink`](../hyperlink) . |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Renvoie un lien hypertexte vers la diapositive précédente. Lecture seule[`Hyperlink`](../hyperlink) . |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Renvoie le type d'action du lien hypertexte. Lecture seule[`HyperlinkActionType`](../hyperlinkactiontype) . |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface IPresentationComponent de base. Lecture seule[`IPresentationComponent`](../ipresentationcomponent) . |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Représente la source de la couleur du lien hypertexte - styles ou format de portion. Lecture/écriture[`HyperlinkColorSource`](../hyperlinkcolorsource) . |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Spécifie l'URL externe. Lecture seuleString . |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Détermine si le lien hypertexte doit être mis en surbrillance au clic. Lecture/écritureBoolean . |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Détermine si la cible de l'hyperlien parent doit être ajoutée à une liste d'hyperliens affichés lorsqu'elle est invoquée. Lecture/écritureBoolean . |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Détermine si le son doit être arrêté lors d'un clic sur un lien hypertexte. Lecture/écritureBoolean . |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Renvoie le cadre dans le jeu de cadres HTML parent pour la cible du lien hypertexte parent lorsqu'il existe. Lecture/écritureString . |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Si le lien hypertexte cible une diapositive spécifique renvoie cette diapositive. Lecture seule[`ISlide`](../islide) . |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Renvoie la chaîne qui peut être affichée dans une interface utilisateur associée au lien hypertexte parent. Lecture/écritureString . |

## Méthodes

| Nom | La description |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Détermine si les deux instances de lien hypertexte sont égales. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Détermine si les deux instances de lien hypertexte sont égales. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Sert de fonction de hachage pour un type particulier, adapté à l'utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Teste l'égalité de deux hyperliens. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Teste deux hyperliens pour l'inégalité. |

### Voir également

* class [PVIObject](../pviobject)
* interface [IHyperlink](../ihyperlink)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
