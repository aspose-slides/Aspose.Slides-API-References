---
title: SetAttribute()
second_title: Справка по API Aspose.Slides для C++
description: Устанавливает значение атрибута с указанным именем.
type: docs
weight: 222
url: /ru/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) метод

Устанавливает значение атрибута с указанным именем.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя атрибута, который нужно создать или изменить. Это квалифицированное имя. Если имя содержит двоеточие, оно разбивается на префикс и локальное имя. |
| value | [String](../../../system/string/) | Значение, которое следует установить для атрибута. |

## XmlElement::SetAttribute(String, String, String) метод

Устанавливает значение атрибута с указанным локальным именем и URI пространства имён.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя атрибута. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён атрибута. |
| value | [String](../../../system/string/) | Значение, которое следует установить для атрибута. |

### Возвращаемое значение

Значение атрибута.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlElement](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)