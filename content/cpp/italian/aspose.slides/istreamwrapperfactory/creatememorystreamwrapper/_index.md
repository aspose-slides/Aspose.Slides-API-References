---
title: CreateMemoryStreamWrapper()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un wrapper MemoryStream.
type: docs
weight: 1
url: /it/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() method

Crea un wrapper MemoryStream.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```

### Valore di ritorno

Wrapper stream per l'interfaccia COM [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) method

Crea un wrapper MemoryStream basato sull'array di byte specificato.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array di byte **uint8_t**[] |

### Valore di ritorno

Wrapper stream per l'interfaccia COM [IStreamWrapper](../../istreamwrapper/)

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IStreamWrapper](../../istreamwrapper/)
* Classe [IStreamWrapperFactory](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)