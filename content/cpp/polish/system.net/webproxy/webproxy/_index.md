---
title: WebProxy()
second_title: Aspose.Slides for C++ – Referencja API
description: Tworzy nową instancję.
type: docs
weight: 131
url: /pl/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() konstruktor


Tworzy nową instancję.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) konstruktor


Tworzy nową instancję.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Adres serwera proxy. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) konstruktor


Tworzy nową instancję.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Adres serwera proxy. |
| BypassOnLocal | **bool** | Wartość określająca, czy serwer proxy ma być używany dla lokalnych adresów. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) konstruktor


Tworzy nową instancję.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Adres serwera proxy. |
| BypassOnLocal | **bool** | Wartość określająca, czy serwer proxy ma być używany dla lokalnych adresów. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Lista adresów, które nie używają serwera proxy. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) konstruktor


Tworzy nową instancję.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Adres serwera proxy. |
| BypassOnLocal | **bool** | Wartość określająca, czy serwer proxy ma być używany dla lokalnych adresów. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Lista adresów, które nie używają serwera proxy. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Poświadczenia wysyłane do serwera proxy w celu uwierzytelnienia. |

## WebProxy::WebProxy(String, int32_t) konstruktor


Tworzy nową instancję.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| Host | [String](../../../system/string/) | Nazwa hosta. |
| Port | **int32_t** | Numer portu. |

## WebProxy::WebProxy(String) konstruktor


Tworzy nową instancję.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Adres serwera proxy. |

## WebProxy::WebProxy(String, bool) konstruktor


Tworzy nową instancję.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Adres serwera proxy. |
| BypassOnLocal | **bool** | Wartość określająca, czy serwer proxy ma być używany dla lokalnych adresów. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) konstruktor


Tworzy nową instancję.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Adres serwera proxy. |
| BypassOnLocal | **bool** | Wartość określająca, czy serwer proxy ma być używany dla lokalnych adresów. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Lista adresów, które nie używają serwera proxy. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) konstruktor


Tworzy nową instancję.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Adres serwera proxy. |
| BypassOnLocal | **bool** | Wartość określająca, czy serwer proxy ma być używany dla lokalnych adresów. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Lista adresów, które nie używają serwera proxy. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Poświadczenia wysyłane do serwera proxy w celu uwierzytelnienia. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [WebProxy](../)
* Klasa [Uri](../../../system/uri/)
* Klasa [String](../../../system/string/)
* Klasa [ICredentials](../../icredentials/)
* Przestrzeń nazw [System::Net](../../)
* Library [Aspose.Slides](../../../)