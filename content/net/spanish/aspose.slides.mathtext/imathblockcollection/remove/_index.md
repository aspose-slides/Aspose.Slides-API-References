---
title: Eliminar
second_title: Referencia de API de Aspose.Slides para .NET
description: Elimina la primera ocurrencia de un objeto específico de la colección.
type: docs
weight: 90
url: /es/aspose.slides.mathtext/imathblockcollection/remove/
---

## IMathBlockCollection.Remove método

Elimina la primera ocurrencia de un objeto específico de la colección.

```csharp
public bool Remove(IMathBlock item)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | IMathBlock | El objeto que se va a eliminar de la colección. |

### Valor de retorno

true si *item* se eliminó correctamente de la colección; de lo contrario, false. Este método también devuelve false si *item* no se encuentra en la colección original.

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
IMathBlock block = new MathBlock(new MathematicalText("y"));
blockCollection.Add(block);
blockCollection.Remove(block);
```

### Véase también

* interfaz [IMathBlock](../../imathblock)
* interfaz [IMathBlockCollection](../../imathblockcollection)
* espacio de nombres [Aspose.Slides.MathText](../../imathblockcollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->