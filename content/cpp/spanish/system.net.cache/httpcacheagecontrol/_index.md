---
title: HttpCacheAgeControl
second_title: Referencia de API de Aspose.Slides para C++
description: CacheAgeControl se utiliza para especificar preferencias con respecto a la edad y frescura de los elementos en caché.
type: docs
weight: 53
url: /es/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enumeración

CacheAgeControl se utiliza para especificar preferencias con respecto a la edad y frescura de los elementos en caché.

```cpp
enum class HttpCacheAgeControl
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | 0 | Solo para uso interno. |
| MinFresh | 1 | El contenido puede obtenerse de la caché si el tiempo restante antes de la expiración es mayor o igual al tiempo especificado con este valor. |
| MaxAge | 2 | El contenido puede obtenerse de la caché hasta que sea más antiguo que la edad especificada con este valor. |
| MaxStale | 4 | El contenido puede obtenerse de la caché después de que haya expirado hasta que transcurra el tiempo especificado con este valor. |
| MaxAgeAndMinFresh | 3 | MaxAge y MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge y MaxStale. |

## Ver también

* Espacio de nombres [System::Net::Cache](../)
* Biblioteca [Aspose.Slides](../../)