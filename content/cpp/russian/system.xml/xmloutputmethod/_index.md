---
title: XmlOutputMethod
second_title: Aspose.Slides для C++ справочник API
description: Указывает метод, используемый для сериализации вывода XmlWriter.
type: docs
weight: 846
url: /ru/system.xml/xmloutputmethod/
---
## XmlOutputMethod enum

Указывает метод, используемый для сериализации вывода [XmlWriter](../xmlwriter/).

```cpp
enum class XmlOutputMethod
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Xml | 0 | Сериализовать согласно правилам XML 1.0. |
| Html | 1 | Сериализовать согласно правилам HTML, указанным XSLT. |
| Text | 2 | Сериализовать только текстовые блоки. |
| AutoDetect | 3 | Использовать правила XSLT для выбора между методами вывода [XmlOutputMethod::Xml](./) и [XmlOutputMethod::Html](./) во время выполнения. |

## См. также

* Пространство имён [System::Xml](../)
* Библиотека [Aspose.Slides](../../)