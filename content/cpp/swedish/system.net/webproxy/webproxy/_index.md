---
title: WebProxy()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans.
type: docs
weight: 131
url: /sv/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() konstruktor


Skapar en ny instans.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) konstruktor


Skapar en ny instans.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Proxyserverns adress. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) konstruktor


Skapar en ny instans.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Proxyserverns adress. |
| BypassOnLocal | **bool** | Ett värde som indikerar om proxyservern ska användas för lokala adresser. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) konstruktor


Skapar en ny instans.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Proxyserverns adress. |
| BypassOnLocal | **bool** | Ett värde som indikerar om proxyservern ska användas för lokala adresser. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Listan med adresser som inte använder proxyservern. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) konstruktor


Skapar en ny instans.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Proxyserverns adress. |
| BypassOnLocal | **bool** | Ett värde som indikerar om proxyservern ska användas för lokala adresser. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Listan med adresser som inte använder proxyservern. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Autentiseringsuppgifterna som skickas till proxyservern för autentisering. |

## WebProxy::WebProxy(String, int32_t) konstruktor


Skapar en ny instans.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| Host | [String](../../../system/string/) | Värdnamnet. |
| Port | **int32_t** | Portnumret. |

## WebProxy::WebProxy(String) konstruktor


Skapar en ny instans.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Proxyserverns adress. |

## WebProxy::WebProxy(String, bool) konstruktor


Skapar en ny instans.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Proxyserverns adress. |
| BypassOnLocal | **bool** | Ett värde som indikerar om proxyservern ska användas för lokala adresser. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) konstruktor


Skapar en ny instans.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Proxyserverns adress. |
| BypassOnLocal | **bool** | Ett värde som indikerar om proxyservern ska användas för lokala adresser. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Listan med adresser som inte använder proxyservern. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) konstruktor


Skapar en ny instans.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Proxyserverns adress. |
| BypassOnLocal | **bool** | Ett värde som indikerar om proxyservern ska användas för lokala adresser. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Listan med adresser som inte använder proxyservern. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Autentiseringsuppgifterna som skickas till proxyservern för autentisering. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [WebProxy](../)
* Klass [Uri](../../../system/uri/)
* Klass [String](../../../system/string/)
* Klass [ICredentials](../../icredentials/)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)