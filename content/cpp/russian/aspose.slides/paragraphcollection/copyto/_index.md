---
title: CopyTo()
second_title: Aspose.Slides для C++ справочник API
description: "Копирует элементы ICollection в System::Array, начиная с определённого индекса System::Array."
type: docs
weight: 105
url: /ru/aspose.slides/paragraphcollection/copyto/
---
## ParagraphCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IParagraph\>\>, int32_t) метод

Копирует элементы из [ICollection](../../../system.collections.generic/icollection/) в [System::Array](../../../system/array/), начиная с определённого индекса [System::Array](../../../system/array/).

```cpp
void Aspose::Slides::ParagraphCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IParagraph>> array, int32_t arrayIndex)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\>\> | Одномерный [System::Array](../../../system/array/), который является получателем элементов, скопированных из [ICollection](../../../system.collections.generic/icollection/). [System::Array](../../../system/array/) должен иметь индексацию, начинающуюся с нуля. |
| arrayIndex | **int32_t** | Нулевой индекс в *array*, с которого начинается копирование. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IParagraph](../../iparagraph/)
* Класс [ParagraphCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)