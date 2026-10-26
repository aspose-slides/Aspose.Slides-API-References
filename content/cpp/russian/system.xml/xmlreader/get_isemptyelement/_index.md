---
title: get_IsEmptyElement()
second_title: Справочник API Aspose.Slides для C++
description: При переопределении в производном классе возвращает значение, указывающее, является ли текущий узел пустым элементом (например, <MyElement/>).
type: docs
weight: 131
url: /ru/system.xml/xmlreader/get_isemptyelement/
---
## XmlReader::get_IsEmptyElement() метод


При переопределении в производном классе возвращает значение, указывающее, является ли текущий узел пустым элементом (например, **<MyElement/>**).

```cpp
virtual bool System::Xml::XmlReader::get_IsEmptyElement()=0
```


### Возвращаемое значение

**true** если текущий узел является элементом ([XmlReader::get_NodeType](../get_nodetype/) равно [XmlNodeType::Element](../../xmlnodetype/)), который заканчивается на **/>**; в противном случае **false**.

## См. также

* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)