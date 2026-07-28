---
title: WebProxy()
second_title: Aspose.Slides for C++ API Referencia
description: Új példányt hoz létre.
type: docs
weight: 131
url: /hu/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() konstruktor

Új példányt hoz létre.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) konstruktor

Új példányt hoz létre.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | A proxykiszolgáló címe. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) konstruktor

Új példányt hoz létre.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | A proxykiszolgáló címe. |
| BypassOnLocal | **bool** | Egy érték, amely jelzi, hogy a proxykiszolgálót helyi címekhez kell-e használni. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) konstruktor

Új példányt hoz létre.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | A proxykiszolgáló címe. |
| BypassOnLocal | **bool** | Egy érték, amely jelzi, hogy a proxykiszolgálót helyi címekhez kell-e használni. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Az a címek listája, amelyek nem használják a proxykiszolgálót. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) konstruktor

Új példányt hoz létre.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | A proxykiszolgáló címe. |
| BypassOnLocal | **bool** | Egy érték, amely jelzi, hogy a proxykiszolgálót helyi címekhez kell-e használni. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Az a címek listája, amelyek nem használják a proxykiszolgálót. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | A hitelesítő adatok, amelyeket a hitelesítéshez a proxykiszolgálónak küldenek. |

## WebProxy::WebProxy(String, int32_t) konstruktor

Új példányt hoz létre.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| Host | [String](../../../system/string/) | A gép neve. |
| Port | **int32_t** | A port száma. |

## WebProxy::WebProxy(String) konstruktor

Új példányt hoz létre.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| Address | [String](../../../system/string/) | A proxykiszolgáló címe. |

## WebProxy::WebProxy(String, bool) konstruktor

Új példányt hoz létre.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| Address | [String](../../../system/string/) | A proxykiszolgáló címe. |
| BypassOnLocal | **bool** | Egy érték, amely jelzi, hogy a proxykiszolgálót helyi címekhez kell-e használni. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) konstruktor

Új példányt hoz létre.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| Address | [String](../../../system/string/) | A proxykiszolgáló címe. |
| BypassOnLocal | **bool** | Egy érték, amely jelzi, hogy a proxykiszolgálót helyi címekhez kell-e használni. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Az a címek listája, amelyek nem használják a proxykiszolgálót. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) konstruktor

Új példányt hoz létre.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| Address | [String](../../../system/string/) | A proxykiszolgáló címe. |
| BypassOnLocal | **bool** | Egy érték, amely jelzi, hogy a proxykiszolgálót helyi címekhez kell-e használni. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Az a címek listája, amelyek nem használják a proxykiszolgálót. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | A hitelesítő adatok, amelyeket a hitelesítéshez a proxykiszolgálónak küldenek. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [WebProxy](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../../icredentials/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)