---
title: ReadOnly()
second_title: Справочник API Aspose.Slides для C++
description: Получает версию форматтера только для чтения.
type: docs
weight: 807
url: /ru/system.globalization/numberformatinfo/readonly/
---
## NumberFormatInfo::ReadOnly(NumberFormatInfoPtr) метод


Получает только для чтения версию форматтера.

```cpp
static NumberFormatInfoPtr System::Globalization::NumberFormatInfo::ReadOnly(NumberFormatInfoPtr nfi)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| nfi | [NumberFormatInfoPtr](../../numberformatinfoptr/) | Форматтер, для которого требуется получить только для чтения версию. |

### Возвращаемое значение

Если **nfi** только для чтения, возвращает его; в противном случае создаёт его копию и помечает её как только для чтения.

## См. также

* Typedef [NumberFormatInfoPtr](../../numberformatinfoptr/)
* Класс [NumberFormatInfo](../)
* Пространство имён [System::Globalization](../../)
* Библиотека [Aspose.Slides](../../../)