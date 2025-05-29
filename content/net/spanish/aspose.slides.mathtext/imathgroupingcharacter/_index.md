---
title: IMathGroupingCharacter
second_title: Referencia de la API de Aspose.Slides para .NET
description: Especifica un símbolo de agrupamiento por encima o por debajo de una expresión, generalmente para resaltar la relación entre elementos.
type: docs
weight: 8040
url: /es/aspose.slides.mathtext/imathgroupingcharacter/
---

## Interfaz IMathGroupingCharacter

Especifica un símbolo de agrupamiento por encima o por debajo de una expresión, generalmente para resaltar la relación entre elementos.

```csharp
public interface IMathGroupingCharacter : IMathElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathgroupingcharacter/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathgroupingcharacter/base) { get; } | Argumento base |
| [Character](../../aspose.slides.mathtext/imathgroupingcharacter/character) { get; set; } | Caracter de agrupamiento Valor por defecto: U+23DF (LLAVE CURLY INFERIOR) |
| [Position](../../aspose.slides.mathtext/imathgroupingcharacter/position) { get; set; } | Posición del carácter de agrupamiento. Por defecto: Inferior |
| [VerticalJustification](../../aspose.slides.mathtext/imathgroupingcharacter/verticaljustification) { get; set; } | Justificación vertical del carácter de agrupamiento. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de agrupamiento está por encima del objeto, la JustificaciónVertical de Superior significa que la parte superior del objeto cae en la línea base; cuando se establece JustificaciónVertical en Inferior, la parte inferior del objeto está en la línea base. Por defecto: Inferior para Position=Superior, y Superior para Position=Inferior |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").Group();
```

### Véase también

* interfaz [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->