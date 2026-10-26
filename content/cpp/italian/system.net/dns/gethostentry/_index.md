---
title: GetHostEntry()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una nuova istanza della classe IPHostEntry utilizzando la stringa specificata che contiene un nome host o un indirizzo IP.
type: docs
weight: 79
url: /it/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) metodo

Crea una nuova istanza della classe IPHostEntry utilizzando la stringa specificata che contiene un nome host o un indirizzo IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Una stringa che contiene un nome host o un indirizzo IP. |

### Valore restituito

Una nuova istanza della classe IPHostEntry.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) metodo

Crea una nuova istanza della classe IPHostEntry utilizzando l'indirizzo IP specificato.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | L'indirizzo IP. |

### Valore restituito

Una nuova istanza della classe IPHostEntry.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPHostEntry](../../iphostentry/)
* Classe [String](../../../system/string/)
* Classe [Dns](../)
* Classe [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)