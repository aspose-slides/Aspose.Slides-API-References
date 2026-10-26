---
title: get_Arguments()
second_title: Referência da API Aspose.Slides para C++
description: O conjunto de itens do array
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() método


O conjunto de itens do array

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## Observações


Exemplo: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElementCollection](../../imathelementcollection/)
* Classe [MathArray](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)