---
title: WebProxy()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una nueva instancia.
type: docs
weight: 131
url: /es/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() constructor

Construye una nueva instancia.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) constructor

Construye una nueva instancia.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | La dirección del servidor proxy. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) constructor

Construye una nueva instancia.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | La dirección del servidor proxy. |
| BypassOnLocal | **bool** | Un valor que indica si el servidor proxy debe usarse para direcciones locales. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) constructor

Construye una nueva instancia.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | La dirección del servidor proxy. |
| BypassOnLocal | **bool** | Un valor que indica si el servidor proxy debe usarse para direcciones locales. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | La lista de direcciones que no usan el servidor proxy. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) constructor

Construye una nueva instancia.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | La dirección del servidor proxy. |
| BypassOnLocal | **bool** | Un valor que indica si el servidor proxy debe usarse para direcciones locales. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | La lista de direcciones que no usan el servidor proxy. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Las credenciales que se envían al servidor proxy para autenticación. |

## WebProxy::WebProxy(String, int32_t) constructor

Construye una nueva instancia.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| Host | [String](../../../system/string/) | El nombre del host. |
| Port | **int32_t** | El número del puerto. |

## WebProxy::WebProxy(String) constructor

Construye una nueva instancia.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| Address | [String](../../../system/string/) | La dirección del servidor proxy. |

## WebProxy::WebProxy(String, bool) constructor

Construye una nueva instancia.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| Address | [String](../../../system/string/) | La dirección del servidor proxy. |
| BypassOnLocal | **bool** | Un valor que indica si el servidor proxy debe usarse para direcciones locales. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) constructor

Construye una nueva instancia.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| Address | [String](../../../system/string/) | La dirección del servidor proxy. |
| BypassOnLocal | **bool** | Un valor que indica si el servidor proxy debe usarse para direcciones locales. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | La lista de direcciones que no usan el servidor proxy. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) constructor

Construye una nueva instancia.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| Address | [String](../../../system/string/) | La dirección del servidor proxy. |
| BypassOnLocal | **bool** | Un valor que indica si el servidor proxy debe usarse para direcciones locales. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | La lista de direcciones que no usan el servidor proxy. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Las credenciales que se envían al servidor proxy para autenticación. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [WebProxy](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../../icredentials/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)