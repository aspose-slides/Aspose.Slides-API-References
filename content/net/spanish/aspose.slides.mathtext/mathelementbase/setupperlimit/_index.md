---
title: SetUpperLimit
second_title: Aspose.Sildes para .NET Referencia de API
description: Toma el límite superior
type: docs
weight: 170
url: /es/aspose.slides.mathtext/mathelementbase/setupperlimit/
---

## SetUpperLimit(IMathElement) {#setupperlimit}

Toma el límite superior

```csharp
public IMathLimit SetUpperLimit(IMathElement limit)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| limit | IMathElement | límite |

### Valor de Retorno

Nueva instancia del tipo [`IMathLimit`](../../imathlimit)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("y");
IMathElement limitValue = new MathematicalText("y−>1");
var limitElement = baseElement.SetUpperLimit(limitValue);
```

### Ver También

* interfaz [IMathLimit](../../imathlimit)
* interfaz [IMathElement](../../imathelement)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblado [Aspose.Slides](../../../)

---

## SetUpperLimit(string) {#setupperlimit_1}

Toma el límite superior

```csharp
public IMathLimit SetUpperLimit(string limit)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| limit | String | límite |

### Valor de Retorno

Nueva instancia del tipo [`IMathLimit`](../../imathlimit)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("y");
var limitElement = baseElement.SetUpperLimit("y−>1");
```

### Ver También

* interfaz [IMathLimit](../../imathlimit)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblado [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->