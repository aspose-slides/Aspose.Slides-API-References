---
title: IMathBlock
second_title: Referencia de la API de Aspose.Slides para .NET
description: Especifica una instancia de texto matemático contenido en un MathParagraph y comienza en su propia línea. Todas las zonas matemáticas incluidas ecuaciones expresiones matrices de ecuaciones o expresiones y fórmulas están representadas por bloques matemáticos.
type: docs
weight: 7430
url: /es/aspose.slides.mathtext/imathblock/
---
## IMathBlock interface

Especifica una instancia de texto matemático contenido en un MathParagraph y comienza en su propia línea. Todas las zonas matemáticas, incluidas ecuaciones, expresiones, matrices de ecuaciones o expresiones y fórmulas, están representadas por bloques matemáticos.

```csharp
public interface IMathBlock : IMathElement, IMathElementCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathblock/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [AsIMathElementCollection](../../aspose.slides.mathtext/imathblock/asimathelementcollection) { get; } | Permite obtener la interfaz base IMathElementCollection [`IMathElementCollection`](../imathelementcollection) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Delimit](../../aspose.slides.mathtext/imathblock/delimit)(char) | Delimita todos los elementos secundarios con carácter separador (sin los corchetes) |
| [Enclose](../../aspose.slides.mathtext/imathblock/enclose)(char, char, char) | Encierra elementos secundarios de este bloque en caracteres específicos como paréntesis u otro como framing y delimita con un carácter separador |
| [JoinBlock](../../aspose.slides.mathtext/imathblock/joinblock)(IMathBlock) | Une otro bloque matemático con este |
| [WriteAsMathMl](../../aspose.slides.mathtext/imathblock/writeasmathml)(Stream) | Guarda el contenido de este[`IMathBlock`](../imathblock) como MathML |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBlock mathBlock = new MathBlock();
```

### Ver también

* interface [IMathElement](../imathelement)
* interface [IMathElementCollection](../imathelementcollection)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
