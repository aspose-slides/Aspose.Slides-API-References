---
title: SpecifyKind()
second_title: Aspose.Slides для C++ справочника API
description: Создаёт новый объект DateTime, представляющий то же количество тиков, что и указанный объект DateTime, и представляющий местное время, время UTC или ни то ни другое, как указано в аргументе kind.
type: docs
weight: 833
url: /ru/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) метод

Создаёт новый объект [DateTime](../), представляющий то же количество тиков, что и указанный объект [DateTime](../), и представляющий местное время, время UTC или ни то ни другое, как указано в аргументе **kind**.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DateTime](../) | Объект [DateTime](../), из которого копируется количество тиков |
| kind | [DateTimeKind](../../datetimekind/) | Указывает, должно ли новый объект представлять местное время, время UTC или ни то ни другое. |

## Возвращаемое значение

Новый объект [DateTime](../), представляющий то же количество тиков, что и **value**, и значение DateTimeKind, указанное в **kind**.

## См. также

* Перечисление [DateTimeKind](../../datetimekind/)
* Класс [DateTime](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)