---
title: SetSubSuperscriptOnTheLeft()
second_title: Referência da API Aspose.Slides para C++
description: Cria subscrito e sobrescrito à esquerda
type: docs
weight: 118
url: /pt/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) método


Cria subscrito e sobrescrito à esquerda

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subscrito (índice inferior à esquerda) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Sobrescrito (índice superior à esquerda) |

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

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) método


Cria subscrito e sobrescrito à esquerda

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
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
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)