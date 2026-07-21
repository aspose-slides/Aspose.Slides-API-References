---
title: CompareTo()
second_title: Справочник API Aspose.Slides для C++
description: Сравнивает два диапазона символов с заданными правилами сравнения строк.
type: docs
weight: 404
url: /ru/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) функция


Сравнивает два диапазона символов с заданными правилами сравнения строк.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The first character span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The second character span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The type of string comparison to perform |

### Возвращаемое значение

Отрицательное значение, если span < other, ноль если равны, положительное если span > other

## См. также

* Перечисление [StringComparison](../../system/stringcomparison/)
* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)