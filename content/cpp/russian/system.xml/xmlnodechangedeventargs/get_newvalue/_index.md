---
title: get_NewValue()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает новое значение узла.
type: docs
weight: 66
url: /ru/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() метод


Возвращает новое значение узла.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```


### Возвращаемое значение

Новое значение узла. Этот метод возвращает **nullptr**, если узел не является ни атрибутом, ни текстовым узлом, или если узел удаляется. Если вызвать в событии **XmlDocument::NodeChanging**, **get_NewValue** возвращает значение узла, если изменение успешно. Если вызвать в событии **XmlDocument::NodeChanged**, **get_NewValue** возвращает текущее значение узла.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlNodeChangedEventArgs](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)