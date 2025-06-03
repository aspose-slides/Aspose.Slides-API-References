---
title: Delimit
second_title: Referencia de la API de Aspose.Slides para .NET
description: Delimita argumentos utilizando el carácter delimitador especificado
type: docs
weight: 80
url: /es/aspose.slides.mathtext/imathdelimiter/delimit/
---

## Método IMathDelimiter.Delimit

Delimita argumentos utilizando el carácter delimitador especificado

```csharp
public IMathDelimiter Delimit(char separatorCharacter)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separatorCharacter | Char | carácter delimitador |

### Valor de Retorno

Este objeto después de aplicar el carácter delimitador

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathDelimiter delimiter = new MathematicalText("x").Join("y").Enclose();
delimiter.Delimit('|');
```

### Vea También

* interfaz [IMathDelimiter](../../imathdelimiter)
* espacio de nombres [Aspose.Slides.MathText](../../imathdelimiter)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->