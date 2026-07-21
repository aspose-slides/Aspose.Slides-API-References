---
title: WebProxy()
second_title: Aspose.Slides для C++ – справочник API
description: Создаёт новый экземпляр.
type: docs
weight: 131
url: /ru/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() конструктор

Создаёт новый экземпляр.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Адрес прокси-сервера. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Адрес прокси-сервера. |
| BypassOnLocal | **bool** | Значение, указывающее, должен ли прокси-сервер использоваться для локальных адресов. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Адрес прокси-сервера. |
| BypassOnLocal | **bool** | Значение, указывающее, должен ли прокси-сервер использоваться для локальных адресов. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Список адресов, которые не используют прокси-сервер. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Адрес прокси-сервера. |
| BypassOnLocal | **bool** | Значение, указывающее, должен ли прокси-сервер использоваться для локальных адресов. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Список адресов, которые не используют прокси-сервер. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Учётные данные, отправляемые прокси-серверу для аутентификации. |

## WebProxy::WebProxy(String, int32_t) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| Host | [String](../../../system/string/) | Имя хоста. |
| Port | **int32_t** | Номер порта. |

## WebProxy::WebProxy(String) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Адрес прокси-сервера. |

## WebProxy::WebProxy(String, bool) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Адрес прокси-сервера. |
| BypassOnLocal | **bool** | Значение, указывающее, должен ли прокси-сервер использоваться для локальных адресов. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Адрес прокси-сервера. |
| BypassOnLocal | **bool** | Значение, указывающее, должен ли прокси-сервер использоваться для локальных адресов. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Список адресов, которые не используют прокси-сервер. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Адрес прокси-сервера. |
| BypassOnLocal | **bool** | Значение, указывающее, должен ли прокси-сервер использоваться для локальных адресов. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Список адресов, которые не используют прокси-сервер. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Учётные данные, отправляемые прокси-серверу для аутентификации. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [WebProxy](../)
* Класс [Uri](../../../system/uri/)
* Класс [String](../../../system/string/)
* Класс [ICredentials](../../icredentials/)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)