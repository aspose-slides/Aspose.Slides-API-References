---
title: SetSuperscript()
second_title: Referência da API Aspose.Slides para C++
description: Cria sobrescrito
type: docs
weight: 79
url: /pt/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) método


Creates superscript

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Superscript (upper index on the right) |

### Valor de Retorno

Novo elemento matemático do tipo [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Observações



Example: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) método


Creates superscript

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Superscript (upper index on the right) |

### Valor de Retorno

Novo elemento matemático do tipo [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Observações



Example: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMathSuperscriptElement](../../imathsuperscriptelement/)
* classe [IMathElement](../../imathelement/)
* classe [MathElementBase](../)
* classe [String](../../../system/string/)
* namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)