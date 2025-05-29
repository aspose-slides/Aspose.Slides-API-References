---
title: ToBox
second_title: Referencia de la API de Aspose.Slides para .NET
description: Coloca este elemento en un grupo lógico no visual, que se utiliza para agrupar componentes de una ecuación u otra instancia de texto matemático. Un objeto enmarcado puede, por ejemplo, servir como un emulador de operador con o sin un punto de alineación, servir como un punto de quiebre de línea o ser agrupado de tal manera que no permita quiebres de línea en su interior.
type: docs
weight: 190
url: /es/aspose.slides.mathtext/mathelementbase/tobox/
---

## Método MathElementBase.ToBox

Coloca este elemento en un cuadro no visual (agrupación lógica) que se utiliza para agrupar componentes de una ecuación u otra instancia de texto matemático. Un objeto enmarcado puede (por ejemplo) servir como un emulador de operador con o sin un punto de alineación, servir como un punto de quiebre de línea, o ser agrupado de tal manera que no permita quiebres de línea en su interior.

```csharp
public IMathBox ToBox()
```

### Valor de Retorno

Caja lógica con este elemento colocado dentro.

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBox box = new MathematicalText("x:=y").ToBox();
```

### Véase También

* interfaz [IMathBox](../../imathbox)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->