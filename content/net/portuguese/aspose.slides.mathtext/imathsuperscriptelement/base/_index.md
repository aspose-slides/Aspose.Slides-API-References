---
title: Base
second_title: Referência de API Aspose.Sildes para .NET
description: Argumento Base
type: docs
weight: 20
url: /pt/aspose.slides.mathtext/imathsuperscriptelement/base/
---
## IMathSuperscriptElement.Base propriedade

Argumento Base

```csharp
public IMathElement Base { get; }
```

### Exemplos

Exemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement superscript = new MathematicalText("i");
IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
IMathElement baseElem = superscriptElement.Base;
```

### Veja Também

* interface [IMathElement](../../imathelement)
* interface [IMathSuperscriptElement](../../imathsuperscriptelement)
* espaço de nomes [Aspose.Slides.MathText](../../imathsuperscriptelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: gerado por xmldocmd para Aspose.Slides.dll -->