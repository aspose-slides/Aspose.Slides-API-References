---
title: CreatePortion()
second_title: Referência da API Aspose.Slides for C++
description: Cria uma porção de texto vazia.
type: docs
weight: 1
url: /pt/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() método


Cria uma porção de texto vazia.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```


### Valor de Retorno

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) método


Cria uma porção de texto a partir da string especificada.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### Valor de Retorno

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) método


Cria uma porção usando dados de porção especificados.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Uma porção a ser usada. |

### Valor de Retorno

[Portion](../../portion/).

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPortion](../../iportion/)
* Classe [IPortionFactory](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)