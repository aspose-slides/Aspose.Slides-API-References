---
title: LookupNamespace()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает URI пространства имён для указанного префикса.
type: docs
weight: 404
url: /ru/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) method


Возвращает URI пространства имён для указанного префикса.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Префикс, чей URI пространства имён вы хотите разрешить. Чтобы соответствовать пространству имён по умолчанию, передайте [String::Empty](../../../system/string/empty/). |

### Возвращаемое значение

Объект [String](../../../system/string/), содержащий URI пространства имён, назначенный указанному префиксу; **nullptr**, если для указанного префикса не назначен URI пространства имён. Возвращаемый [String](../../../system/string/) атомизирован.

## См. также

* Класс [String](../../../system/string/)
* Класс [XPathNavigator](../)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)