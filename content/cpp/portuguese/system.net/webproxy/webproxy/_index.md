---
title: WebProxy()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância.
type: docs
weight: 131
url: /pt/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() construtor

Constrói uma nova instância.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) construtor

Constrói uma nova instância.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O endereço do servidor proxy. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) construtor

Constrói uma nova instância.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O endereço do servidor proxy. |
| BypassOnLocal | **bool** | Um valor que indica se o servidor proxy deve ser usado para endereços locais. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) construtor

Constrói uma nova instância.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O endereço do servidor proxy. |
| BypassOnLocal | **bool** | Um valor que indica se o servidor proxy deve ser usado para endereços locais. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | A lista de endereços que não usam o servidor proxy. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) construtor

Constrói uma nova instância.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O endereço do servidor proxy. |
| BypassOnLocal | **bool** | Um valor que indica se o servidor proxy deve ser usado para endereços locais. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | A lista de endereços que não usam o servidor proxy. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | As credenciais enviadas ao servidor proxy para autenticação. |

## WebProxy::WebProxy(String, int32_t) construtor

Constrói uma nova instância.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| Host | [String](../../../system/string/) | O nome do host. |
| Port | **int32_t** | O número da porta. |

## WebProxy::WebProxy(String) construtor

Constrói uma nova instância.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| Address | [String](../../../system/string/) | O endereço do servidor proxy. |

## WebProxy::WebProxy(String, bool) construtor

Constrói uma nova instância.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| Address | [String](../../../system/string/) | O endereço do servidor proxy. |
| BypassOnLocal | **bool** | Um valor que indica se o servidor proxy deve ser usado para endereços locais. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) construtor

Constrói uma nova instância.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| Address | [String](../../../system/string/) | O endereço do servidor proxy. |
| BypassOnLocal | **bool** | Um valor que indica se o servidor proxy deve ser usado para endereços locais. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | A lista de endereços que não usam o servidor proxy. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) construtor

Constrói uma nova instância.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| Address | [String](../../../system/string/) | O endereço do servidor proxy. |
| BypassOnLocal | **bool** | Um valor que indica se o servidor proxy deve ser usado para endereços locais. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | A lista de endereços que não usam o servidor proxy. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | As credenciais enviadas ao servidor proxy para autenticação. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [WebProxy](../)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [ICredentials](../../icredentials/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)