---
title: GetRangeLength()
second_title: Справка API Aspose.Slides для C++
description: Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса RangeHeaderValue.
type: docs
weight: 118
url: /ru/system.net.http.headers/rangeheadervalue/getrangelength/
---
## RangeHeaderValue::GetRangeLength(String, int32_t, System::SharedPtr\<Object\>\&) метод


Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [RangeHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::RangeHeaderValue::GetRangeLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [String](../../../system/string/) | Строка для разбора. |
| startIndex | **int32_t** | Начальная позиция для разбора. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Экземпляр, в который будет присвоен разобранный объект. |

### Возвращаемое значение

Возвращает длину разобранной подстроки, в противном случае 0.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [Object](../../../system/object/)
* Класс [RangeHeaderValue](../)
* Пространство имён [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)