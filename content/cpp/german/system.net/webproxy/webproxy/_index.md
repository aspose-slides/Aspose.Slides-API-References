---
title: WebProxy()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt eine neue Instanz.
type: docs
weight: 131
url: /de/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Die Proxy-Serveradresse. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Die Proxy-Serveradresse. |
| BypassOnLocal | **bool** | Ein Wert, der angibt, ob der Proxy-Server für lokale Adressen verwendet werden muss. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Die Proxy-Serveradresse. |
| BypassOnLocal | **bool** | Ein Wert, der angibt, ob der Proxy-Server für lokale Adressen verwendet werden muss. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Die Liste von Adressen, die den Proxy-Server nicht verwenden. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Die Proxy-Serveradresse. |
| BypassOnLocal | **bool** | Ein Wert, der angibt, ob der Proxy-Server für lokale Adressen verwendet werden muss. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Die Liste von Adressen, die den Proxy-Server nicht verwenden. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Die Anmeldeinformationen, die zur Authentifizierung an den Proxy-Server gesendet werden. |

## WebProxy::WebProxy(String, int32_t) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Host | [String](../../../system/string/) | Der Hostname. |
| Port | **int32_t** | Die Portnummer. |

## WebProxy::WebProxy(String) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Die Proxy-Serveradresse. |

## WebProxy::WebProxy(String, bool) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Die Proxy-Serveradresse. |
| BypassOnLocal | **bool** | Ein Wert, der angibt, ob der Proxy-Server für lokale Adressen verwendet werden muss. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Die Proxy-Serveradresse. |
| BypassOnLocal | **bool** | Ein Wert, der angibt, ob der Proxy-Server für lokale Adressen verwendet werden muss. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Die Liste von Adressen, die den Proxy-Server nicht verwenden. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Die Proxy-Serveradresse. |
| BypassOnLocal | **bool** | Ein Wert, der angibt, ob der Proxy-Server für lokale Adressen verwendet werden muss. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Die Liste von Adressen, die den Proxy-Server nicht verwenden. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Die Anmeldeinformationen, die zur Authentifizierung an den Proxy-Server gesendet werden. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [WebProxy](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../../icredentials/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)