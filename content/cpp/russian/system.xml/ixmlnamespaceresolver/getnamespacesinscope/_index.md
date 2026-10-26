---
title: GetNamespacesInScope()
second_title: Aspose.Slides для C++ - справочник API
description: Возвращает коллекцию определённых отображений префикс-пространство имён, которые в настоящее время находятся в области действия.
type: docs
weight: 1
url: /ru/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope) метод

Возвращает коллекцию определённых отображений префикс-пространство имён, которые в настоящее время находятся в области действия.

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Значение XmlNamespaceScope, которое указывает тип возвращаемых узлов пространства имён. |

### Возвращаемое значение

Коллекция IDictionary, содержащая текущие пространства имён в области действия.

## Смотрите также

* Перечисление [XmlNamespaceScope](../../xmlnamespacescope/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IDictionary](../../../system.collections.generic/idictionary/)
* Класс [String](../../../system/string/)
* Класс [IXmlNamespaceResolver](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)