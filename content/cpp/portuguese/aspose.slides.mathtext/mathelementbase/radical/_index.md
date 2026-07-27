---
title: Radical()
second_title: Referência da API do Aspose.Slides para C++
description: Especifica a raiz matemática do grau fornecido a partir do argumento especificado.
type: docs
weight: 118
url: /pt/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) método

Especifica a raiz matemática do grau fornecido a partir do argumento especificado.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argumento do Radical |

### Valor de Retorno

Nova instância do tipo [IMathRadical](../../imathradical/)

## Observações



Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) método

Especifica a raiz matemática do grau fornecido a partir do argumento especificado.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argumento do Radical |

### Valor de Retorno

Nova instância do tipo [IMathRadical](../../imathradical/)

## Observações



Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathRadical](../../imathradical/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)