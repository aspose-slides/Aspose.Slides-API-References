---
title: RequestCacheLevel
second_title: Referencia de la API de Aspose.Slides para C++
description: La enumeración describe la configuración de caché aplicable a cualquier WebRequest.
type: docs
weight: 27
url: /es/system.net.cache/requestcachelevel/
---
## RequestCacheLevel enumeración


La enumeración describe la configuración de caché aplicable a cualquier [WebRequest](../../system.net/webrequest/).

```cpp
enum class RequestCacheLevel
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Default | 0 | Cumple una solicitud de un recurso ya sea usando la copia en caché del recurso o enviando una solicitud del recurso al servidor. |
| BypassCache | 1 | Cumple una solicitud usando el servidor. No se toman entradas de la caché. |
| CacheOnly | 2 | Cumple una solicitud de un recurso solo desde la caché. Se lanzará WebException cuando un recurso no esté en la caché del cliente. |
| CacheIfAvailable | 3 | Cumple una solicitud de un recurso desde la caché si el recurso está disponible, de lo contrario envía una solicitud al servidor. |
| Revalidate | 4 | Usa una copia local del recurso si la marca de tiempo del cliente es la misma que la marca de tiempo del recurso en el servidor. De lo contrario, el recurso se descarga de un servidor. |
| Reload | 5 | Un recurso siempre se descarga del servidor. |
| NoCacheNoStore | 6 | Nunca cumple una solicitud usando recursos de la caché y no almacena recursos en caché. |

## Ver también

* Espacio de nombres [System::Net::Cache](../)
* Library [Aspose.Slides](../../)