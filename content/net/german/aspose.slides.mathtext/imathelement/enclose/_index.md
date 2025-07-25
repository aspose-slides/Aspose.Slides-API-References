---
title: Enclose
second_title: Aspose.Sildes für .NET API Referenz
description: Schließt ein Mathe-Element in Klammern ein
type: docs
weight: 40
url: /de/aspose.slides.mathtext/imathelement/enclose/
---

## Enclose() {#enclose}

Schließt ein Mathe-Element in Klammern ein

```csharp
public IMathDelimiter Enclose()
```

### Rückgabewert

Das Mathe-Element vom Typ [`IMathDelimiter`](../../imathdelimiter), das die Klammern enthält

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
IMathDelimiter delimiter = element.Enclose();
```

### Siehe Auch

* Schnittstelle [IMathDelimiter](../../imathdelimiter)
* Schnittstelle [IMathElement](../../imathelement)
* Namespace [Aspose.Slides.MathText](../../imathelement)
* Assembly [Aspose.Slides](../../../)

---

## Enclose(char, char) {#enclose_1}

Schließt dieses Element in angegebenen Zeichen wie Klammern oder andere Zeichen als Rahmen ein

```csharp
public IMathDelimiter Enclose(char beginningCharacter, char endingCharacter)
```

| Parameter           | Typ  | Beschreibung        |
|---------------------|------|---------------------|
| beginningCharacter   | Char | Anfangszeichen (normalerweise linke Klammer) |
| endingCharacter      | Char | Endzeichen (normalerweise rechte Klammer) |

### Rückgabewert

Das Mathe-Element vom Typ [`IMathDelimiter`](../../imathdelimiter), das die angegebenen Zeichen als Rahmen enthält

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
IMathDelimiter delimiter = element.Enclose('[', ']');
```

### Siehe Auch

* Schnittstelle [IMathDelimiter](../../imathdelimiter)
* Schnittstelle [IMathElement](../../imathelement)
* Namespace [Aspose.Slides.MathText](../../imathelement)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->