---
title: PrependChildElement()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый дочерний элемент в начале списка дочерних узлов текущего узла, используя указанный префикс пространства имён, локальное имя и URI пространства имён со значением.
type: docs
weight: 989
url: /ru/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) метод

Создаёт новый дочерний элемент в начале списка дочерних узлов текущего узла, используя указанный префикс пространства имён, локальное имя и URI пространства имён со значением.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Префикс пространства имён нового дочернего элемента (если есть). |
| localName | [String](../../../system/string/) | Локальное имя нового дочернего элемента (если есть). |
| namespaceURI | [String](../../../system/string/) | URI пространства имён нового дочернего элемента (если есть). [String::Empty](../../../system/string/empty/) и **nullptr** эквивалентны. |
| value | [String](../../../system/string/) | Значение нового дочернего элемента. Если [String::Empty](../../../system/string/empty/) или **nullptr** переданы, создаётся пустой элемент. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XPathNavigator](../)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)