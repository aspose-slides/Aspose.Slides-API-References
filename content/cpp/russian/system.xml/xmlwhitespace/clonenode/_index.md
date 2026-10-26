---
title: CloneNode()
second_title: Aspose.Slides для справки API C++
description: Создаёт дубликат этого узла.
type: docs
weight: 79
url: /ru/system.xml/xmlwhitespace/clonenode/
---
## XmlWhitespace::CloneNode(bool) метод

Создаёт дубликат этого узла.

```cpp
SharedPtr<XmlNode> System::Xml::XmlWhitespace::CloneNode(bool deep) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | **bool** | **true** для рекурсивного клонирования поддерева под указанным узлом; **false** для клонирования только самого узла. Для узлов пробельных символов клонированный узел всегда включает значение данных, независимо от настройки параметра. |

### Возвращаемое значение

Клонированный узел.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlWhitespace](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)