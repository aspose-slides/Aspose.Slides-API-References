---
title: GetCookieHeader()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve un encabezado HTTP que contiene las cookies asociadas a la URI especificada.
type: docs
weight: 170
url: /es/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) método


Devuelve un encabezado HTTP que contiene las cookies asociadas a la URI especificada.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Una URI para la que se construirá el nombre del encabezado. |

### Valor de retorno

Un encabezado HTTP que contiene las cookies asociadas a la URI especificada.

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) método


Devuelve un encabezado HTTP que contiene las cookies asociadas a la URI especificada.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Una URI para la que se construirá el nombre del encabezado. |
| optCookie2 | [String](../../../system/string/)\& | El parámetro de salida donde se asignará una cookie con la versión máxima soportada. |

### Valor de retorno

Un encabezado HTTP que contiene las cookies asociadas a la URI especificada.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [Uri](../../../system/uri/)
* Clase [CookieContainer](../)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)