---
title: GetHostByAddress()
second_title: Aspose.Slides per il riferimento API di C++
description: Crea una nuova istanza IPHostEntry-class usando la rappresentazione stringa specificata di un indirizzo IP.
type: docs
weight: 14
url: /it/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) method

Crea una nuova istanza IPHostEntry-class usando la rappresentazione stringa specificata di un indirizzo IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| address | [String](../../../system/string/) | La rappresentazione stringa di un indirizzo IP. |

### Valore di ritorno

Una nuova istanza IPHostEntry-class.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) method

Crea una nuova istanza IPHostEntry-class usando l'indirizzo IP specificato.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | L'indirizzo IP. |

### Valore di ritorno

Una nuova istanza IPHostEntry-class.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [String](../../../system/string/)
* Class [Dns](../)
* Class [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)