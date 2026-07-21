---
title: RegisterPrefix()
second_title: Справочник API Aspose.Slides для C++
description: Регистрирует потомка WebRequest для указанного URI.
type: docs
weight: 92
url: /ru/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) метод

Регистрирует [WebRequest](../) потомок для указанного URI.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | URI или префикс URI. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | Создаёт новые экземпляры класса [WebRequest](../). |

### Возвращаемое значение

True, если [WebRequest](../) потомок успешно зарегистрирован для указанного URI, иначе false.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [IWebRequestCreate](../../iwebrequestcreate/)
* Класс [WebRequest](../)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)