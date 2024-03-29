---
title: Remove
second_title: Referencia de la API de Aspose.Slides para .NET
description: Elimina la primera aparición de un objeto específico de la colección.
type: docs
weight: 100
url: /es/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection.Remove method

Elimina la primera aparición de un objeto específico de la colección.

```csharp
public bool Remove(IMathElement item)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| item | IMathElement | El objeto que se va a quitar de la colección. |

### Valor_devuelto

verdadero si*item* fue eliminado con éxito de la colección; en caso contrario, falso. Este método también devuelve falso si*item* no se encuentra en la colección original.

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
collection.Add(plusElement);
collection.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
collection.Remove(plusElement);
```

### Ver también

* interface [IMathElement](../../imathelement)
* interface [IMathElementCollection](../../imathelementcollection)
* espacio de nombres [Aspose.Slides.MathText](../../imathelementcollection)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
