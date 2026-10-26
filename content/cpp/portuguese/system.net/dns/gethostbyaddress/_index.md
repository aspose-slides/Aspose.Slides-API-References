---
title: GetHostByAddress()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova instância IPHostEntry-class usando a representação em string especificada de um endereço IP.
type: docs
weight: 14
url: /pt/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) método


Cria uma nova instância IPHostEntry-class usando a representação em string de um endereço IP especificado.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| address | [String](../../../system/string/) | A representação em string de um endereço IP. |

### Valor de Retorno

Uma nova instância IPHostEntry-class.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) método


Cria uma nova instância IPHostEntry-class usando o endereço IP especificado.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | O endereço IP. |

### Valor de Retorno

Uma nova instância IPHostEntry-class.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPHostEntry](../../iphostentry/)
* Classe [String](../../../system/string/)
* Classe [Dns](../)
* Classe [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)