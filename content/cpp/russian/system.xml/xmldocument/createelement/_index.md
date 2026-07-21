---
title: CreateElement()
second_title: Aspose.Slides для C++ справочник API
description: Создает элемент с указанным именем.
type: docs
weight: 339
url: /ru/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) метод


Создает элемент с указанным именем.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Полное имя элемента. Если имя содержит двоеточие, то значение [XmlNode::get_Prefix](../../xmlnode/get_prefix/) отражает часть имени до двоеточия, а значение [XmlDocument::get_LocalName](../get_localname/) — часть имени после двоеточия. Полное имя не может включать префикс **xmlns**. |

### Возвращаемое значение

Новый [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&) метод


Создает [XmlElement](../../xmlelement/) с полным именем и [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Полное имя элемента. Если имя содержит двоеточие, то значение [XmlNode::get_Prefix](../../xmlnode/get_prefix/) будет отражать часть имени до двоеточия, а значение [XmlDocument::get_LocalName](../get_localname/) — часть имени после двоеточия. Полное имя не может включать префикс **xmlns**. |
| namespaceURI | const [String](../../../system/string/)\& | URI пространства имен элемента. |

### Возвращаемое значение

Новый [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) метод


Создает элемент с указанными [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) и [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Префикс нового элемента (если есть). [String::Empty](../../../system/string/empty/) и **nullptr** эквивалентны. |
| localName | const [String](../../../system/string/)\& | Локальное имя нового элемента. |
| namespaceURI | const [String](../../../system/string/)\& | URI пространства имен нового элемента (если есть). [String::Empty](../../../system/string/empty/) и **nullptr** эквивалентны. |

### Возвращаемое значение

Новый [XmlElement](../../xmlelement/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlElement](../../xmlelement/)
* Класс [String](../../../system/string/)
* Класс [XmlDocument](../)
* Пространство имен [System::Xml](../../)
* Library [Aspose.Slides](../../../)