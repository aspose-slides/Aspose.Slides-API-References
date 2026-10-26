---
title: ToMathArray()
second_title: Aspose.Slides for C++ Referência da API
description: Coloca em um array vertical
type: docs
weight: 183
url: /pt/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() método


Coloca em um array vertical

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```


### Valor de retorno

Nova instância do tipo [IMathArray](../../imatharray/)
## Observações



Exemplo: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathArray](../../imatharray/)
* Classe [IMathElement](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)