---
title: GetRangeItemLength()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса RangeItemHeaderValue.
type: docs
weight: 92
url: /ru/system.net.http.headers/rangeitemheadervalue/getrangeitemlength/
---
## RangeItemHeaderValue::GetRangeItemLength(String, int32_t, System::SharedPtr\<RangeItemHeaderValue\>\&) метод


Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [RangeItemHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength(String input, int32_t startIndex, System::SharedPtr<RangeItemHeaderValue> &parsedValue)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [String](../../../system/string/) | Строка для разбора. |
| startIndex | **int32_t** | Начальная позиция для разбора. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\& | Экземпляр, в который будет присвоен разобранный объект. |

### Возвращаемое значение

Возвращает длину разобранной подстроки, в противном случае 0.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [RangeItemHeaderValue](../)
* Пространство имён [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)