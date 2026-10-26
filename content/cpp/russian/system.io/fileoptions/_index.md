---
title: FileOptions
second_title: Справочник API Aspose.Slides для C++
description: Представляет расширенные параметры для создания объекта FileStream.
type: docs
weight: 521
url: /ru/system.io/fileoptions/
---
## FileOptions enum

Представляет расширенные параметры для создания [FileStream](../filestream/) object.

```cpp
enum class FileOptions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Нет дополнительных параметров. |
| Encrypted | 16384 | Файл зашифрован. НЕ РЕАЛИЗОВАНО. |
| DeleteOnClose | 67108864 | Файл должен быть автоматически удалён, когда больше не используется. |
| SequentialScan | 134217728 | Файл должен быть доступен последовательно. |
| RandomAccess | 268435456 | Файл доступен случайным образом. |
| Asynchronous | 1073741824 | Файл может использоваться для асинхронных операций ввода-вывода. |
| WriteThrough | n/a | Все записи должны записываться напрямую на диск, обходя любой промежуточный кэш. |

## See Also

* Пространство имён [System::IO](../)
* Библиотека [Aspose.Slides](../../)