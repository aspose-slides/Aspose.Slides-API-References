---
title: LookupPrefix()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает префикс, объявленный для указанного URI пространства имён.
type: docs
weight: 417
url: /ru/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String\&) метод

Возвращает префикс, объявленный для указанного URI пространства имён.

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | URI пространства имён, для которого необходимо разрешить префикс. |

### Возвращаемое значение

Объект [String](../../../system/string/), содержащий префикс пространства имён, назначенный указанному URI пространства имён; в противном случае [String::Empty](../../../system/string/empty/), если префикс не назначен указанному URI пространства имён. Возвращаемый [String](../../../system/string/) атомизирован.

## См. также

* Класс [String](../../../system/string/)
* Класс [XPathNavigator](../)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)