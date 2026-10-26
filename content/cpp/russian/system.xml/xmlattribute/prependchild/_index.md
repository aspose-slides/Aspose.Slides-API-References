---
title: PrependChild()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет указанный узел в начало списка дочерних узлов данного узла.
type: docs
weight: 261
url: /ru/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) метод

Добавляет указанный узел в начало списка дочерних узлов данного узла.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) для добавления. Если это [XmlDocumentFragment](../../xmldocumentfragment/), всё содержимое фрагмента документа перемещается в список дочерних узлов этого узла. |

### Возвращаемое значение

[XmlNode](../../xmlnode/) добавлен.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlAttribute](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)