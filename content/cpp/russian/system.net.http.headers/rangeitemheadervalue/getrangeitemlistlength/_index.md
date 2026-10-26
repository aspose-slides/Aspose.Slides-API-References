---
title: GetRangeItemListLength()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует переданную строку, начиная с указанной позиции, в коллекцию экземпляров класса RangeItemHeaderValue.
type: docs
weight: 79
url: /ru/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) метод

Преобразует переданную строку, начиная с указанной позиции, в коллекцию экземпляров класса RangeItemHeaderValue.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [String](../../../system/string/) | Строка для разбора. |
| startIndex | **int32_t** | Начальная позиция для разбора. |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | Экземпляр, в котором будет присвоена разобранная коллекция. |

### Возвращаемое значение

Длина разобранной подстроки, иначе 0.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [ICollection](../../../system.collections.generic/icollection/)
* Класс [RangeItemHeaderValue](../)
* Пространство имён [System::Net::Http::Headers](../../)
* Библиотека [Aspose.Slides](../../../)