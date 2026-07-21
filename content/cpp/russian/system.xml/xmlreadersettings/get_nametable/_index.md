---
title: get_NameTable()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает XmlNameTable, используемую для атомарных сравнений строк.
type: docs
weight: 1
url: /ru/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() метод

Возвращает [XmlNameTable](../../xmlnametable/), используемый для атомарных сравнений строк.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```

### Возвращаемое значение

Объект [XmlNameTable](../../xmlnametable/), который хранит все атомарные строки, используемые всеми экземплярами [XmlReader](../../xmlreader/), созданными с помощью этого объекта [XmlReaderSettings](../). Значение по умолчанию — **nullptr**. Созданный экземпляр [XmlReader](../../xmlreader/) будет использовать новый пустой [NameTable](../../nametable/), если это значение равно **nullptr**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNameTable](../../xmlnametable/)
* Класс [XmlReaderSettings](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)