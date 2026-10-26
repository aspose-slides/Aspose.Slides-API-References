---
title: Join()
second_title: Referência da API Aspose.Slides para C++
description: Une um elemento matemático e forma um bloco matemático
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) método

Une um elemento matemático e forma um bloco matemático

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | O elemento a ser unido |

### Valor de Retorno

Um novo [IMathBlock](../../imathblock/) contendo esta instância e o argumento especificado
## Observações

Exemplo:
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) método

Une um texto matemático e forma um bloco matemático

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Texto matemático a ser unido |

### Valor de Retorno

Um novo [IMathBlock](../../imathblock/) contendo esta instância e o argumento especificado
## Observações

Exemplo:
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)