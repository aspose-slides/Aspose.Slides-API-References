---
title: GetContentRangeLength()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует переданную строку с указанной позиции в экземпляр класса ContentRangeHeaderValue.
type: docs
weight: 170
url: /ru/system.net.http.headers/contentrangeheadervalue/getcontentrangelength/
---
## ContentRangeHeaderValue::GetContentRangeLength(String, int32_t, System::SharedPtr\<Object\>\&) метод

Преобразует переданную строку с указанной позиции в экземпляр класса [ContentRangeHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::ContentRangeHeaderValue::GetContentRangeLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [String](../../../system/string/) | Строка для разбора. |
| startIndex | **int32_t** | Начальная позиция для разбора. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Экземпляр, в который будет присвоен разобранный объект. |

### Возвращаемое значение

Длина разобранной подстроки, иначе 0.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [ContentRangeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)