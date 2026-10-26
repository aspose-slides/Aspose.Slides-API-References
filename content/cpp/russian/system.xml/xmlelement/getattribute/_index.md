---
title: GetAttribute()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает значение атрибута с указанным именем.
type: docs
weight: 209
url: /ru/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) метод


Возвращает значение атрибута с указанным именем.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя атрибута для получения. Это квалифицированное имя. Оно сравнивается со значением **get_Name** соответствующего узла. |

### Возвращаемое значение

Значение указанного атрибута. Пустая строка возвращается, если соответствующий атрибут не найден или если атрибут не имеет указанного или значения по умолчанию.

## XmlElement::GetAttribute(String, String) метод


Возвращает значение атрибута с указанным локальным именем и URI пространства имён.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя атрибута для получения. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён атрибута для получения. |

### Возвращаемое значение

Значение указанного атрибута. Пустая строка возвращается, если соответствующий атрибут не найден или если атрибут не имеет указанного или значения по умолчанию.

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [XmlElement](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)