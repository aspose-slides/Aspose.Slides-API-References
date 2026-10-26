---
title: get_RotationAngle()
second_title: Referência da API Aspose.Slides para C++
description: Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. Se não for especificado, a rotação da forma associada é usada. Se for especificado, então isso é aplicado independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada além da própria rotação do texto. O valor resultante da rotação visual do texto, resumido a partir desta propriedade e do tipo vertical predefinido na propriedade TextVerticalType. Leia float.
type: docs
weight: 235
url: /pt/aspose.slides.charts/icharttextblockformat/get_rotationangle/
---
## IChartTextBlockFormat::get_RotationAngle() método


Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. Se não for especificado, a rotação da forma associada é usada. Se for especificado, então esta é aplicada independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada além da própria rotação do texto. O valor resultante da rotação visual do texto, resumido a partir desta propriedade e do tipo vertical predefinido na propriedade TextVerticalType. Leia **float**.

```cpp
virtual float Aspose::Slides::Charts::IChartTextBlockFormat::get_RotationAngle()=0
```

## Observações


Considere o caso em que uma forma tem uma rotação de 90 graus no sentido horário aplicada a ela. Além disso, o próprio corpo do texto tem uma rotação de -90 graus no sentido anti-horário aplicada a ele. Então, a forma resultante pareceria estar rotacionada, mas o texto dentro dela pareceria como se não tivesse sido rotacionado.

## Veja Também

* Classe [IChartTextBlockFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)