---
title: CloneNode()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт копию этого узла.
type: docs
weight: 118
url: /ru/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) метод

Создаёт копию этого узла.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | **bool** | **true** для рекурсивного клонирования поддерева под указанным узлом; **false** для клонирования только самого узла. Для узлов типа документа клонированный узел всегда включает поддерево, независимо от значения параметра. |

### Возвращаемое значение

Клонированный узел.

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlDocumentType](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)