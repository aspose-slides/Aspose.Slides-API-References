---
title: Añadir
second_title: Referencia de la API de Aspose.Slides para .NET
description: Añade un elemento matemático al final de la colección.
type: docs
weight: 40
url: /es/aspose.slides.mathtext/imathelementcollection/add/
---

## Método IMathElementCollection.Add

Añade un elemento matemático al final de la colección.

```csharp
public void Add(IMathElement item)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | IMathElement | El IMathElement que se añadirá al final de la colección. |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
collection.Add(new MathematicalText("+"));
collection.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
```

### Ver También

* interfaz [IMathElement](../../imathelement)
* interfaz [IMathElementCollection](../../imathelementcollection)
* espacio de nombres [Aspose.Slides.MathText](../../imathelementcollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->