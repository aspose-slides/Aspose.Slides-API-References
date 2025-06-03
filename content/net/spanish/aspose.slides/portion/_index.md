---
title: Portion
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa una porción de texto dentro de un párrafo de texto.
type: docs
weight: 9190
url: /es/aspose.slides/portion/
---

## Clase Porción

Representa una porción de texto dentro de un párrafo de texto.

```csharp
public class Portion : IPortion
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Portion](portion#constructor)() | Inicializa una nueva instancia de la clase Porción. |
| [Portion](portion#constructor_1)(Portion) | Inicializa una nueva instancia de la clase Porción. |
| [Portion](portion#constructor_2)(string) | Inicializa una nueva instancia de la clase Porción. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Field](../../aspose.slides/portion/field) { get; } | Devuelve un campo de esta porción. Solo lectura [`IField`](../ifield). |
| [PortionFormat](../../aspose.slides/portion/portionformat) { get; } | Devuelve un objeto de formato que contiene propiedades de formato establecidas explícitamente de la porción de texto sin herencia aplicada. Solo lectura [`IPortionFormat`](../iportionformat). |
| [Text](../../aspose.slides/portion/text) { get; set; } | Obtiene o establece el texto plano de una porción. Lectura/escritura String. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddField](../../aspose.slides/portion/addfield#addfield)(IFieldType) | Convierte esta porción en el campo actualizado automáticamente. |
| [AddField](../../aspose.slides/portion/addfield#addfield_1)(string) | Convierte esta porción en el campo actualizado automáticamente. |
| [GetCoordinates](../../aspose.slides/portion/getcoordinates)() | Obtiene las coordenadas del comienzo de la porción. La coordenada X del punto representa el comienzo de la porción desde el primer carácter, incluido el margen izquierdo. La coordenada Y incluye el margen superior. |
| [GetRect](../../aspose.slides/portion/getrect)() | Obtiene las coordenadas del rectángulo que delimita la porción. El rectángulo incluye todas las líneas de texto en la porción, incluidas las vacías. |
| [RemoveField](../../aspose.slides/portion/removefield)() | Convierte esta porción de campo en una porción simple. |

### Véase También

* interfaz [IPortion](../iportion)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->