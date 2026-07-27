---
title: SetSubSuperscriptOnTheRight()
second_title: Referência da API Aspose.Slides para C++
description: Cria subscrito e sobrescrito à direita
type: docs
weight: 92
url: /pt/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) método

Cria subscrito e sobrescrito à direita

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Subscrito (índice inferior à direita) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Sobrescrito (índice superior à direita) |

### Valor de Retorno

Novo elemento matemático do tipo [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)

## Observações



Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) método

Cria subscrito e sobrescrito à direita

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscrito (índice inferior à direita) |
| superscript | [System::String](../../../system/string/) | Sobrescrito (índice superior à direita) |

### Valor de Retorno

Novo elemento matemático do tipo [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)

## Observações



Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)