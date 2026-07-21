---
title: idx_get()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает cookie из коллекции cookie по указанному индексу.
type: docs
weight: 40
url: /ru/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) метод

Возвращает cookie из коллекции cookie по указанному индексу.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс cookie, который необходимо вернуть. |

### Возвращаемое значение

Cookie по указанному индексу.

## CookieCollection::idx_get(String) метод

Возвращает cookie из коллекции cookie по указанному имени.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя cookie, которое необходимо вернуть. |

### Возвращаемое значение

Cookie из коллекции cookie по указанному имени, если найден, иначе nullptr.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Cookie](../../cookie/)
* Класс [CookieCollection](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)