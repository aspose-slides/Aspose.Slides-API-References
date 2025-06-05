---
title: IMathDelimiter
second_title: Referencia de la API de Aspose.Slides para .NET
description: Especifica el objeto delimitador que consiste en caracteres de apertura y cierre como paréntesis, llaves, corchetes y barras verticales, y uno o más elementos matemáticos dentro, separados por un carácter especificado. Ejemplos 2 2x7C2
type: docs
weight: 7960
url: /es/aspose.slides.mathtext/imathdelimiter/
---

## Interfaz IMathDelimiter

Especifica el objeto delimitador, que consiste en caracteres de apertura y cierre (como paréntesis, llaves, corchetes y barras verticales), y uno o más elementos matemáticos dentro, separados por un carácter especificado. Ejemplos: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public interface IMathDelimiter : IMathElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/imathdelimiter/arguments) { get; } | Uno o más elementos matemáticos separados por caracteres delimitadores |
| [AsIMathElement](../../aspose.slides.mathtext/imathdelimiter/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [BeginningCharacter](../../aspose.slides.mathtext/imathdelimiter/beginningcharacter) { get; set; } | El carácter de inicio del delimitador especifica el carácter delimitador de inicio o apertura. Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves. El valor predeterminado: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/imathdelimiter/delimitershape) { get; set; } | Especifica la forma de los delimitadores en el objeto delimitador. Cuando es MathDelimiterShape.Centered, los delimitadores se centran alrededor del eje matemático del texto matemático y aún pueden ajustarse para encajar en toda la altura de su contenido. Cuando es MathDelimiterShape.Match, su altura y forma se alteran para coincidir exactamente con su contenido. |
| [EndingCharacter](../../aspose.slides.mathtext/imathdelimiter/endingcharacter) { get; set; } | El carácter final del delimitador especifica el carácter delimitador de cierre o final. Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves. El valor predeterminado: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/imathdelimiter/growtomatchoperandheight) { get; set; } | Especifica el crecimiento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Cuando es verdadero, los delimitadores crecen verticalmente para igualar la altura de su operando. El valor predeterminado es verdadero. |
| [SeparatorCharacter](../../aspose.slides.mathtext/imathdelimiter/separatorcharacter) { get; set; } | El carácter separador del delimitador especifica el carácter que separa los argumentos en el objeto delimitador. El valor predeterminado: '&#x7C;'. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Delimit](../../aspose.slides.mathtext/imathdelimiter/delimit)(char) | Delimita los argumentos utilizando el carácter delimitador especificado |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
IMathDelimiter delimiter = element.Enclose();
```

### También Vea

* interfaz [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->