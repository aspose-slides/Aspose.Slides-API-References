---
title: AppendChildElement()
second_title: Aspose.Slides для C++ справочника API
description: Создаёт новый узел дочернего элемента в конце списка дочерних узлов текущего узла, используя указанный префикс пространства имён, локальное имя и URI пространства имён со значением.
type: docs
weight: 1002
url: /ru/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) метод

Создаёт новый узел дочернего элемента в конце списка дочерних узлов текущего узла, используя указанные префикс пространства имён, локальное имя и URI пространства имён со значением.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Префикс пространства имён нового узла дочернего элемента (если имеется). |
| localName | [String](../../../system/string/) | Локальное имя нового узла дочернего элемента (если имеется). |
| namespaceURI | [String](../../../system/string/) | URI пространства имён нового узла дочернего элемента (если имеется). [String::Empty](../../../system/string/empty/) и **nullptr** эквивалентны. |
| value | [String](../../../system/string/) | Значение нового узла дочернего элемента. Если [String::Empty](../../../system/string/empty/) или **nullptr** переданы, создаётся пустой элемент. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XPathNavigator](../)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)