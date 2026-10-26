---
title: "System::Net::Cache"
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 664
url: /it/system.net.cache/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [HttpRequestCachePolicy](./httprequestcachepolicy/) | Policy di cache HTTP che esprime la semantica di caching HTTP secondo RFC2616. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché causerà errori di runtime e/o violazioni di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizza questo puntatore per passarla alle funzioni come argomento. |
| [RequestCachePolicy](./requestcachepolicy/) | Policy di cache per richieste comuni utilizzata per la memorizzazione nella cache di [Http](../system.net.http/), FTP, ecc. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché causerà errori di runtime e/o violazioni di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizza questo puntatore per passarla alle funzioni come argomento. |
## Enumerazioni

| Enum | Descrizione |
| --- | --- |
| [RequestCacheLevel](./requestcachelevel/) | L'enumerazione descrive le impostazioni di cache applicabili a qualsiasi [WebRequest](../system.net/webrequest/). |
| [HttpRequestCacheLevel](./httprequestcachelevel/) | L'enumerazione descrive le impostazioni di cache per HTTP. |
| [HttpCacheAgeControl](./httpcacheagecontrol/) | CacheAgeControl è usato per specificare le preferenze relative all'età e alla freschezza degli elementi in cache. |