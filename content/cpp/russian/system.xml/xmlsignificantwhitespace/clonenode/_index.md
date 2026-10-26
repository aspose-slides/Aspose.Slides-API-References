---
title: CloneNode()
second_title: Aspose.Slides для C++ API справочник
description: Создаёт дубликат этого узла.
type: docs
weight: 79
url: /ru/system.xml/xmlsignificantwhitespace/clonenode/
---
## XmlSignificantWhitespace::CloneNode(bool) метод


Создаёт дубликат этого узла.

```cpp
SharedPtr<XmlNode> System::Xml::XmlSignificantWhitespace::CloneNode(bool deep) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | **bool** | **true** для рекурсивного клонирования поддерева под указанным узлом; **false** для клонирования только самого узла. Для узлов значимого пробела клонированный узел всегда включает значение данных, независимо от настройки параметра. |

### Возвращаемое значение

Клонированный узел.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlSignificantWhitespace](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)