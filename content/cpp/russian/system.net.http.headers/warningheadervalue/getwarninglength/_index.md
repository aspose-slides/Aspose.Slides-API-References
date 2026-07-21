---
title: GetWarningLength()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса WarningHeaderValue.
type: docs
weight: 131
url: /ru/system.net.http.headers/warningheadervalue/getwarninglength/
---
## WarningHeaderValue::GetWarningLength(String, int32_t, System::SharedPtr\<Object\>\&) метод

Конвертирует переданную строку, начиная с указанного индекса, в экземпляр класса [WarningHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::WarningHeaderValue::GetWarningLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [String](../../../system/string/) | Строка для разбора. |
| startIndex | **int32_t** | Начальная позиция для разбора. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Экземпляр, в который будет присвоен разобранный объект. |

### Возвращаемое значение

Возвращает длину разобранной подстроки, иначе 0.

## Смотрите также

* Типedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [Object](../../../system/object/)
* Класс [WarningHeaderValue](../)
* Пространство имён [System::Net::Http::Headers](../../)
* Библиотека [Aspose.Slides](../../../)