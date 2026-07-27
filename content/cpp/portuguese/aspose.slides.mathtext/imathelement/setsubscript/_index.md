---
title: SetSubscript()
second_title: Referência da API Aspose.Slides para C++
description: Cria subscrito
type: docs
weight: 79
url: /pt/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) método

Cria subscrito

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subscrito (índice inferior à direita) |

### Valor de retorno

New math element of type [IMathSubscriptElement](../../imathsubscriptelement/)
## Observações



Exemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) método

Cria subscrito

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscrito (índice inferior à direita) |

### Valor de retorno

New math element of type [IMathSubscriptElement](../../imathsubscriptelement/)
## Observações



Exemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathSubscriptElement](../../imathsubscriptelement/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)