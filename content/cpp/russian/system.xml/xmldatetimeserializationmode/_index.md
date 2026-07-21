---
title: XmlDateTimeSerializationMode
second_title: Справочник API Aspose.Slides для C++
description: Указывает, как обрабатывать значение времени при преобразовании между строкой и DateTime.
type: docs
weight: 781
url: /ru/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum

Указывает, как обрабатывать значение времени при преобразовании между строкой и [DateTime](../../system/datetime/).

```cpp
enum class XmlDateTimeSerializationMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Local | 0 | Обрабатывается как локальное время. Если объект [DateTime](../../system/datetime/) представляет всемирное координированное время (UTC), он преобразуется в локальное время. |
| Utc | 1 | Обрабатывается как UTC. Если объект [DateTime](../../system/datetime/) представляет локальное время, он преобразуется в UTC. |
| Unspecified | 2 | Обрабатывается как локальное время, если [DateTime](../../system/datetime/) преобразуется в строку. Если строка преобразуется в [DateTime](../../system/datetime/), преобразуйте в локальное время, если указан часовой пояс. |
| RoundtripKind | 3 | Информация о часовом поясе должна сохраняться при преобразовании. |

## См. также

* Пространство имён [System::Xml](../)
* Библиотека [Aspose.Slides](../../)