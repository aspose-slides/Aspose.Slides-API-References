---
title: IMathGroupingCharacter
second_title: Aspose.Slides para .NET Referencia de API
description: Especifica un símbolo de agrupación encima o debajo de una expresión, generalmente para resaltar la relación entre elementos
type: docs
weight: 8040
url: /es/aspose.slides.mathtext/imathgroupingcharacter/
---

## Interfaz IMathGroupingCharacter

Especifica un símbolo de agrupación encima o debajo de una expresión, generalmente para resaltar la relación entre elementos

```csharp
public interface IMathGroupingCharacter : IMathElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathgroupingcharacter/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathgroupingcharacter/base) { get; } | Argumento base |
| [Character](../../aspose.slides.mathtext/imathgroupingcharacter/character) { get; set; } | Carácter de agrupación Valor por defecto: U+23DF (LLAVE CURVA INFERIOR) |
| [Position](../../aspose.slides.mathtext/imathgroupingcharacter/position) { get; set; } | Posición del carácter de agrupación. Predeterminado: Inferior |
| [VerticalJustification](../../aspose.slides.mathtext/imathgroupingcharacter/verticaljustification) { get; set; } | Justificación vertical del carácter de grupo. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de grupo está por encima del objeto, la JustificaciónVertical de Superior significa que la parte superior del objeto cae sobre la línea base; cuando la JustificaciónVertical se establece en Inferior, la parte inferior del objeto está en la línea base. Predeterminado: Inferior para Position=Superior, y Superior para Position=Inferior |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").Group();
```

### Vea También

* interfaz [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->