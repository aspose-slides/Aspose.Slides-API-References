---
title: IMathBlock
second_title: Référence de l'API Aspose.Slides pour .NET
description: Spécifie une instance de texte mathématique contenue dans un MathParagraph et commence sur sa propre ligne. Toutes les zones mathématiques y compris les équations les expressions les tableaux déquations ou dexpressions et les formules sont représentées par un bloc mathématique.
type: docs
weight: 7460
url: /fr/aspose.slides.mathtext/imathblock/
---
## IMathBlock interface

Spécifie une instance de texte mathématique contenue dans un MathParagraph et commence sur sa propre ligne. Toutes les zones mathématiques, y compris les équations, les expressions, les tableaux d'équations ou d'expressions et les formules sont représentées par un bloc mathématique.

```csharp
public interface IMathBlock : IMathElement, IMathElementCollection
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathblock/asimathelement) { get; } | Permet d'obtenir l'interface IMathElement de base [`IMathElement`](../imathelement) |
| [AsIMathElementCollection](../../aspose.slides.mathtext/imathblock/asimathelementcollection) { get; } | Permet d'obtenir l'interface IMathElementCollection de base [`IMathElementCollection`](../imathelementcollection) |

## Méthodes

| Nom | La description |
| --- | --- |
| [Delimit](../../aspose.slides.mathtext/imathblock/delimit)(char) | Délimite tous les éléments enfants avec un caractère séparateur (sans les crochets) |
| [Enclose](../../aspose.slides.mathtext/imathblock/enclose)(char, char, char) | Encadre les éléments enfants de ce bloc dans des caractères spécifiés tels que des parenthèses ou un autre comme framing et délimite avec un caractère séparateur |
| [JoinBlock](../../aspose.slides.mathtext/imathblock/joinblock)(IMathBlock) | Joint un autre bloc mathématique avec celui-ci |
| [WriteAsMathMl](../../aspose.slides.mathtext/imathblock/writeasmathml)(Stream) | Enregistre le contenu de ce[`IMathBlock`](../imathblock) comme MathML |

### Exemples

Exemple :

```csharp
[C#]
IMathBlock mathBlock = new MathBlock();
```

### Voir également

* interface [IMathElement](../imathelement)
* interface [IMathElementCollection](../imathelementcollection)
* espace de noms [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
