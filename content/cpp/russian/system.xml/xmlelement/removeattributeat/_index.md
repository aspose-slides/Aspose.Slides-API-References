---
title: RemoveAttributeAt()
second_title: Aspose.Slides для C++ справочник API
description: Удаляет узел атрибута с указанным индексом из элемента. (Если удалённый атрибут имеет значение по умолчанию, оно сразу заменяется).
type: docs
weight: 339
url: /ru/system.xml/xmlelement/removeattributeat/
---
## XmlElement::RemoveAttributeAt(int32_t) метод

Удаляет узел атрибута с указанным индексом из элемента. (Если удалённый атрибут имеет значение по умолчанию, оно сразу заменяется).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlElement::RemoveAttributeAt(int32_t i)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | **int32_t** | Индекс узла, который нужно удалить. Первый узел имеет индекс 0. |

### Возвращаемое значение

Удалённый узел атрибута или **nullptr**, если в указанном индексе нет узла.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNode](../../xmlnode/)
* Класс [XmlElement](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)