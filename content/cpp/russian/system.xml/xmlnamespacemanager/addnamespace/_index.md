---
title: AddNamespace()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет указанное пространство имен в коллекцию.
type: docs
weight: 66
url: /ru/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) метод

Добавляет указанное пространство имен в коллекцию.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Префикс, который будет связан с добавляемым пространством имен. Используйте [String::Empty](../../../system/string/empty/) для добавления пространства имен по умолчанию. Если [XmlNamespaceManager](../) будет использоваться для разрешения пространств имен в выражении XML Path Language ([XPath](../../../system.xml.xpath/)), необходимо указать префикс. Если в выражении [XPath](../../../system.xml.xpath/) не указан префикс, считается, что URI пространства имен является пустым пространством имен. Для получения дополнительной информации о выражениях [XPath](../../../system.xml.xpath/) и [XmlNamespaceManager](../) обратитесь к методам XmlNode::SelectNodes(String) и XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) methods. |
| uri | [String](../../../system/string/) | Пространство имен, которое необходимо добавить. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlNamespaceManager](../)
* Пространство имен [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)