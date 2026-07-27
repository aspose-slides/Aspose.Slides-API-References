---
title: ToMathArray()
second_title: Referência da API Aspose.Slides para C++
description: Coloca elementos filhos em um array vertical
type: docs
weight: 235
url: /pt/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() método


Coloca elementos filhos em um array vertical

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```


### Valor de Retorno

Nova instância do tipo [IMathArray](../../imatharray/)
## Observações



Exemplo: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathArray](../../imatharray/)
* Classe [MathBlock](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)