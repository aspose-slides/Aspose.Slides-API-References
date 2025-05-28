---
title: Unir
second_title: Referencia de la API de Aspose.Slides para .NET
description: Une un elemento matemático con este bloque matemático
type: docs
weight: 140
url: /es/aspose.slides.mathtext/mathblock/join/
---

## Unir(IMathElement) {#join}

Une un elemento matemático con este bloque matemático

```csharp
public override IMathBlock Join(IMathElement mathElement)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElement | IMathElement | El elemento a unir |

### Valor de Retorno

La instancia actual de IMathBlock

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement element1 = new MathematicalText("x");
IMathElement element2 = new MathematicalText("y");
IMathBlock block = element1.Join(element2);
```

### Véase También

* interfaz [IMathBlock](../../imathblock)
* interfaz [IMathElement](../../imathelement)
* clase [MathBlock](../../mathblock)
* espacio de nombres [Aspose.Slides.MathText](../../mathblock)
* ensamblado [Aspose.Slides](../../../)

---

## Unir(string) {#join_1}

Une un texto matemático con este bloque matemático

```csharp
public override IMathBlock Join(string mathText)
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

### Véase También

* interfaz [IMathBlock](../../imathblock)
* clase [MathBlock](../../mathblock)
* espacio de nombres [Aspose.Slides.MathText](../../mathblock)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->