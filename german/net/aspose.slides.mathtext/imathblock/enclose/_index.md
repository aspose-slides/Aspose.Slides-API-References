---
title: Enclose
second_title: Aspose.Slides für .NET-API-Referenz
description: Schließt untergeordnete Elemente dieses Blocks in bestimmte Zeichen wie Klammern oder andere als Rahmen ein und begrenzt sie mit einem Trennzeichen
type: docs
weight: 40
url: /de/net/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock.Enclose method

Schließt untergeordnete Elemente dieses Blocks in bestimmte Zeichen wie Klammern oder andere als Rahmen ein und begrenzt sie mit einem Trennzeichen

```csharp
public IMathDelimiter Enclose(char beginningCharacter, char endingCharacter, 
    char separatorCharacter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| beginningCharacter | Char | Anfangszeichen (normalerweise linke Klammer) |
| endingCharacter | Char | Endzeichen (normalerweise rechte Klammer) |
| separatorCharacter | Char | Trennzeichen |

### Rückgabewert

Das mathematische Element von type[`IMathDelimiter`](../../imathdelimiter) die bestimmte Zeichen als Rahmen und Trennzeichen enthält

### Beispiele

Beispiel:

```csharp
[C#]
IMathBlock mathBlock = new MathematicalText("x").Join("y");
IMathDelimiter delimiterElement = mathBlock.Enclose('{', '}', '%');
```

### Siehe auch

* interface [IMathDelimiter](../../imathdelimiter)
* interface [IMathBlock](../../imathblock)
* namensraum [Aspose.Slides.MathText](../../imathblock)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->