---
title: Add()
second_title: Aspose.Slides для C++ API Reference
description: Добавляет cookie в коллекцию.
type: docs
weight: 105
url: /ru/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) метод


Добавляет cookie в коллекцию.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Cookie для добавления. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) метод


Добавляет cookie в коллекцию.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Cookie для добавления. |
| throwOnError | **bool** | Значение, указывающее, будет ли выброшено исключение при возникновении ошибки. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) метод


Копирует cookie из указанной коллекции в текущую.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Коллекция, из которой будут скопированы cookie. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) метод


Добавляет cookie для указанного URI.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI cookie. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Cookie для добавления. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) метод


Копирует cookie из указанной коллекции для указанного URI в текущую коллекцию.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI cookie. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Коллекция cookie, из которой необходимо скопировать cookie. |

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [Cookie](../../cookie/)
* Класс [CookieContainer](../)
* Класс [CookieCollection](../../cookiecollection/)
* Класс [Uri](../../../system/uri/)
* Пространство имен [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)