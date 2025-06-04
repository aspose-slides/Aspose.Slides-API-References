---
title: SetSuperscript
second_title: Aspose.Sildes para la referencia de API de .NET
description: Crea superíndices
type: docs
weight: 160
url: /es/aspose.slides.mathtext/mathelementbase/setsuperscript/
---

## SetSuperscript(IMathElement) {#setsuperscript}

Crea superíndices

```csharp
public IMathSuperscriptElement SetSuperscript(IMathElement superscript)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| superscript | IMathElement | Superíndice (índice superior a la derecha) |

### Valor de retorno

Nuevo elemento matemático del tipo [`IMathSuperscriptElement`](../../imathsuperscriptelement)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement element = new MathematicalText("N");
IMathElement index = new MathematicalText("4");
IMathSuperscriptElement superscript = element.SetSuperscript(index);
```

### Ver También

* interfaz [IMathSuperscriptElement](../../imathsuperscriptelement)
* interfaz [IMathElement](../../imathelement)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblaje [Aspose.Slides](../../../)

---

## SetSuperscript(string) {#setsuperscript_1}

Crea superíndices

```csharp
public IMathSuperscriptElement SetSuperscript(string superscript)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| superscript | String | Superíndice (índice superior a la derecha) |

### Valor de retorno

Nuevo elemento matemático del tipo [`IMathSuperscriptElement`](../../imathsuperscriptelement)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement element = new MathematicalText("N");
IMathSuperscriptElement superscript = element.SetSuperscript("4");
```

### Ver También

* interfaz [IMathSuperscriptElement](../../imathsuperscriptelement)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->
