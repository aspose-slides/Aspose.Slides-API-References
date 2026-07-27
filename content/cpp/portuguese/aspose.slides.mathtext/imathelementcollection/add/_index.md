---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona um elemento matemático ao final da coleção.
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/imathelementcollection/add/
---
## IMathElementCollection::Add(System::SharedPtr\<IMathElement\>) método

Adiciona um elemento matemático ao final da coleção.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::Add(System::SharedPtr<IMathElement> item)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O [IMathElement](../../imathelement/) a ser adicionado ao final da coleção. |
## Observações



Exemplo: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
collection->Add(System::MakeObject<MathematicalText>(u"+"));
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathElementCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)