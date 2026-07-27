---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona um elemento matemático ao final da coleção.
type: docs
weight: 79
url: /pt/aspose.slides.mathtext/mathblock/add/
---
## MathBlock::Add(System::SharedPtr\<IMathElement\>) método


Adiciona um elemento matemático ao final da coleção.

```cpp
void Aspose::Slides::MathText::MathBlock::Add(System::SharedPtr<IMathElement> item) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O [IMathElement](../../imathelement/) a ser adicionado ao final da coleção. |
## Observações



Exemplo: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
mathBlock->Add(System::MakeObject<MathematicalText>(u"+"));
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)