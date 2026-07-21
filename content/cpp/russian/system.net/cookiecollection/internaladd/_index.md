---
title: InternalAdd()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет указанную куку в коллекцию.
type: docs
weight: 118
url: /ru/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) метод

Добавляет указанную куку в коллекцию.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Кука для добавления. |
| isStrict | **bool** | Истина, когда указанная кука должна заменить старую, иначе ложь. |

### Возвращаемое значение

0, когда указанная кука заменила старую, иначе 1.

## См. также

* Типоопределение [SharedPtr](../../../system/sharedptr/)
* Класс [Cookie](../../cookie/)
* Класс [CookieCollection](../)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)