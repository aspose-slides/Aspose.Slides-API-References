---
title: GetRetryConditionLength()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса RetryConditionHeaderValue.
type: docs
weight: 105
url: /ru/system.net.http.headers/retryconditionheadervalue/getretryconditionlength/
---
## RetryConditionHeaderValue::GetRetryConditionLength(String, int32_t, System::SharedPtr\<Object\>\&) method

Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [RetryConditionHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::RetryConditionHeaderValue::GetRetryConditionLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Строка для разбора. |
| startIndex | **int32_t** | Начальная позиция для разбора. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Экземпляр, в который будет присвоен разобранный объект. |

### Возвращаемое значение

Возвращает длину разобранной подстроки, иначе 0.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [Object](../../../system/object/)
* Класс [RetryConditionHeaderValue](../)
* Пространство имён [System::Net::Http::Headers](../../)
* Библиотека [Aspose.Slides](../../../)