---
title: WebProxy()
second_title: Aspose.Slides pro C++ - reference API
description: Vytvoří novou instanci.
type: docs
weight: 131
url: /cs/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() konstruktor

Vytvoří novou instanci.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Adresa proxy serveru. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Adresa proxy serveru. |
| BypassOnLocal | **bool** | Hodnota, která určuje, zda má být proxy server použit pro lokální adresy. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Adresa proxy serveru. |
| BypassOnLocal | **bool** | Hodnota, která určuje, zda má být proxy server použit pro lokální adresy. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Seznam adres, které nepoužívají proxy server. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Adresa proxy serveru. |
| BypassOnLocal | **bool** | Hodnota, která určuje, zda má být proxy server použit pro lokální adresy. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Seznam adres, které nepoužívají proxy server. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Přihlašovací údaje odesílané na proxy server pro ověření. |

## WebProxy::WebProxy(String, int32_t) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| Host | [String](../../../system/string/) | Název hostitele. |
| Port | **int32_t** | Číslo portu. |

## WebProxy::WebProxy(String) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Adresa proxy serveru. |

## WebProxy::WebProxy(String, bool) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Adresa proxy serveru. |
| BypassOnLocal | **bool** | Hodnota, která určuje, zda má být proxy server použit pro lokální adresy. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Adresa proxy serveru. |
| BypassOnLocal | **bool** | Hodnota, která určuje, zda má být proxy server použit pro lokální adresy. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Seznam adres, které nepoužívají proxy server. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Adresa proxy serveru. |
| BypassOnLocal | **bool** | Hodnota, která určuje, zda má být proxy server použit pro lokální adresy. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Seznam adres, které nepoužívají proxy server. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Přihlašovací údaje odesílané na proxy server pro ověření. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [WebProxy](../)
* Třída [Uri](../../../system/uri/)
* Třída [String](../../../system/string/)
* Třída [ICredentials](../../icredentials/)
* Jmenný prostor [System::Net](../../)
* Library [Aspose.Slides](../../../)