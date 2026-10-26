---
title: SetSuperscript()
second_title: Referência da API Aspose.Slides para C++
description: Cria sobrescrito
type: docs
weight: 92
url: /pt/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) método

Cria sobrescrito

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Sobrescrito (índice superior à direita) |

### Valor de Retorno

Novo elemento matemático do tipo [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Observações



Exemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) método


Cria sobrescrito

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Sobrescrito (índice superior à direita) |

### Valor de Retorno

Novo elemento matemático do tipo [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Observações



Exemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)