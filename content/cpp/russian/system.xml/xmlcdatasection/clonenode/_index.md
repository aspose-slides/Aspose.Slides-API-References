---
title: CloneNode()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт дубликат этого узла.
type: docs
weight: 53
url: /ru/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) метод

Создаёт дубликат этого узла.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | **bool** | **true**, если нужно рекурсивно клонировать поддерево под указанным узлом; **false**, если требуется клонировать только сам узел. Поскольку CDATA-узлы не имеют дочерних элементов, независимо от значения параметра клонированный узел всегда будет включать содержимое данных. |

### Возвращаемое значение

Клонированный узел.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlCDataSection](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)