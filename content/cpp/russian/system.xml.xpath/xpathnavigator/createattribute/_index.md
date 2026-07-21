---
title: CreateAttribute()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт узел-атрибут в текущем узле-элементе, используя указанный префикс пространства имён, локальное имя и URI пространства имён, а также указанное значение.
type: docs
weight: 1041
url: /ru/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) метод

Создаёт узел-атрибут в текущем узле-элементе, используя указанный префикс пространства имён, локальное имя и URI пространства имён, а также указанное значение.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Префикс пространства имён нового узла-атрибута (если имеется). |
| localName | [String](../../../system/string/) | Локальное имя нового узла-атрибута, которое не может [String::Empty](../../../system/string/empty/) или **nullptr**. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён для нового узла-атрибута (если имеется). |
| value | [String](../../../system/string/) | Значение нового узла-атрибута. Если передано [String::Empty](../../../system/string/empty/) или **nullptr**, будет создан пустой узел-атрибут. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XPathNavigator](../)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)