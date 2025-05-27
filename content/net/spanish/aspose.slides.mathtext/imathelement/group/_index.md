---
title: Grupo
second_title: Referencia de la API de Aspose.Slides para .NET
description: Coloca este elemento en un grupo utilizando una llave de apertura
type: docs
weight: 70
url: /es/aspose.slides.mathtext/imathelement/group/
---

## Group() {#group}

Coloca este elemento en un grupo utilizando una llave de apertura

```csharp
public IMathGroupingCharacter Group()
```

### Valor de Retorno

Nueva instancia del tipo [`IMathGroupingCharacter`](../../imathgroupingcharacter)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").Group();
```

### Ver También

* interfaz [IMathGroupingCharacter](../../imathgroupingcharacter)
* interfaz [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* ensamblaje [Aspose.Slides](../../../)

---

## Group(char, MathTopBotPositions, MathTopBotPositions) {#group_1}

Coloca este elemento en un grupo utilizando un carácter de agrupación, como una llave de apertura o otro

```csharp
public IMathGroupingCharacter Group(char character, MathTopBotPositions position, 
    MathTopBotPositions verticalJustification)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| character | Char | Carácter de agrupación, como la LLAVE DE APERTURA INFERIOR (U+23DF) o cualquier otro |
| position | MathTopBotPositions | Posición del carácter de agrupación |
| verticalJustification | MathTopBotPositions | Justificación vertical del carácter de grupo. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de grupo está por encima del objeto, la JustificaciónVertical de Top significa que la parte superior del objeto cae sobre la línea base; cuando la JustificaciónVertical se establece en Bottom, la parte inferior del objeto está en la línea base |

### Valor de Retorno

Nueva instancia del tipo [`IMathGroupingCharacter`](../../imathgroupingcharacter)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").Group('\u23E1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
```

### Ver También

* interfaz [IMathGroupingCharacter](../../imathgroupingcharacter)
* enum [MathTopBotPositions](../../mathtopbotpositions)
* interfaz [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->