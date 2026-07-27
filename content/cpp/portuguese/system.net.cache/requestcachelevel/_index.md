---
title: RequestCacheLevel
second_title: Aspose.Slides para Referência da API C++
description: O enum descreve as configurações de cache aplicáveis a qualquer WebRequest.
type: docs
weight: 27
url: /pt/system.net.cache/requestcachelevel/
---
## RequestCacheLevel enum

O enum descreve as configurações de cache aplicáveis a qualquer [WebRequest](../../system.net/webrequest/).

```cpp
enum class RequestCacheLevel
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Default | 0 | Atende a uma solicitação de recurso usando a cópia em cache do recurso ou enviando uma solicitação do recurso ao servidor. |
| BypassCache | 1 | Atende a uma solicitação usando o servidor. Nenhuma entrada é obtida do cache. |
| CacheOnly | 2 | Atende a uma solicitação de recurso somente a partir do cache. Uma WebException será lançada quando um recurso não estiver no cache do cliente. |
| CacheIfAvailable | 3 | Atende a uma solicitação de recurso a partir do cache se o recurso estiver disponível, caso contrário, envia uma solicitação ao servidor. |
| Revalidate | 4 | Usa uma cópia local do recurso se a marca de tempo do cliente for a mesma que a do recurso no servidor. Caso contrário, o recurso é baixado de um servidor. |
| Reload | 5 | Um recurso é sempre baixado do servidor. |
| NoCacheNoStore | 6 | Nunca atende a uma solicitação usando recursos do cache e não armazena recursos em cache. |

## Ver também

* Namespace [System::Net::Cache](../)
* Biblioteca [Aspose.Slides](../../)