---
title: SetSubscript
second_title: Aspose.Sildes for .NET API Reference
description: Crea subíndices
type: docs
weight: 140
url: /es/aspose.slides.mathtext/imathelement/setsubscript/
---

## SetSubscript(IMathElement) {#setsubscript}

Crea subíndices

```csharp
public IMathSubscriptElement SetSubscript(IMathElement subscript)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | IMathElement | Subíndice (índice inferior a la derecha) |

### Valor de Retorno

Nuevo elemento matemático de tipo [`IMathSubscriptElement`](../../imathsubscriptelement)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement element = new MathematicalText("N");
IMathElement index = new MathematicalText("i");
IMathSubscriptElement subscript = element.SetSubscript(index);
```

### Véase También

* interface [IMathSubscriptElement](../../imathsubscriptelement)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## SetSubscript(string) {#setsubscript_1}

Crea subíndices

```csharp
public IMathSubscriptElement SetSubscript(string subscript)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | String | Subíndice (índice inferior a la derecha) |

### Valor de Retorno

Nuevo elemento matemático de tipo [`IMathSubscriptElement`](../../imathsubscriptelement)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement element = new MathematicalText("N");
IMathSubscriptElement subscript = element.SetSubscript("i");
```

### Véase También

* interface [IMathSubscriptElement](../../imathsubscriptelement)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->