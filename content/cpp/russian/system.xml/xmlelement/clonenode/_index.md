---
title: CloneNode()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт дубликат этого узла.
type: docs
weight: 196
url: /ru/system.xml/xmlelement/clonenode/
---
## XmlElement::CloneNode(bool) метод

Создаёт дубликат этого узла.

```cpp
SharedPtr<XmlNode> System::Xml::XmlElement::CloneNode(bool deep) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | **bool** | **true** для рекурсивного клонирования поддерева под указанным узлом; **false** для клонирования только самого узла (и его атрибутов, если узел является [XmlElement](../)). |

## Возвращаемое значение

Клон узла.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlElement](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)