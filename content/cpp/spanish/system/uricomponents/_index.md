---
title: UriComponents
second_title: Referencia de API de Aspose.Slides para C++
description: Representa los componentes de URI.
type: docs
weight: 3251
url: /es/system/uricomponents/
---
## UriComponents enum

Representa los componentes de URI.

```cpp
enum class UriComponents
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Scheme | 1 | Los datos de Scheme. |
| UserInfo | 2 | Los datos de UserInfo. |
| Host | 4 | Los datos de Host. |
| Port | 8 | Los datos de Port. |
| SchemeAndServer | n/a | Los datos de Scheme, Host y Port. |
| Path | 16 | Los datos de LocalPath. |
| Query | 32 | Los datos de Query. |
| PathAndQuery | n/a | Los datos de LocalPath y Query. |
| HttpRequestUrl | n/a | Los datos de Scheme, Host, Port, Query y LocalPath. |
| Fragment | 64 | Los datos de Fragment. |
| AbsoluteUri | n/a | Los datos de Scheme, Host, Port, Quer, LocalPath y Fragment. |
| StrongPort | 128 | Los datos de Port; si los datos de puerto no están presentes en el [Uri](../uri/) y se ha asignado un puerto predeterminado al Scheme, se devuelve el puerto predeterminado; si no hay puerto predeterminado, se devuelve -1. |
| HostAndPort | n/a | Los datos de Host y Port; si los datos de puerto no están presentes en el [Uri](../uri/) y se ha asignado un puerto predeterminado al Scheme, se devuelve el puerto predeterminado. Si no hay puerto predeterminado, se devuelve -1. |
| StrongAuthority | n/a | Los datos de UserInfo, Host y Port. Si no hay datos de puerto en el [Uri](../uri/) y se ha asignado un puerto predeterminado al Scheme, se devuelve el puerto predeterminado. Si no hay puerto predeterminado, se devuelve -1. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Especifica que el delimitador debe incluirse. |
| SerializationInfoString | n/a | El contexto completo de [Uri](../uri/) que se necesita para los Serializers de [Uri](../uri/). El contexto incluye el alcance IPv6. |

## Véase también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)