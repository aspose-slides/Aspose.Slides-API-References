---
title: GetApplicationResourceStream()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve un flujo de recurso de aplicación a partir del URI especificado.
type: docs
weight: 1
url: /es/system.xml/iapplicationresourcestreamresolver/getapplicationresourcestream/
---
## IApplicationResourceStreamResolver::GetApplicationResourceStream(SharedPtr\<Uri\>) método


Devuelve un flujo de recurso de aplicación desde el URI especificado.

```cpp
virtual SharedPtr<IO::Stream> System::Xml::IApplicationResourceStreamResolver::GetApplicationResourceStream(SharedPtr<Uri> relativeUri)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| relativeUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | El URI relativo. |

### Valor devuelto

Un flujo de recurso de aplicación.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Stream](../../../system.io/stream/)
* Clase [Uri](../../../system/uri/)
* Clase [IApplicationResourceStreamResolver](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)