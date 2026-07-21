---
title: CloneNode()
second_title: Aspose.Slides для C++ справка по API
description: Создаёт дубликат этого узла.
type: docs
weight: 157
url: /ru/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) метод


Создаёт дубликат этого узла.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | **bool** | **true** — рекурсивно клонировать поддерево под указанным узлом; **false** — клонировать только сам узел. Поскольку узлы [XmlDeclaration](../) не имеют дочерних элементов, клонированный узел всегда включает значение данных, независимо от настройки параметра. |

### Возвращаемое значение

Клонированный узел.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlDeclaration](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)