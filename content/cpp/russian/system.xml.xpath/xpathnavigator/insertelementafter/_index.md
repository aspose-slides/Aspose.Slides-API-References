---
title: InsertElementAfter()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый элемент-сосед после текущего узла, используя указанные префикс пространства имён, локальное имя и URI пространства имён, со указанным значением.
type: docs
weight: 1028
url: /ru/system.xml.xpath/xpathnavigator/insertelementafter/
---
## XPathNavigator::InsertElementAfter(String, String, String, String) метод

Создает новый элемент-сосед после текущего узла, используя указанные префикс пространства имён, локальное имя и URI пространства имён, со значением, указанным.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementAfter(String prefix, String localName, String namespaceURI, String value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Префикс пространства имён нового дочернего элемента (если есть). |
| localName | [String](../../../system/string/) | Локальное имя нового дочернего элемента (если есть). |
| namespaceURI | [String](../../../system/string/) | URI пространства имён нового дочернего элемента (если есть). [String::Empty](../../../system/string/empty/) и **nullptr** эквивалентны. |
| value | [String](../../../system/string/) | Значение нового дочернего элемента. Если передан [String::Empty](../../../system/string/empty/) или **nullptr**, создаётся пустой элемент. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XPathNavigator](../)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)