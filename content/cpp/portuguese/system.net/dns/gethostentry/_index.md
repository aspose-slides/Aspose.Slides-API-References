---
title: GetHostEntry()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova instância da classe IPHostEntry usando a string especificada que contém um nome de host ou endereço IP.
type: docs
weight: 79
url: /pt/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) método

Cria uma nova instância da classe IPHostEntry usando a string especificada que contém um nome de host ou endereço IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Uma string que contém um nome de host ou endereço IP. |

### Valor de Retorno

Uma instância recém-criada da classe IPHostEntry.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) método

Cria uma nova instância da classe IPHostEntry usando o endereço IP especificado.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | O endereço IP. |

### Valor de Retorno

Uma instância recém-criada da classe IPHostEntry.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPHostEntry](../../iphostentry/)
* Classe [String](../../../system/string/)
* Classe [Dns](../)
* Classe [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)