---
title: GetNamespacesInScope()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает коллекцию имен пространств имён, индексированных префиксом, которые можно использовать для перечисления пространств имён, находящихся в текущей области видимости.
type: docs
weight: 105
url: /ru/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope) метод

Возвращает коллекцию имен пространств имён, индексированных префиксом, которые можно использовать для перечисления пространств имён, находящихся в текущей области видимости.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Перечислимое значение, которое определяет тип узлов пространства имён, которые следует вернуть. |

### Возвращаемое значение

Коллекция пар пространств имён и префиксов, находящихся в текущей области видимости.

## См. также

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)