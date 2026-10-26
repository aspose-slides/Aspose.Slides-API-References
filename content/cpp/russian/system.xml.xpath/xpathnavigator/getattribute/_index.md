---
title: GetAttribute()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает значение атрибута с указанным локальным именем и URI пространства имён.
type: docs
weight: 482
url: /ru/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) метод


Возвращает значение атрибута с указанным локальным именем и URI пространства имён.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя атрибута. **localName** чувствителен к регистру. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён атрибута. |

### Возвращаемое значение

Объект [String](../../../system/string/), содержащий значение указанного атрибута; [String::Empty](../../../system/string/empty/), если соответствующий атрибут не найден, или если [XPathNavigator](../) не находится на узле-элементе.

## См. также

* Класс [String](../../../system/string/)
* Класс [XPathNavigator](../)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)