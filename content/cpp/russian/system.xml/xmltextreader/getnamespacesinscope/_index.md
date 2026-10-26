---
title: GetNamespacesInScope()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает коллекцию, содержащую все пространства имён, находящиеся в текущей области видимости.
type: docs
weight: 716
url: /ru/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) метод

Возвращает коллекцию, содержащую все пространства имён, находящиеся в текущей области видимости.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Значение XmlNamespaceScope, которое указывает тип узлов пространств имён, которые следует вернуть. |

### Возвращаемое значение

Объект IDictionary, содержащий все текущие пространства имён в области видимости. Если читатель не находится на элементе, возвращается пустой словарь (без пространств имён).

## См. также

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)