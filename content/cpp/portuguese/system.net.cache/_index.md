---
title: "System::Net::Cache"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 664
url: /pt/system.net.cache/
---
## Classes

| Classe | Descrição |
| --- | --- |
| [HttpRequestCachePolicy](./httprequestcachepolicy/) | Política de cache HTTP que expressa a semântica de cache HTTP RFC2616. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-la a funções como argumento. |
| [RequestCachePolicy](./requestcachepolicy/) | Política de cache de requisição comum usada para o cache de [Http](../system.net.http/), FTP, etc. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-la a funções como argumento. |

## Enumerações

| Enumeração | Descrição |
| --- | --- |
| [RequestCacheLevel](./requestcachelevel/) | O enum descreve as configurações de cache aplicáveis a qualquer [WebRequest](../system.net/webrequest/). |
| [HttpRequestCacheLevel](./httprequestcachelevel/) | O enum descreve as configurações de cache para HTTP. |
| [HttpCacheAgeControl](./httpcacheagecontrol/) | CacheAgeControl é usado para especificar preferências relacionadas à idade e frescor dos itens em cache. |