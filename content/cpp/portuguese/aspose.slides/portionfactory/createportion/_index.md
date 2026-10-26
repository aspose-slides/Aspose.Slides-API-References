---
title: CreatePortion()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma porção de texto vazia.
type: docs
weight: 1
url: /pt/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() método

Cria uma porção de texto vazia.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```

### Valor de Retorno

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) método

Cria uma porção de texto a partir da string especificada.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### Valor de Retorno

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) método

Cria uma porção usando os dados de uma porção especificada.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Uma porção a ser usada. |

### Valor de Retorno

[Portion](../../portion/).

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortion](../../iportion/)
* Class [PortionFactory](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)