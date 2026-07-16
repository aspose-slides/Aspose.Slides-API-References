---
title: WebProxy()
second_title: Référence API Aspose.Slides pour C++
description: Construit une nouvelle instance.
type: docs
weight: 131
url: /fr/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() constructeur


Construit une nouvelle instance.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) constructeur


Construit une nouvelle instance.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'adresse du serveur proxy. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) constructeur


Construit une nouvelle instance.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'adresse du serveur proxy. |
| BypassOnLocal | **bool** | Une valeur indiquant si le serveur proxy doit être utilisé pour les adresses locales. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) constructeur


Construit une nouvelle instance.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'adresse du serveur proxy. |
| BypassOnLocal | **bool** | Une valeur indiquant si le serveur proxy doit être utilisé pour les adresses locales. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | La liste des adresses qui n'utilisent pas le serveur proxy. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) constructeur


Construit une nouvelle instance.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'adresse du serveur proxy. |
| BypassOnLocal | **bool** | Une valeur indiquant si le serveur proxy doit être utilisé pour les adresses locales. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | La liste des adresses qui n'utilisent pas le serveur proxy. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Les informations d'identification envoyées au serveur proxy pour l'authentification. |

## WebProxy::WebProxy(String, int32_t) constructeur


Construit une nouvelle instance.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| Host | [String](../../../system/string/) | Le nom d'hôte. |
| Port | **int32_t** | Le numéro de port. |

## WebProxy::WebProxy(String) constructeur


Construit une nouvelle instance.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | L'adresse du serveur proxy. |

## WebProxy::WebProxy(String, bool) constructeur


Construit une nouvelle instance.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | L'adresse du serveur proxy. |
| BypassOnLocal | **bool** | Une valeur indiquant si le serveur proxy doit être utilisé pour les adresses locales. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) constructeur


Construit une nouvelle instance.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | L'adresse du serveur proxy. |
| BypassOnLocal | **bool** | Une valeur indiquant si le serveur proxy doit être utilisé pour les adresses locales. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | La liste des adresses qui n'utilisent pas le serveur proxy. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) constructeur


Construit une nouvelle instance.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | L'adresse du serveur proxy. |
| BypassOnLocal | **bool** | Une valeur indiquant si le serveur proxy doit être utilisé pour les adresses locales. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | La liste des adresses qui n'utilisent pas le serveur proxy. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Les informations d'identification envoyées au serveur proxy pour l'authentification. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [WebProxy](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../../icredentials/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)