---
title: get_PathTypes()
second_title: Referência da API Aspose.Slides para C++
description: Obtém um array de valores byte que especificam o tipo de cada ponto no caminho do elemento.
type: docs
weight: 27
url: /pt/aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() method

Obtém um array de valores byte que especificam o tipo de cada ponto no caminho do elemento.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```

## Observações

**0** Indica que o ponto é o início de uma figura.

**1** Indica que o ponto é um dos dois extremos de uma linha.

**3** Indica que o ponto é um ponto final ou ponto de controle de uma spline cúbica de Bezier.

**7** Masca todos os bits exceto os três bits de ordem inferior, que indicam o tipo de ponto.

**16** Especifica que o segmento correspondente é tracejado.

**32** Especifica que o ponto é um marcador.

**128** Especifica que o ponto é o último ponto em um subcaminho fechado (figura).

**129** Indica um ponto de dados que é tanto um extremo do segmento de linha quanto o último ponto de um subcaminho fechado.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ShapeElement](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)