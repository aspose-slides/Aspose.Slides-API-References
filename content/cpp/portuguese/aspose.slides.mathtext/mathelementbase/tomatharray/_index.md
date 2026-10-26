---
title: ToMathArray()
second_title: Referência da API Aspose.Slides for C++
description: Insere em um array vertical
type: docs
weight: 170
url: /pt/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() método


Insere em um array vertical

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```


### Valor de Retorno

Nova instância do tipo [IMathArray](../../imatharray/)
## Observações



Exemplo: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathArray](../../imatharray/)
* Classe [MathElementBase](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)