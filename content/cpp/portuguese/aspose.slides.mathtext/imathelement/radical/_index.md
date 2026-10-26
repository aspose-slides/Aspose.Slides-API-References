---
title: Radical()
second_title: Aspose.Slides para C++ Referência da API
description: Especifica a raiz matemática do grau fornecido a partir do argumento especificado.
type: docs
weight: 131
url: /pt/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) método


Especifica a raiz matemática do grau fornecido a partir do argumento especificado.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argument of Radical |

### Valor de Retorno

Nova instância do tipo [IMathRadical](../../imathradical/)
## Observações



Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) método


Especifica a raiz matemática do grau fornecido a partir do argumento especificado.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argument of Radical |

### Valor de Retorno

Nova instância do tipo [IMathRadical](../../imathradical/)
## Observações



Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathRadical](../../imathradical/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)