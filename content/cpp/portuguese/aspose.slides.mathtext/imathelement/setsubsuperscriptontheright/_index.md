---
title: SetSubSuperscriptOnTheRight()
second_title: Referência da API Aspose.Slides para C++
description: Cria subscrito e sobrescrito à direita
type: docs
weight: 105
url: /pt/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) método

Cria subscrito e sobrescrito à direita

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subscrito (índice inferior à direita) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Sobrescrito (índice superior à direita) |

### Valor de retorno

Novo elemento matemático do tipo [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Observações

Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) método

Cria subscrito e sobrescrito à direita

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscrito (índice inferior à direita) |
| superscript | [System::String](../../../system/string/) | Sobrescrito (índice superior à direita) |

### Valor de retorno

Novo elemento matemático do tipo [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Observações

Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)