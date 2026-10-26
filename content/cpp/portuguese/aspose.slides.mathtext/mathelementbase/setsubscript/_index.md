---
title: SetSubscript()
second_title: Referência da API Aspose.Slides para C++
description: Cria subscrito
type: docs
weight: 66
url: /pt/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) método


Cria subscrito

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Subscript (lower index on the right) |

### Valor de retorno

Novo elemento matemático do tipo [IMathSubscriptElement](../../imathsubscriptelement/)
## Observações



Exemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) método


Cria subscrito

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscript (lower index on the right) |

### Valor de retorno

Novo elemento matemático do tipo [IMathSubscriptElement](../../imathsubscriptelement/)
## Observações



Exemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathSubscriptElement](../../imathsubscriptelement/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)