---
title: GetEntityTagLength()
second_title: Aspose.Slides для C++ API Reference
description: Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса EntityTagHeaderValue.
type: docs
weight: 118
url: /ru/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) метод

Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [EntityTagHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [String](../../../system/string/) | Строка для разбора. |
| startIndex | **int32_t** | Начальная позиция для разбора. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | Экземпляр, в который будет присвоен разобранный объект. |

### Возвращаемое значение

Длина разобранной подстроки, иначе 0.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [EntityTagHeaderValue](../)
* Пространство имён [System::Net::Http::Headers](../../)
* Библиотека [Aspose.Slides](../../../)