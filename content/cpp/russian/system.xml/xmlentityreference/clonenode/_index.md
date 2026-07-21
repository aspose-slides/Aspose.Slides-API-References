---
title: CloneNode()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт дубликат этого узла.
type: docs
weight: 92
url: /ru/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) метод

Создаёт дубликат этого узла.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | **bool** | **true** чтобы рекурсивно клонировать поддерево под указанным узлом; **false** чтобы клонировать только сам узел. Для узлов [XmlEntityReference](../) этот метод всегда возвращает узел ссылки на сущность без дочерних элементов. Текст замещения задаётся, когда узел вставляется в родителя. |

### Return Value

Клонированный узел.

## See Also

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlEntityReference](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)