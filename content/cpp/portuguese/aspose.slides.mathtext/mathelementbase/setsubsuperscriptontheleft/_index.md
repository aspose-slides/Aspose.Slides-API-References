---
title: SetSubSuperscriptOnTheLeft()
second_title: Referência da API Aspose.Slides para C++
description: Cria subscrito e sobrescrito à esquerda
type: docs
weight: 105
url: /pt/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

Cria subscrito e sobrescrito à esquerda

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Subscrito (índice inferior à esquerda) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Sobrescrito (índice superior à esquerda) |

### Valor de Retorno

Novo elemento matemático do tipo [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Observações



Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) method

Cria subscrito e sobrescrito à esquerda

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscrito (índice inferior à esquerda) |
| superscript | [System::String](../../../system/string/) | Sobrescrito (índice superior à esquerda) |

### Valor de Retorno

Novo elemento matemático do tipo [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Observações



Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)