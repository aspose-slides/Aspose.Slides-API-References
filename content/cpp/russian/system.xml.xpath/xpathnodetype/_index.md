---
title: XPathNodeType
second_title: Aspose.Slides для C++ справочник API
description: Определяет типы узлов XPath, которые могут быть возвращены классом XPathNavigator.
type: docs
weight: 157
url: /ru/system.xml.xpath/xpathnodetype/
---
## XPathNodeType перечисление

Определяет типы узлов [XPath](../), которые могут быть возвращены классом [XPathNavigator](../xpathnavigator/).

```cpp
enum class XPathNodeType
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Root | 0 | Корневой узел XML-документа или дерева узлов. |
| Element | 1 | Элемент, например **<element>**. |
| Attribute | 2 | Атрибут, например **id='123'**. |
| Namespace | 3 | Пространство имён, например **xmlns="namespace"**. |
| Text | 4 | Текстовое содержимое узла. Эквивалентно типам узлов Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) и CDATA. Содержит минимум один символ. |
| SignificantWhitespace | 5 | Узел, содержащий пробельные символы и с **xml:space**, установленным в **preserve**. |
| Whitespace | 6 | Узел, содержащий только пробельные символы и без значимых пробелов. Пробельные символы: **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | Инструкция обработки, например **<?pi test?>**. Не включает объявления XML, которые не видны классу [XPathNavigator](../xpathnavigator/). |
| Comment | 8 | Комментарий, например ****. |
| All | 9 | Любой из типов узлов XPathNodeType. |

## См. также

* Namespace [System::Xml::XPath](../)
* Library [Aspose.Slides](../../)