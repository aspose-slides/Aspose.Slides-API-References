---
title: SetUpperLimit
second_title: Aspose.Slides für .NET-API-Referenz
description: nimmt Obergrenze
type: docs
weight: 170
url: /de/net/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## SetUpperLimit(IMathElement) {#setupperlimit}

nimmt Obergrenze

```csharp
public IMathLimit SetUpperLimit(IMathElement limit)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| limit | IMathElement | Grenze |

### Rückgabewert

Neue Instanz des Typs[`IMathLimit`](../../imathlimit)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("y");
IMathElement limitValue = new MathematicalText("y−>1");
var limitElement = baseElement.SetUpperLimit(limitValue);
```

### Siehe auch

* interface [IMathLimit](../../imathlimit)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namensraum [Aspose.Slides.MathText](../../mathelementbase)
* Montage [Aspose.Slides](../../../)

---

## SetUpperLimit(string) {#setupperlimit_1}

nimmt Obergrenze

```csharp
public IMathLimit SetUpperLimit(string limit)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| limit | String | Grenze |

### Rückgabewert

Neue Instanz des Typs[`IMathLimit`](../../imathlimit)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("y");
var limitElement = baseElement.SetUpperLimit("y−>1");
```

### Siehe auch

* interface [IMathLimit](../../imathlimit)
* class [MathElementBase](../../mathelementbase)
* namensraum [Aspose.Slides.MathText](../../mathelementbase)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->