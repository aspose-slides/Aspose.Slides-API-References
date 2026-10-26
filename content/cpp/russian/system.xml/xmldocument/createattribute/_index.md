---
title: CreateAttribute()
second_title: Aspose.Slides для C++ API Справочник
description: Создает XmlAttribute с указанным именем.
type: docs
weight: 274
url: /ru/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) метод

Создаёт [XmlAttribute](../../xmlattribute/) с указанным именем.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Квалифицированное имя атрибута. Если имя содержит двоеточие, значение [XmlNode::get_Prefix](../../xmlnode/get_prefix/) отражает часть имени, предшествующую первому двоеточию, а значение [XmlDocument::get_LocalName](../get_localname/) — часть имени, следующую за первым двоеточием. [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) остаётся пустым, если только префикс не является распознанным встроенным префиксом, таким как **xmlns**. В этом случае get_NamespaceURI имеет значение [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Возвращаемое значение

Новый [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&) метод

Создаёт [XmlAttribute](../../xmlattribute/) с указанным квалифицированным именем и [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Квалифицированное имя атрибута. Если имя содержит двоеточие, значение [XmlNode::get_Prefix](../../xmlnode/get_prefix/) будет отражать часть имени, предшествующую двоеточию, а значение [XmlDocument::get_LocalName](../get_localname/) — часть имени после двоеточия. |
| namespaceURI | const [String](../../../system/string/)\& | NamespaceURI атрибута. Если квалифицированное имя включает префикс **xmlns**, то этот параметр должен быть [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Возвращаемое значение

Новый [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) метод

Создаёт [XmlAttribute](../../xmlattribute/) с указанными [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) и [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Префикс атрибута (если есть). [String::Empty](../../../system/string/empty/) и **nullptr** эквивалентны. |
| localName | const [String](../../../system/string/)\& | Локальное имя атрибута. |
| namespaceURI | const [String](../../../system/string/)\& | URI пространства имён атрибута (если есть). [String::Empty](../../../system/string/empty/) и **nullptr** эквивалентны. Если **prefix** является **xmlns**, то этот параметр должен быть [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;), иначе генерируется исключение. |

### Возвращаемое значение

Новый [XmlAttribute](../../xmlattribute/).

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)