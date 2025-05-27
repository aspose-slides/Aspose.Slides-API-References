---
title: SetSubscript
second_title: Referencia de API de Aspose.Slides para .NET
description: Crea subíndice
type: docs
weight: 130
url: /es/aspose.slides.mathtext/mathelementbase/setsubscript/
---

## SetSubscript(IMathElement) {#setsubscript}

Crea subíndice

```csharp
public IMathSubscriptElement SetSubscript(IMathElement subscript)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | IMathElement | Subíndice (índice inferior a la derecha) |

### Valor de retorno

Nuevo elemento matemático de tipo [`IMathSubscriptElement`](../../imathsubscriptelement)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement element = new MathematicalText("N");
IMathElement index = new MathematicalText("i");
IMathSubscriptElement subscript = element.SetSubscript(index);
```

### Véase también

* interfaz [IMathSubscriptElement](../../imathsubscriptelement)
* interfaz [IMathElement](../../imathelement)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblado [Aspose.Slides](../../../)

---

## SetSubscript(string) {#setsubscript_1}

Crea subíndice

```csharp
public IMathSubscriptElement SetSubscript(string subscript)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | String | Subíndice (índice inferior a la derecha) |

### Valor de retorno

Nuevo elemento matemático de tipo [`IMathSubscriptElement`](../../imathsubscriptelement)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement element = new MathematicalText("N");
IMathSubscriptElement subscript = element.SetSubscript("i");
```

### Véase también

* interfaz [IMathSubscriptElement](../../imathsubscriptelement)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->