---
title: Group
second_title: Aspose.Sildes pour la référence API .NET
description: Place cet élément dans un groupe en utilisant une accolade courbe inférieure
type: docs
weight: 70
url: /fr/aspose.slides.mathtext/imathelement/group/
---

## Group() {#group}

Place cet élément dans un groupe en utilisant une accolade courbe inférieure.

```csharp
public IMathGroupingCharacter Group()
```

### Valeur de retour

Nouvelle instance de type [`IMathGroupingCharacter`](../../imathgroupingcharacter)

### Exemples

Exemple :

```csharp
[C#]
IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").Group();
```

### Voir aussi

* interface [IMathGroupingCharacter](../../imathgroupingcharacter)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Group(char, MathTopBotPositions, MathTopBotPositions) {#group_1}

Place cet élément dans un groupe en utilisant un caractère de groupement tel qu'une accolade courbe inférieure ou un autre.

```csharp
public IMathGroupingCharacter Group(char character, MathTopBotPositions position, 
    MathTopBotPositions verticalJustification)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| character | Char | Caractère de groupement tel que l'ACCOLADE COURBE INFÉRIEURE (U+23DF) ou tout autre |
| position | MathTopBotPositions | Position du caractère de groupement |
| verticalJustification | MathTopBotPositions | Justification verticale du caractère de groupe. Spécifie l'alignement de l'objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupe est au-dessus de l'objet, VerticalJustification de Top signifie que le haut de l'objet tombe sur la ligne de base ; lorsque VerticalJustification est défini sur Bottom, le bas de l'objet est sur la ligne de base |

### Valeur de retour

Nouvelle instance de type [`IMathGroupingCharacter`](../../imathgroupingcharacter)

### Exemples

Exemple :

```csharp
[C#]
IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").Group('\u23E1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
```

### Voir aussi

* interface [IMathGroupingCharacter](../../imathgroupingcharacter)
* enum [MathTopBotPositions](../../mathtopbotpositions)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->