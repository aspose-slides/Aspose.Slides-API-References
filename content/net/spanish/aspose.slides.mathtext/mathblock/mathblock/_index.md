---
title: MathBlock
second_title: Referencia de API de Aspose.Slides para .NET
description: Inicializa una nueva instancia de la clase MathBlock.
type: docs
weight: 10
url: /es/aspose.slides.mathtext/mathblock/mathblock/
---

## MathBlock() {#constructor}

Inicializa una nueva instancia de la clase MathBlock.

```csharp
public MathBlock()
```

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Véase también

* clase [MathBlock](../../mathblock)
* espacio de nombres [Aspose.Slides.MathText](../../mathblock)
* ensamblado [Aspose.Slides](../../../)

---

## MathBlock(IMathElement) {#constructor_1}

Crea un nuevo bloque matemático y coloca el elemento especificado en él.

```csharp
public MathBlock(IMathElement mathElement)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElement | IMathElement | El elemento matemático a colocar en el bloque |

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
```

### Véase también

* interfaz [IMathElement](../../imathelement)
* clase [MathBlock](../../mathblock)
* espacio de nombres [Aspose.Slides.MathText](../../mathblock)
* ensamblado [Aspose.Slides](../../../)

---

## MathBlock(IEnumerable&lt;IMathElement&gt;) {#constructor_2}

Crea un nuevo bloque matemático y coloca los elementos especificados en él.

```csharp
public MathBlock(IEnumerable<IMathElement> mathElements)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElements | IEnumerable`1 | Elementos matemáticos a colocar en el bloque |

### Ejemplos

Ejemplo:

```csharp
[C#]
var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
MathBlock mathBlock = new MathBlock(elems);
```

### Véase también

* interfaz [IMathElement](../../imathelement)
* clase [MathBlock](../../mathblock)
* espacio de nombres [Aspose.Slides.MathText](../../mathblock)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->