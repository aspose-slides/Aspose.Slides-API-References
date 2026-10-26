---
title: WebProxy()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza.
type: docs
weight: 131
url: /it/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() costruttore


Crea una nuova istanza.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) costruttore


Crea una nuova istanza.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'indirizzo del server proxy. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) costruttore


Crea una nuova istanza.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'indirizzo del server proxy. |
| BypassOnLocal | **bool** | Un valore che indica se il server proxy deve essere usato per gli indirizzi locali. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) costruttore


Crea una nuova istanza.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'indirizzo del server proxy. |
| BypassOnLocal | **bool** | Un valore che indica se il server proxy deve essere usato per gli indirizzi locali. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | L'elenco degli indirizzi che non usano il server proxy. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) costruttore


Crea una nuova istanza.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'indirizzo del server proxy. |
| BypassOnLocal | **bool** | Un valore che indica se il server proxy deve essere usato per gli indirizzi locali. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | L'elenco degli indirizzi che non usano il server proxy. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Le credenziali inviate al server proxy per l'autenticazione. |

## WebProxy::WebProxy(String, int32_t) costruttore


Crea una nuova istanza.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| Host | [String](../../../system/string/) | Il nome host. |
| Port | **int32_t** | Il numero di porta. |

## WebProxy::WebProxy(String) costruttore


Crea una nuova istanza.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| Address | [String](../../../system/string/) | L'indirizzo del server proxy. |

## WebProxy::WebProxy(String, bool) costruttore


Crea una nuova istanza.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| Address | [String](../../../system/string/) | L'indirizzo del server proxy. |
| BypassOnLocal | **bool** | Un valore che indica se il server proxy deve essere usato per gli indirizzi locali. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) costruttore


Crea una nuova istanza.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| Address | [String](../../../system/string/) | L'indirizzo del server proxy. |
| BypassOnLocal | **bool** | Un valore che indica se il server proxy deve essere usato per gli indirizzi locali. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | L'elenco degli indirizzi che non usano il server proxy. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) costruttore


Crea una nuova istanza.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| Address | [String](../../../system/string/) | L'indirizzo del server proxy. |
| BypassOnLocal | **bool** | Un valore che indica se il server proxy deve essere usato per gli indirizzi locali. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | L'elenco degli indirizzi che non usano il server proxy. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Le credenziali inviate al server proxy per l'autenticazione. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [WebProxy](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../../icredentials/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)