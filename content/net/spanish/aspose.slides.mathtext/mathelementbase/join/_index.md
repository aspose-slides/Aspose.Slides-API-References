---
title: Unir
second_title: Referencia de la API de Aspose.Slides para .NET
description: Une un elemento matemático y forma un bloque matemático
type: docs
weight: 80
url: /es/aspose.slides.mathtext/mathelementbase/join/
---

## Unir(IMathElement) {#join}

Une un elemento matemático y forma un bloque matemático

```csharp
public virtual IMathBlock Join(IMathElement mathElement)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElement | IMathElement | El elemento a unir |

### Valor de Retorno

Un nuevo IMathBlock que contiene esta instancia y el argumento especificado

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement element1 = new MathematicalText("x");
IMathElement element2 = new MathematicalText("y");
IMathBlock block = element1.Join(element2);
```

### Ver También

* interfaz [IMathBlock](../../imathblock)
* interfaz [IMathElement](../../imathelement)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblado [Aspose.Slides](../../../)

---

## Unir(string) {#join_1}

Une un texto matemático y forma un bloque matemático

```csharp
public virtual IMathBlock Join(string mathText)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | String | Texto matemático a unir |

### Valor de Retorno

Un nuevo IMathBlock que contiene esta instancia y el argumento especificado

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
IMathBlock block = element.Join("+y");
```

### Ver También

* interfaz [IMathBlock](../../imathblock)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->