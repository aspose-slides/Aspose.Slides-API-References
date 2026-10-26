---
title: HttpRequestCacheLevel
second_title: Aspose.Slides para C++ Referência da API
description: O enum descreve as configurações de cache para HTTP.
type: docs
weight: 40
url: /pt/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel enum

O enum descreve as configurações de cache para HTTP.

```cpp
enum class HttpRequestCacheLevel
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | 0 | Atende a uma solicitação de recurso usando a cópia em cache do recurso ou enviando uma solicitação do recurso ao servidor. |
| BypassCache | 1 | Atende a uma solicitação usando o servidor. |
| CacheOnly | 2 | Sempre usa o cache do cliente para obter um recurso. |
| CacheIfAvailable | 3 | Atende a uma solicitação de recurso a partir do cache se o recurso estiver disponível; caso contrário, envia uma solicitação ao servidor. |
| Revalidate | 4 | Usa uma cópia local do recurso se a marca de tempo do cliente for a mesma que a marca de tempo do recurso no servidor. Caso contrário, o recurso é baixado de um servidor. |
| Reload | 5 | Um recurso é sempre baixado do servidor. |
| NoCacheNoStore | 6 | Nunca atende a uma solicitação usando recursos do cache e não armazena recursos em cache. |
| CacheOrNextCacheOnly | 7 | Atende a uma solicitação de recurso tanto a partir do cache do computador local quanto de um cache remoto na LAN. |
| Refresh | 8 | Atende a uma solicitação usando o servidor ou um cache diferente do cache local. |

## Veja Também

* Namespace [System::Net::Cache](../)
* Biblioteca [Aspose.Slides](../../)