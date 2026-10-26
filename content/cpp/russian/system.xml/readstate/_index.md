---
title: ReadState
second_title: Aspose.Slides для C++ справочник API
description: Указывает состояние считывателя.
type: docs
weight: 703
url: /ru/system.xml/readstate/
---
## ReadState перечисление

Указывает состояние считывателя.

```cpp
enum class ReadState
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Initial | 0 | Метод [XmlReader::Read](../xmlreader/read/) не был вызван. |
| Interactive | 1 | Метод [XmlReader::Read](../xmlreader/read/) был вызван. Дополнительные методы могут быть вызваны у считывателя. |
| Error | 2 | Произошла ошибка, препятствующая продолжению операции чтения. |
| EndOfFile | 3 | Конец файла успешно достигнут. |
| Closed | 4 | Метод [XmlReader::Close](../xmlreader/close/) был вызван. |

## См. также

* Пространство имен [System::Xml](../)
* Библиотека [Aspose.Slides](../../)