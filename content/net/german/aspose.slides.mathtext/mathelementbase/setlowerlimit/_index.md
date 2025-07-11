---
title: SetLowerLimit
second_title: Aspose.Slides für .NET API Referenz
description: Nimmt untere Grenze
type: docs
weight: 120
url: /de/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---

## SetLowerLimit(IMathElement) {#setlowerlimit}

Nimmt untere Grenze

```csharp
public IMathLimit SetLowerLimit(IMathElement limit)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| limit | IMathElement | untere Grenze |

### Rückgabewert

Neue Instanz vom Typ [`IMathLimit`](../../imathlimit)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("lim");
IMathElement limitValue = new MathematicalText("𝑛→∞");
var limitElement = baseElement.SetLowerLimit(limitValue);
```

### Siehe auch

* Schnittstelle [IMathLimit](../../imathlimit)
* Schnittstelle [IMathElement](../../imathelement)
* Klasse [MathElementBase](../../mathelementbase)
* Namespace [Aspose.Slides.MathText](../../mathelementbase)
* Assembly [Aspose.Slides](../../../)

---

## SetLowerLimit(string) {#setlowerlimit_1}

Nimmt untere Grenze

```csharp
public IMathLimit SetLowerLimit(string limit)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| limit | String | untere Grenze |

### Rückgabewert

Neue Instanz vom Typ [`IMathLimit`](../../imathlimit)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("lim");
var limitElement = baseElement.SetLowerLimit("𝑛→∞");
```

### Siehe auch

* Schnittstelle [IMathLimit](../../imathlimit)
* Klasse [MathElementBase](../../mathelementbase)
* Namespace [Aspose.Slides.MathText](../../mathelementbase)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->