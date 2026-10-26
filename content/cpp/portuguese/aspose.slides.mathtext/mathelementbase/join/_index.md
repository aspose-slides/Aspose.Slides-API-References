---
title: Join()
second_title: Aspose.Slides para C++ Referência da API
description: Une um elemento matemático e forma um bloco matemático
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) método


Une um elemento matemático e forma um bloco matemático

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O elemento a ser unido |

### Valor de Retorno

Um novo [IMathBlock](../../imathblock/) contendo esta instância e o argumento especificado
## Observações



Exemplo: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) método


Une um texto matemático e forma um bloco matemático

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
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
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)