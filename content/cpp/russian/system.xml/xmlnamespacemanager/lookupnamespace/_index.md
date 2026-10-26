---
title: LookupNamespace()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает URI пространства имён для указанного префикса.
type: docs
weight: 118
url: /ru/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) метод

Возвращает URI пространства имён для указанного префикса.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Префикс, чей URI пространства имён необходимо разрешить. Чтобы соответствовать пространству имён по умолчанию, передайте [String::Empty](../../../system/string/empty/). |

### Возвращаемое значение

URI пространства имён для **prefix** или **nullptr**, если соответствующее пространство имён не найдено. Возвращаемая строка атомизирована. Для получения дополнительной информации об атомизированных строках см. класс [XmlNameTable](../../xmlnametable/).

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlNamespaceManager](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)