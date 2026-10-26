---
title: Remove()
second_title: Aspose.Slides для C++ справочник API
description: Удаляет первое вхождение конкретного объекта из ICollection.
type: docs
weight: 131
url: /ru/aspose.slides/paragraphcollection/remove/
---
## ParagraphCollection::Remove(System::SharedPtr\<IParagraph\>) method


Удаляет первое вхождение конкретного объекта из [ICollection](../../../system.collections.generic/icollection/).

```cpp
bool Aspose::Slides::ParagraphCollection::Remove(System::SharedPtr<IParagraph> item) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | Объект, который нужно удалить из [ICollection](../../../system.collections.generic/icollection/). |

### Значение возврата

true, если *item* был успешно удалён из [ICollection](../../../system.collections.generic/icollection/); в противном случае — false. Этот метод также возвращает false, если *item* не найден в исходном [ICollection](../../../system.collections.generic/icollection/).

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IParagraph](../../iparagraph/)
* Класс [ParagraphCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)