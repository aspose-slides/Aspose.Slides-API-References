---
title: Join()
second_title: Referência da API Aspose.Slides para C++
description: Junta um elemento matemático a este bloco matemático
type: docs
weight: 183
url: /pt/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) método


Junta um elemento matemático a este bloco matemático

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O elemento a ser juntado |

### Valor de retorno

A instância atual de [IMathBlock](../../imathblock/)
## Observações



Exemplo: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) método


Junta um texto matemático a este bloco matemático

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Texto matemático a ser juntado |

### Valor de retorno

Um novo [IMathBlock](../../imathblock/) contendo esta instância e o argumento especificado
## Observações



Exemplo: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBlock](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)