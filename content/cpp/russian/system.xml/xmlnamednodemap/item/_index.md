---
title: Item()
second_title: Справочник API Aspose.Slides для C++
description: Получает узел с указанным индексом в XmlNamedNodeMap.
type: docs
weight: 53
url: /ru/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) метод


Получает узел с указанным индексом в [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция индекса узла, который нужно получить из [XmlNamedNodeMap](../). Индекс начинается с нуля; поэтому индекс первого узла равен 0, а индекс последнего узла составляет [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### Возвращаемое значение

[XmlNode](../../xmlnode/) по указанному индексу. Если **index** меньше 0 или больше либо равен значению [XmlNamedNodeMap::get_Count](../get_count/), возвращается **nullptr**.

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlNamedNodeMap](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)