---
title: HttpRequestCacheLevel
second_title: Referencia de API de Aspose.Slides para C++
description: El enum describe la configuración de caché para HTTP.
type: docs
weight: 40
url: /es/system.net.cache/httprequestcachelevel/
---
## enum HttpRequestCacheLevel

El enum describe la configuración de caché para HTTP.

```cpp
enum class HttpRequestCacheLevel
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Default | 0 | Satisface una solicitud de un recurso ya sea usando la copia en caché del recurso o enviando una solicitud del recurso al servidor. |
| BypassCache | 1 | Satisface una solicitud usando el servidor. |
| CacheOnly | 2 | Siempre usa la caché del cliente para obtener un recurso. |
| CacheIfAvailable | 3 | Satisface una solicitud de un recurso desde la caché si el recurso está disponible, de lo contrario envía una solicitud al servidor. |
| Revalidate | 4 | Usa una copia local del recurso si la marca de tiempo del cliente es la misma que la marca de tiempo del recurso en el servidor. De lo contrario, el recurso se descarga desde un servidor. |
| Reload | 5 | Un recurso siempre se descarga del servidor. |
| NoCacheNoStore | 6 | Nunca satisface una solicitud usando recursos de la caché y no almacena recursos en caché. |
| CacheOrNextCacheOnly | 7 | Satisface una solicitud de un recurso ya sea desde la caché del equipo local o desde una caché remota en la LAN. |
| Refresh | 8 | Satisface una solicitud usando el servidor o una caché distinta a la caché local. |

## Ver también

* Espacio de nombres [System::Net::Cache](../)
* Biblioteca [Aspose.Slides](../../)