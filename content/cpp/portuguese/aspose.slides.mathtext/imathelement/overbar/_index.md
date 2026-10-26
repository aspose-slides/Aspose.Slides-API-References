---
title: Overbar()
second_title: Referência da API Aspose.Slides para C++
description: Define uma barra no topo deste elemento
type: docs
weight: 222
url: /pt/aspose.slides.mathtext/imathelement/overbar/
---
## IMathElement::Overbar() método


Define uma barra no topo deste elemento

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathElement::Overbar()=0
```


### Valor de retorno

Nova instância do tipo [IMathBar](../../imathbar/)
## Observações



Exemplo:
```cpp
auto bar = System::MakeObject<MathematicalText>(u"x")->Overbar();
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBar](../../imathbar/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)