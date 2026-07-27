---
title: get_RotationAngle()
second_title: Referência da API Aspose.Slides para C++
description: Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. Se não for especificado, a rotação da forma adjacente é usada. Se for especificado, então isso é aplicado independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada além da própria rotação do texto. O valor resultante da rotação visual do texto resumido a partir desta propriedade e do tipo vertical pré-definido na propriedade TextVerticalType. Leia float.
type: docs
weight: 339
url: /pt/aspose.slides/itextframeformat/get_rotationangle/
---
## ITextFrameFormat::get_RotationAngle() método

Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. Se não for especificado, a rotação da forma adjacente é usada. Se for especificado, então isso é aplicado independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada além da própria rotação do texto. O valor resultante da rotação visual do texto resumido a partir desta propriedade e do tipo vertical pré-definido na propriedade TextVerticalType. Read **float**.

```cpp
virtual float Aspose::Slides::ITextFrameFormat::get_RotationAngle()=0
```

## Observações

Considere o caso em que uma forma tem uma rotação de 90 graus no sentido horário aplicada a ela. Além disso, o corpo do texto tem uma rotação de -90 graus no sentido anti-horário aplicada a ele. Então, a forma resultante pareceria estar rotacionada, mas o texto dentro dela pareceria como se não tivesse sido rotacionado.

## Ver também

* Classe [ITextFrameFormat](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)