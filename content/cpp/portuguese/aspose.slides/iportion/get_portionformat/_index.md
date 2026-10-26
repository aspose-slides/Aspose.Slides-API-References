---
title: get_PortionFormat()
second_title: Referência da API Aspose.Slides para C++
description: Retorna objeto de formatação que contém propriedades de formatação definidas explicitamente da porção de texto sem herança aplicada. Somente leitura IPortionFormat.
type: docs
weight: 1
url: /pt/aspose.slides/iportion/get_portionformat/
---
## IPortion::get_PortionFormat() método

Retorna objeto de formatação que contém propriedades de formatação definidas explicitamente da porção de texto sem herança aplicada. Somente leitura [IPortionFormat](../../iportionformat/).

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::IPortion::get_PortionFormat()=0
```

## Observações

O objeto de formatação contém os parâmetros de formatação definidos apenas para a porção atual, dados herdados não são aplicados.

Para obter os valores efetivos, incluindo os herdados, use o método [IPortionFormat::GetEffective](../../iportionformat/geteffective/).

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPortionFormat](../../iportionformat/)
* Classe [IPortion](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)