---
title: set_RotationAngle()
second_title: Referência da API Aspose.Slides para C++
description: Especifica personalizada a rotação que está sendo aplicada ao texto dentro da caixa delimitadora. Se não for especificado, a rotação da forma associada é usada. Se for especificado, então isso é aplicado independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada além da rotação aplicada ao próprio texto. O valor resultante da rotação visual do texto é resumido a partir desta propriedade e do tipo vertical predefinido na propriedade TextVerticalType. Escreva float.
type: docs
weight: 313
url: /pt/aspose.slides/textframeformat/set_rotationangle/
---
## TextFrameFormat::set_RotationAngle(float) método


Especifica personalizado a rotação que está sendo aplicada ao texto dentro da caixa delimitadora. Se não for especificado, a rotação da forma associada é usada. Se for especificado, então isso é aplicado independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada além da rotação aplicada ao próprio texto. O valor resultante da rotação visual do texto é resumido a partir desta propriedade e do tipo vertical predefinido na propriedade TextVerticalType. Escreva **float**.

```cpp
void Aspose::Slides::TextFrameFormat::set_RotationAngle(float value) override
```

## Observações


Considere o caso em que uma forma tem uma rotação de 90 graus no sentido horário aplicada a ela. Além disso, o próprio corpo de texto tem uma rotação de -90 graus no sentido anti-horário aplicada a ele. Então, a forma resultante pareceria estar rotacionada, mas o texto dentro dela pareceria como se não tivesse sido rotacionado.

## Ver também

* Classe [TextFrameFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)