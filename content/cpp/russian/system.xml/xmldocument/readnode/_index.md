---
title: ReadNode()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт объект XmlNode на основе информации из XmlReader. Читатель должен быть позиционирован на узле или атрибуте.
type: docs
weight: 495
url: /ru/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) метод


Создаёт объект [XmlNode](../../xmlnode/) на основе информации в [XmlReader](../../xmlreader/). Читатель должен быть позиционирован на узле или атрибуте.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Источник XML. |

### Возвращаемое значение

Новый [XmlNode](../../xmlnode/) или **nullptr**, если больше узлов не существует.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlReader](../../xmlreader/)
* Класс [XmlDocument](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)