---
title: InsertElementBefore()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новый соседний элемент перед текущим узлом, используя указанные префикс пространства имён, локальное имя и URI пространства имён, с указанным значением.
type: docs
weight: 1015
url: /ru/system.xml.xpath/xpathnavigator/insertelementbefore/
---
## XPathNavigator::InsertElementBefore(String, String, String, String) method


Создаёт новый соседний элемент перед текущим узлом, используя указанные префикс пространства имён, локальное имя и URI пространства имён, с указанным значением.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementBefore(String prefix, String localName, String namespaceURI, String value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Префикс пространства имён нового дочернего элемента (если есть). |
| localName | [String](../../../system/string/) | Локальное имя нового дочернего элемента (если есть). |
| namespaceURI | [String](../../../system/string/) | URI пространства имён нового дочернего элемента (если есть). [String::Empty](../../../system/string/empty/) и **nullptr** равнозначны. |
| value | [String](../../../system/string/) | Значение нового дочернего элемента. Если переданы [String::Empty](../../../system/string/empty/) или **nullptr**, создаётся пустой элемент. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XPathNavigator](../)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)