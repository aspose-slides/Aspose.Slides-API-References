---
title: "System::Net::Cache"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 664
url: /fr/system.net.cache/
---
## Classes

| Class | Description |
| --- | --- |
| [HttpRequestCachePolicy](./httprequestcachepolicy/) | Politique de cache HTTP qui exprime la sémantique de mise en cache HTTP RFC2616. Les objets de cette classe ne doivent être alloués qu’à l’aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d’instance de ce type sur la pile ou à l’aide de l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des échecs d’assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu’argument. |
| [RequestCachePolicy](./requestcachepolicy/) | Politique de cache de requête commune utilisée pour la mise en cache de [Http](../system.net.http/), FTP, etc. Les objets de cette classe ne doivent être alloués qu’à l’aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d’instance de ce type sur la pile ou à l’aide de l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des échecs d’assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu’argument. |
## Énumérations

| Enum | Description |
| --- | --- |
| [RequestCacheLevel](./requestcachelevel/) | L’énumération décrit les paramètres de cache applicables à tout [WebRequest](../system.net/webrequest/). |
| [HttpRequestCacheLevel](./httprequestcachelevel/) | L’énumération décrit les paramètres de cache pour HTTP. |
| [HttpCacheAgeControl](./httpcacheagecontrol/) | CacheAgeControl est utilisé pour spécifier les préférences concernant l’âge et la fraîcheur des éléments mis en cache. |