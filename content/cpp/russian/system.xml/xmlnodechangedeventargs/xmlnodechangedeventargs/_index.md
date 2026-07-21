---
title: XmlNodeChangedEventArgs()
second_title: Справочник API Aspose.Slides для C++
description: Инициализирует новый экземпляр класса XmlNodeChangedEventArgs.
type: docs
weight: 79
url: /ru/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) конструктор

Инициализирует новый экземпляр класса [XmlNodeChangedEventArgs](../).

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Объект [XmlNode](../../xmlnode/), сгенерировавший событие. |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Старый родитель [XmlNode](../../xmlnode/) объекта [XmlNode](../../xmlnode/), сгенерировавшего событие. |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Новый родитель [XmlNode](../../xmlnode/) объекта [XmlNode](../../xmlnode/), сгенерировавшего событие. |
| oldValue | const [String](../../../system/string/)\& | Старое значение [XmlNode](../../xmlnode/), сгенерировавшего событие. |
| newValue | const [String](../../../system/string/)\& | Новое значение [XmlNode](../../xmlnode/), сгенерировавшего событие. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | XmlNodeChangedAction. |

## Смотрите также

* Перечисление [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [String](../../../system/string/)
* Класс [XmlNodeChangedEventArgs](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)