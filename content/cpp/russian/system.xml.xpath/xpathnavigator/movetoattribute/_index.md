---
title: MoveToAttribute()
second_title: Справочник API Aspose.Slides для C++
description: Перемещает XPathNavigator к атрибуту с совпадающим локальным именем и URI пространства имён.
type: docs
weight: 495
url: /ru/system.xml.xpath/xpathnavigator/movetoattribute/
---
## XPathNavigator::MoveToAttribute(String, String) метод


Перемещает [XPathNavigator](../) к атрибуту с совпадающим локальным именем и URI пространства имён.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToAttribute(String localName, String namespaceURI)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя атрибута. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён атрибута; **nullptr** для пустого пространства имён. |

### Возвращаемое значение

**true** если [XPathNavigator](../) успешно переместился к атрибуту; иначе **false**. Если **false**, позиция [XPathNavigator](../) остаётся неизменной.

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [XPathNavigator](../)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)