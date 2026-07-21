---
title: get_OldValue()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает исходное значение узла.
type: docs
weight: 53
url: /ru/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() метод

Возвращает исходное значение узла.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```

### Возвращаемое значение

Исходное значение узла. Этот метод возвращает **nullptr**, если узел не является ни атрибутом, ни текстовым узлом, или если узел вставляется. Если вызвать в событии **XmlDocument::NodeChanging**, **get_OldValue** возвращает текущее значение узла, которое будет заменено, если изменение будет выполнено успешно. Если вызвать в событии **XmlDocument::NodeChanged**, **get_OldValue** возвращает значение узла до изменения.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlNodeChangedEventArgs](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)