---
title: DtdProcessing
second_title: Справочник API Aspose.Slides для C++
description: Указывает варианты обработки DTD. Перечисление DtdProcessing используется классом XmlReaderSettings.
type: docs
weight: 638
url: /ru/system.xml/dtdprocessing/
---
## DtdProcessing перечисление

Указывает варианты обработки DTD. Перечисление DtdProcessing используется классом [XmlReaderSettings](../xmlreadersettings/).

```cpp
enum class DtdProcessing
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Prohibit | 0 | Указывает, что при встрече DTD генерируется XmlException с сообщением, указывающим, что DTD запрещены. Это поведение по умолчанию. |
| Ignore | 1 | Приводит к игнорированию элемента DOCTYPE. Обработка DTD не происходит, и DTD/DOCTYPE теряется при выводе. |
| Parse | 2 | Используется для разбора DTD. |

## См. также

* Пространство имен [System::Xml](../)
* Библиотека [Aspose.Slides](../../)