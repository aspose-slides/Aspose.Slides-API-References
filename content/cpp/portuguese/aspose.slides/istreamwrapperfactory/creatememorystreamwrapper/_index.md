---
title: CreateMemoryStreamWrapper()
second_title: Referência da API Aspose.Slides para C++
description: Cria wrapper de MemoryStream.
type: docs
weight: 1
url: /pt/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() método

Cria wrapper de MemoryStream.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```

### Valor de retorno

Wrapper de fluxo para a interface COM [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) método

Cria wrapper de MemoryStream baseado no array de bytes especificado.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array de bytes **uint8_t**[] |

### Valor de retorno

Wrapper de fluxo para a interface COM [IStreamWrapper](../../istreamwrapper/)

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IStreamWrapper](../../istreamwrapper/)
* Classe [IStreamWrapperFactory](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)