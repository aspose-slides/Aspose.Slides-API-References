---
title: MathematicalText
second_title: Aspose.Sildes pour la référence de l'API .NET
description: Le constructeur par défaut crée une valeur String.Empty
type: docs
weight: 10
url: /fr/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---

## MathematicalText() {#constructor}

Constructeur par défaut (crée une valeur String.Empty)

```csharp
public MathematicalText()
```

### Exemples

Exemple:

```csharp
[C#]
MathematicalText mathText = new MathematicalText();
```

### Voir aussi

* class [MathematicalText](../../mathematicaltext)
* namespace [Aspose.Slides.MathText](../../mathematicaltext)
* assembly [Aspose.Slides](../../../)

---

## MathematicalText(char) {#constructor_1}

Créer MathText avec un symbole unique

```csharp
public MathematicalText(char mathSymbol)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| mathSymbol | Char | symbole unique |

### Exemples

Exemple:

```csharp
[C#]
MathematicalText mathText = new MathematicalText('$');
```

### Voir aussi

* class [MathematicalText](../../mathematicaltext)
* namespace [Aspose.Slides.MathText](../../mathematicaltext)
* assembly [Aspose.Slides](../../../)

---

## MathematicalText(string) {#constructor_2}

Créer MathematicalText à partir d'un texte

```csharp
public MathematicalText(string mathText)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | String | valeur texte |

### Exemples

Exemple:

```csharp
[C#]
MathematicalText mathText = new MathematicalText("x+y");
```

### Voir aussi

* class [MathematicalText](../../mathematicaltext)
* namespace [Aspose.Slides.MathText](../../mathematicaltext)
* assembly [Aspose.Slides](../../../)

---

## MathematicalText(string, IPortionFormat) {#constructor_3}

Créer MathematicalText à partir d'un texte et des paramètres de format

```csharp
public MathematicalText(string mathText, IPortionFormat portionFormat)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | String | valeur texte |
| portionFormat | IPortionFormat | paramètres de format de texte |

### Exemples

Exemple:

```csharp
[C#]
IPortionFormat format = new PortionFormat() { FontHeight = 12 };
MathematicalText mathText = new MathematicalText("x+y", format);
```

### Voir aussi

* interface [IPortionFormat](../../../aspose.slides/iportionformat)
* class [MathematicalText](../../mathematicaltext)
* namespace [Aspose.Slides.MathText](../../mathematicaltext)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->