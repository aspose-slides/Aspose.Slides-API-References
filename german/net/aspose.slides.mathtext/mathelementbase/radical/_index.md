---
title: Radical
second_title: Aspose.Slides für .NET-API-Referenz
description: Gibt die mathematische Wurzel des angegebenen Grads aus dem angegebenen Argument an.
type: docs
weight: 110
url: /de/net/aspose.slides.mathtext/mathelementbase/radical/
---
## Radical(IMathElement) {#radical}

Gibt die mathematische Wurzel des angegebenen Grads aus dem angegebenen Argument an.

```csharp
public IMathRadical Radical(IMathElement degree)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| degree | IMathElement | Argument des Radikalen |

### Rückgabewert

Neue Instanz des Typs[`IMathRadical`](../../imathradical)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("2px");
IMathElement degree = new MathematicalText("y");
var radical = baseElement.Radical(degree);
```

### Siehe auch

* interface [IMathRadical](../../imathradical)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namensraum [Aspose.Slides.MathText](../../mathelementbase)
* Montage [Aspose.Slides](../../../)

---

## Radical(string) {#radical_1}

Gibt die mathematische Wurzel des angegebenen Grads aus dem angegebenen Argument an.

```csharp
public IMathRadical Radical(string degree)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| degree | String | Argument des Radikalen |

### Rückgabewert

Neue Instanz des Typs[`IMathRadical`](../../imathradical)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("2px");
var radical = baseElement.Radical("3");
```

### Siehe auch

* interface [IMathRadical](../../imathradical)
* class [MathElementBase](../../mathelementbase)
* namensraum [Aspose.Slides.MathText](../../mathelementbase)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->