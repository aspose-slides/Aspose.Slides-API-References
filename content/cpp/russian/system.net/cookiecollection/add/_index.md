---
title: Add()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет cookie в коллекцию.
type: docs
weight: 53
url: /ru/system.net/cookiecollection/add/
---
## CookieCollection::Add(const System::SharedPtr\<Cookie\>\&) метод

Добавляет cookie в коллекцию.

```cpp
void System::Net::CookieCollection::Add(const System::SharedPtr<Cookie> &cookie) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cookie | const [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\>\& | Cookie, который нужно добавить. |

## CookieCollection::Add(System::SharedPtr\<CookieCollection\>) метод

Добавляет cookies из указанной коллекции в текущую.

```cpp
void System::Net::CookieCollection::Add(System::SharedPtr<CookieCollection> cookies)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../)\> | Коллекция, из которой cookies будут скопированы в текущую. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieCollection](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)