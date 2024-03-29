---
title: Enclose
second_title: Aspose.Slides für .NET-API-Referenz
description: Schließt ein mathematisches Element in Klammern ein
type: docs
weight: 40
url: /de/aspose.slides.mathtext/imathelement/enclose/
---
## Enclose() {#enclose}

Schließt ein mathematisches Element in Klammern ein

```csharp
public IMathDelimiter Enclose()
```

### Rückgabewert

Das mathematische Element von type[`IMathDelimiter`](../../imathdelimiter) was die Klammer enthält

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
IMathDelimiter delimiter = element.Enclose();
```

### Siehe auch

* interface [IMathDelimiter](../../imathdelimiter)
* interface [IMathElement](../../imathelement)
* namensraum [Aspose.Slides.MathText](../../imathelement)
* Montage [Aspose.Slides](../../../)

---

## Enclose(char, char) {#enclose_1}

Schließt dieses Element in bestimmte Zeichen wie Klammern oder andere Zeichen wie framing ein

```csharp
public IMathDelimiter Enclose(char beginningCharacter, char endingCharacter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| beginningCharacter | Char | Anfangszeichen (normalerweise linke Klammer) |
| endingCharacter | Char | Endzeichen (normalerweise rechte Klammer) |

### Rückgabewert

Das mathematische Element von type[`IMathDelimiter`](../../imathdelimiter) die bestimmte Zeichen als Rahmen enthält

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
IMathDelimiter delimiter = element.Enclose('[', ']');
```

### Siehe auch

* interface [IMathDelimiter](../../imathdelimiter)
* interface [IMathElement](../../imathelement)
* namensraum [Aspose.Slides.MathText](../../imathelement)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
