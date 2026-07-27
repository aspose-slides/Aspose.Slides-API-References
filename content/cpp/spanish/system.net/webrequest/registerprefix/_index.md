---
title: RegisterPrefix()
second_title: Referencia de la API de Aspose.Slides para C++
description: Registra el descendente WebRequest para el URI especificado.
type: docs
weight: 92
url: /es/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) método


Registra el descendente [WebRequest](../) para el URI especificado.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | El URI o el prefijo del URI. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | Crea nuevas instancias de la clase [WebRequest](../). |

### Valor devuelto

True cuando el descendente [WebRequest](../) se registra correctamente para el URI especificado, de lo contrario false.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [IWebRequestCreate](../../iwebrequestcreate/)
* Clase [WebRequest](../)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)