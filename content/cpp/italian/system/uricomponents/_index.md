---
title: UriComponents
second_title: Aspose.Slides per C++ Riferimento API
description: Rappresenta i componenti URI.
type: docs
weight: 3251
url: /it/system/uricomponents/
---
## UriComponents enum

Rappresenta i componenti URI.

```cpp
enum class UriComponents
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Scheme | 1 | I dati Scheme. |
| UserInfo | 2 | I dati UserInfo. |
| Host | 4 | I dati Host. |
| Port | 8 | I dati Port. |
| SchemeAndServer | n/a | I dati Scheme, Host e Port. |
| Path | 16 | I dati LocalPath. |
| Query | 32 | I dati Query. |
| PathAndQuery | n/a | I dati LocalPath e Query. |
| HttpRequestUrl | n/a | I dati Scheme, Host, Port, Query e LocalPath. |
| Fragment | 64 | I dati Fragment. |
| AbsoluteUri | n/a | I dati Scheme, Host, Port, Quer, LocalPath e Fragment. |
| StrongPort | 128 | I dati Port; se i dati della porta non sono presenti nel [Uri](../uri/) e una porta predefinita è stata assegnata al Scheme, viene restituita la porta predefinita; se non esiste una porta predefinita, viene restituito -1. |
| HostAndPort | n/a | I dati Host e Port; se i dati della porta non sono presenti nel [Uri](../uri/) e una porta predefinita è stata assegnata al Scheme, viene restituita la porta predefinita. Se non esiste una porta predefinita, viene restituito -1. |
| StrongAuthority | n/a | I dati UserInfo, Host e Port. Se nessun dato della porta è presente nel [Uri](../uri/) e una porta predefinita è stata assegnata al Scheme, viene restituita la porta predefinita. Se non esiste una porta predefinita, viene restituito -1. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Specificare che il delimitatore dovrebbe essere incluso. |
| SerializationInfoString | n/a | Il contesto completo [Uri](../uri/) necessario per i Serializzatori [Uri](../uri/). Il contesto include lo scope IPv6. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)