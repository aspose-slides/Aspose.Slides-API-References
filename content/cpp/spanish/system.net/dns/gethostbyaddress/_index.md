---
title: GetHostByAddress()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una nueva instancia de la clase IPHostEntry-class usando la representación en cadena especificada de una dirección IP.
type: docs
weight: 14
url: /es/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) método

Crea una nueva instancia de la clase IPHostEntry-class usando la representación en cadena especificada de una dirección IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| address | [String](../../../system/string/) | La representación en cadena de una dirección IP. |

### Valor devuelto

Una nueva instancia de la clase IPHostEntry-class.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) método

Crea una nueva instancia de la clase IPHostEntry-class usando la dirección IP especificada.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | La dirección IP. |

### Valor devuelto

Una nueva instancia de la clase IPHostEntry-class.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPHostEntry](../../iphostentry/)
* Clase [String](../../../system/string/)
* Clase [Dns](../)
* Clase [IPAddress](../../ipaddress/)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)