---
title: set_RotationAngle()
second_title: Aspose.Slides para C++ Referência da API
description: Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. Se não for especificada, é usada a rotação da forma associada. Se for especificada, então ela é aplicada independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada além da própria rotação do texto. O valor resultante da rotação visual do texto é resumido a partir desta propriedade e do tipo vertical predefinido na propriedade TextVerticalType. Escreva float.
type: docs
weight: 352
url: /pt/aspose.slides/itextframeformat/set_rotationangle/
---
## ITextFrameFormat::set_RotationAngle(float) método


Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. Se não for especificado, é usada a rotação da forma associada. Se for especificado, então isso é aplicado independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada além da própria rotação do texto. O valor resultante da rotação visual do texto é resumido a partir desta propriedade e do tipo vertical predefinido na propriedade TextVerticalType. Escreva **float**.

```cpp
virtual void Aspose::Slides::ITextFrameFormat::set_RotationAngle(float value)=0
```

## Observações


Considere o caso em que uma forma tem uma rotação de 90 graus no sentido horário aplicada a ela. Além disso, o corpo de texto em si tem uma rotação de -90 graus no sentido anti-horário aplicada a ele. Então, a forma resultante pareceria estar rotacionada, mas o texto dentro dela pareceria como se não tivesse sido rotacionado.

## Veja Também

* Classe [ITextFrameFormat](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)