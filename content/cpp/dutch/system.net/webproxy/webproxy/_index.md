---
title: WebProxy()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw exemplaar.
type: docs
weight: 131
url: /nl/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() constructor

Maakt een nieuw exemplaar.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) constructor

Maakt een nieuw exemplaar.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Het proxyserveradres. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) constructor

Maakt een nieuw exemplaar.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Het proxyserveradres. |
| BypassOnLocal | **bool** | Een waarde die aangeeft of de proxyserver moet worden gebruikt voor lokale adressen. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) constructor

Maakt een nieuw exemplaar.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Het proxyserveradres. |
| BypassOnLocal | **bool** | Een waarde die aangeeft of de proxyserver moet worden gebruikt voor lokale adressen. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | De lijst met adressen die de proxyserver niet gebruiken. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) constructor

Maakt een nieuw exemplaar.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Het proxyserveradres. |
| BypassOnLocal | **bool** | Een waarde die aangeeft of de proxyserver moet worden gebruikt voor lokale adressen. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | De lijst met adressen die de proxyserver niet gebruiken. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | De referenties die naar de proxyserver worden gestuurd voor authenticatie. |

## WebProxy::WebProxy(String, int32_t) constructor

Maakt een nieuw exemplaar.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| Host | [String](../../../system/string/) | De hostnaam. |
| Port | **int32_t** | Het poortnummer. |

## WebProxy::WebProxy(String) constructor

Maakt een nieuw exemplaar.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Het proxyserveradres. |

## WebProxy::WebProxy(String, bool) constructor

Maakt een nieuw exemplaar.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Het proxyserveradres. |
| BypassOnLocal | **bool** | Een waarde die aangeeft of de proxyserver moet worden gebruikt voor lokale adressen. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) constructor

Maakt een nieuw exemplaar.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Het proxyserveradres. |
| BypassOnLocal | **bool** | Een waarde die aangeeft of de proxyserver moet worden gebruikt voor lokale adressen. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | De lijst met adressen die de proxyserver niet gebruiken. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) constructor

Maakt een nieuw exemplaar.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Het proxyserveradres. |
| BypassOnLocal | **bool** | Een waarde die aangeeft of de proxyserver moet worden gebruikt voor lokale adressen. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | De lijst met adressen die de proxyserver niet gebruiken. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | De referenties die naar de proxyserver worden gestuurd voor authenticatie. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [WebProxy](../)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [ICredentials](../../icredentials/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)