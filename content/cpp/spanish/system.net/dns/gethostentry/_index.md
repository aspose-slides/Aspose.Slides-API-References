---
title: GetHostEntry()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una nueva instancia de la clase IPHostEntry utilizando la cadena especificada que contiene un nombre de host o una dirección IP.
type: docs
weight: 79
url: /es/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) método


Crea una nueva instancia de la clase IPHostEntry utilizando la cadena especificada que contiene un nombre de host o una dirección IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Una cadena que contiene un nombre de host o una dirección IP. |

### Valor devuelto

Una instancia de la clase IPHostEntry recién creada.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) método


Crea una nueva instancia de la clase IPHostEntry utilizando la dirección IP especificada.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | La dirección IP. |

### Valor devuelto

Una instancia de la clase IPHostEntry recién creada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPHostEntry](../../iphostentry/)
* Clase [String](../../../system/string/)
* Clase [Dns](../)
* Clase [IPAddress](../../ipaddress/)
* Espacio de nombres [System::Net](../../)
* Library [Aspose.Slides](../../../)