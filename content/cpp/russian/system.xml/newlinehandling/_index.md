---
title: NewLineHandling
second_title: Aspose.Slides для C++ справка по API
description: Указывает, как обрабатывать разрывы строк.
type: docs
weight: 690
url: /ru/system.xml/newlinehandling/
---
## Перечисление NewLineHandling


Указывает, как обрабатывать разрывы строк.

```cpp
enum class NewLineHandling
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Replace | 0 | Символы новой строки заменяются, чтобы соответствовать символу, указанному в значении [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/). |
| Entitize | 1 | Символы новой строки энтифицируются. Эта настройка сохраняет все символы, когда вывод читается нормализующим [XmlReader](../xmlreader/). |
| None | 2 | Символы новой строки остаются без изменений. Вывод совпадает с вводом. |

## См. также

* Пространство имён [System::Xml](../)
* Библиотека [Aspose.Slides](../../)