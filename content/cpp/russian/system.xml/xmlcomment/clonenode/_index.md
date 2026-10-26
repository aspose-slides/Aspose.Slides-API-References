---
title: CloneNode()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт дубликат этого узла.
type: docs
weight: 40
url: /ru/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) method


Создает дубликат этого узла.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | **bool** | **true** для рекурсивного клонирования поддерева под указанным узлом; **false** для клонирования только самого узла. Поскольку узлы комментариев не имеют дочерних элементов, клонированный узел всегда включает текстовое содержимое, независимо от настройки параметра. |

### Возвращаемое значение

Клонированный узел.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlComment](../)
* Пространство имён [System::Xml](../../)
* Library [Aspose.Slides](../../../)