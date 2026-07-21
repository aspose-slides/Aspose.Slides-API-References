---
title: CloneNode()
second_title: Справочник API Aspose.Slides для C++
description: Создает дубликат этого узла. Узлы Entity нельзя клонировать. Вызов этого метода для объекта XmlEntity бросает исключение.
type: docs
weight: 170
url: /ru/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) method


Создает дубликат этого узла. Узлы Entity нельзя клонировать. Вызов этого метода для объекта [XmlEntity](../) бросает исключение.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| deep | **bool** | **true** для рекурсивного клонирования подпоследовательности под указанным узлом; **false** для клонирования только самого узла. |

### Возвращаемое значение

Копия [XmlNode](../../xmlnode/), из которой вызывается метод.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlEntity](../)
* Пространство имен [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)