---
title: CompareOptions
second_title: Справка API Aspose.Slides для C++
description: Параметры сравнения строк.
type: docs
weight: 430
url: /ru/system.globalization/compareoptions/
---
## CompareOptions enum


[String](../../system/string/) параметры сравнения.

```cpp
enum class CompareOptions : int32_t
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Нет специальных параметров. |
| IgnoreCase | 1 | Игнорировать регистр. |
| IgnoreNonSpace | 2 | Игнорировать неразделяющие комбинирующие символы, например диакритические знаки. |
| IgnoreSymbols | 4 | Включать пробелы, знаки пунктуации и т. д. |
| IgnoreKanaType | 8 | Игнорировать тип каны (японский). |
| IgnoreWidth | 16 | Игнорировать ширину символов при сравнении строк. |
| OrdinalIgnoreCase | 268435456 | Порядковое сравнение без учёта регистра. |
| StringSort | 536870912 | Использовать алгоритм сортировки строк для сравнения символов. |
| Ordinal | 1073741824 | Сравнивать коды UTF напрямую для первого сравнения. |

## См. также

* Namespace [System::Globalization](../)
* Library [Aspose.Slides](../../)