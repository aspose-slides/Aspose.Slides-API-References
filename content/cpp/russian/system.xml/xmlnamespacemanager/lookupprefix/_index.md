---
title: LookupPrefix()
second_title: Aspose.Slides для справочника API C++
description: Находит префикс, объявленный для указанного URI пространства имён.
type: docs
weight: 131
url: /ru/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix(const String\&) метод

Находит префикс, объявленный для указанного URI пространства имён.

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Пространство имён, которое нужно разрешить для префикса. |

### Возвращаемое значение

Соответствующий префикс. Если соответствующий префикс не найден, метод возвращает [String::Empty](../../../system/string/empty/). Если передано нулевое значение, возвращается **nullptr**.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlNamespaceManager](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)