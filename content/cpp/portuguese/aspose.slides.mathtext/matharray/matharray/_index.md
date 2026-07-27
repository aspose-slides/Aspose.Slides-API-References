---
title: MathArray()
second_title: Aspose.Slides para C++ Referência da API
description: Cria um array matemático e coloca o elemento especificado nele
type: docs
weight: 144
url: /pt/aspose.slides.mathtext/matharray/matharray/
---
## MathArray::MathArray(System::SharedPtr\<IMathElement\>) construtor


Cria um array matemático e coloca o elemento especificado nele

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<IMathElement> element)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O elemento a ser colocado no array |
## Observações



Exemplo: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
```

## MathArray::MathArray(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) construtor


Cria um array matemático e coloca os elementos especificados nele

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> elements)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| elements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Elementos a serem colocados no array |

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathArray](../)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)