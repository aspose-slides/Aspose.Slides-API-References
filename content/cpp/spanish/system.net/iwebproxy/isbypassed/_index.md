---
title: IsBypassed()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve un valor que indica si el proxy no debe usarse para el host especificado.
type: docs
weight: 40
url: /es/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed(System::SharedPtr\<Uri\>) método


Devuelve un valor que indica si el proxy no debe usarse para el host especificado.

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | El URI del host a comprobar. |

### Valor devuelto

True cuando el servidor proxy no debe usarse, de lo contrario false.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [IWebProxy](../)
* Espacio de nombres [System::Net](../../)
* Library [Aspose.Slides](../../../)