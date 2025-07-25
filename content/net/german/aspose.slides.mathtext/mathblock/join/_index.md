---
title: Join
second_title: Aspose.Slides für .NET API-Referenz
description: Verbindet ein mathematisches Element mit diesem mathematischen Block
type: docs
weight: 140
url: /de/aspose.slides.mathtext/mathblock/join/
---

## Join(IMathElement) {#join}

Verbindet ein mathematisches Element mit diesem mathematischen Block

```csharp
public override IMathBlock Join(IMathElement mathElement)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElement | IMathElement | Das zu verbindende Element |

### Rückgabewert

Die aktuelle Instanz von IMathBlock

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement element1 = new MathematicalText("x");
IMathElement element2 = new MathematicalText("y");
IMathBlock block = element1.Join(element2);
```

### Siehe auch

* Schnittstelle [IMathBlock](../../imathblock)
* Schnittstelle [IMathElement](../../imathelement)
* Klasse [MathBlock](../../mathblock)
* Namespace [Aspose.Slides.MathText](../../mathblock)
* Assembly [Aspose.Slides](../../../)

---

## Join(string) {#join_1}

Verbindet einen mathematischen Text mit diesem mathematischen Block

```csharp
public override IMathBlock Join(string mathText)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathText | String | Mathematischer Text, der verbunden werden soll |

### Rückgabewert

Ein neues IMathBlock, das diese Instanz und das angegebene Argument enthält

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
IMathBlock block = element.Join("+y");
```

### Siehe auch

* Schnittstelle [IMathBlock](../../imathblock)
* Klasse [MathBlock](../../mathblock)
* Namespace [Aspose.Slides.MathText](../../mathblock)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
