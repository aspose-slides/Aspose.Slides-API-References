---
title: get_Arguments()
second_title: Referência da API Aspose.Slides para C++
description: O conjunto de itens do array
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() método


O conjunto de itens do array

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## Observações


Exemplo:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElementCollection](../../imathelementcollection/)
* Classe [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)