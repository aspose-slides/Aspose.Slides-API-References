---
title: GetMember()
second_title: Aspose.Slides для C++ API Reference
description: Получает список членов с указанным именем.
type: docs
weight: 495
url: /ru/system/typeinfo/getmember/
---
## TypeInfo::GetMember(const String\&) const метод

Получает список членов с указанным именем.

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::GetMember(const String &name) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../string/)\& | Имя члена, который нужно получить. |

### Возвращаемое значение

[Array](../../array/) дескрипторов членов (пусто, если член не найден).

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Класс [MemberInfo](../../../system.reflection/memberinfo/)
* Класс [String](../../string/)
* Класс [TypeInfo](../)
* Пространство имён [System](../../)
* Library [Aspose.Slides](../../../)