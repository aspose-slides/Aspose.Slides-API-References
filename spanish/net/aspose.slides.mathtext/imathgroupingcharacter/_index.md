---
title: IMathGroupingCharacter
second_title: Referencia de la API de Aspose.Slides para .NET
description: Especifica un símbolo de agrupación encima o debajo de una expresión generalmente para resaltar la relación entre elementos
type: docs
weight: 7580
url: /es/net/aspose.slides.mathtext/imathgroupingcharacter/
---
## IMathGroupingCharacter interface

Especifica un símbolo de agrupación encima o debajo de una expresión, generalmente para resaltar la relación entre elementos

```csharp
public interface IMathGroupingCharacter : IMathElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathgroupingcharacter/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathgroupingcharacter/base) { get; } | Argumento base |
| [Character](../../aspose.slides.mathtext/imathgroupingcharacter/character) { get; set; } | Carácter de agrupación Valor predeterminado: U+23DF (CORCHETE INFERIOR) |
| [Position](../../aspose.slides.mathtext/imathgroupingcharacter/position) { get; set; } | Posición del carácter de agrupación. Predeterminado: Inferior |
| [VerticalJustification](../../aspose.slides.mathtext/imathgroupingcharacter/verticaljustification) { get; set; } | Justificación vertical del carácter de grupo. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de grupo está sobre el objeto, Justificación vertical de la parte superior significa que la parte superior del objeto cae sobre la línea base; cuando VerticalJustification se establece en Inferior, la parte inferior del objeto está en la línea base Predeterminado: Inferior para Posición=Superior y Superior para Posición=Inferior |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").Group();
```

### Ver también

* interface [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->