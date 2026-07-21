---
title: WriteStartElement()
second_title: Aspose.Slides для C++ справочник API
description: Записывает указанный начальный тег и связывает его с заданным пространством имён и префиксом.
type: docs
weight: 235
url: /ru/system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement(const String\&, const String\&, const String\&) метод

Записывает указанный начальный тег и связывает его с указанным пространством имён и префиксом.

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Префикс пространства имён элемента. |
| localName | const [String](../../../system/string/)\& | Локальное имя элемента. |
| ns | const [String](../../../system/string/)\& | URI пространства имён, которое связывается с элементом. Если это пространство имён уже находится в области видимости и имеет связанный префикс, запись автоматически включает этот префикс. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlTextWriter](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)