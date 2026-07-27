---
title: PresentationLockingBehavior
second_title: Aspose.Slides para C++ Referência da API
description: "Representa o comportamento em relação ao tratamento da fonte IPresentation (arquivo ou System::IO::Stream) ao carregar e trabalhar com uma instância de IPresentation."
type: docs
weight: 6748
url: /pt/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum

Representa o comportamento em relação ao tratamento da fonte [IPresentation](../ipresentation/) (arquivo ou [System::IO::Stream](../../system.io/stream/)) ao carregar e trabalhar com uma instância de [IPresentation](../ipresentation/).

```cpp
enum class PresentationLockingBehavior
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| LoadAndRelease | 0 | A fonte será bloqueada apenas durante a execução do construtor [IPresentation](../ipresentation/). |
| KeepLocked | 1 | A fonte será bloqueada por toda a vida útil da instância [IPresentation](../ipresentation/), até que seja descartada. |

## Observações

A fonte é o parâmetro passado ao construtor [IPresentation](../ipresentation/). No exemplo abaixo, a fonte é o arquivo \"pres.pptx\":

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

Para este exemplo, a fonte (arquivo \"pres.pptx\") será bloqueada por toda a vida útil da instância [IPresentation](../ipresentation/), ou seja, não pode ser alterada ou excluída por outro processo.

## Veja Também

* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)