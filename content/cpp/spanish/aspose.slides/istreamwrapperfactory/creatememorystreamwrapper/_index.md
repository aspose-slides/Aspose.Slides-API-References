---
title: CreateMemoryStreamWrapper()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un envoltorio MemoryStream.
type: docs
weight: 1
url: /es/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() método

Crea un envoltorio MemoryStream.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```

### Valor de retorno

Envoltorio de flujo para la interfaz COM [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) método

Crea un envoltorio MemoryStream basado en la matriz de bytes especificada.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Matriz de bytes **uint8_t**[] |

### Valor de retorno

Envoltorio de flujo para la interfaz COM [IStreamWrapper](../../istreamwrapper/)

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [IStreamWrapper](../../istreamwrapper/)
* Clase [IStreamWrapperFactory](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)