---
title: GetCacheControlLength()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса CacheControlHeaderValue.
type: docs
weight: 456
url: /ru/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) метод

Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [CacheControlHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [String](../../../system/string/) | Строка для разбора. |
| startIndex | **int32_t** | Начальная позиция для разбора. |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | Значение, которое должно быть добавлено к разобранному объекту. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | Экземпляр, в котором будет назначен разобранный объект. |

### Возвращаемое значение

Длина разобранной подстроки, иначе 0.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [CacheControlHeaderValue](../)
* Пространство имён [System::Net::Http::Headers](../../)
* Библиотека [Aspose.Slides](../../../)