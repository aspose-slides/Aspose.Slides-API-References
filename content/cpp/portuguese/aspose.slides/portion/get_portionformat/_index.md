---
title: get_PortionFormat()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um objeto de formatação que contém as propriedades de formatação definidas explicitamente da porção de texto, sem herança aplicada. Somente leitura IPortionFormat.
type: docs
weight: 1
url: /pt/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() método

Retorna um objeto de formatação que contém as propriedades de formatação definidas explicitamente da porção de texto, sem herança aplicada. Somente leitura [IPortionFormat](../../iportionformat/).

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## Observações

O objeto de formatação contém os parâmetros de formatação definidos apenas para a porção atual; os dados herdados não são aplicados.

Para obter os valores efetivos, incluindo os herdados, use o método [PortionFormat::GetEffective](../../portionformat/geteffective/).

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IPortionFormat](../../iportionformat/)
* classe [Portion](../)
* espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)