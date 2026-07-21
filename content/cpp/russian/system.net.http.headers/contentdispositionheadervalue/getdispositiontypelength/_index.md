---
title: GetDispositionTypeLength()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса ContentDispositionHeaderValue.
type: docs
weight: 300
url: /ru/system.net.http.headers/contentdispositionheadervalue/getdispositiontypelength/
---
## ContentDispositionHeaderValue::GetDispositionTypeLength(String, int32_t, System::SharedPtr\<Object\>\&) метод

Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [ContentDispositionHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::ContentDispositionHeaderValue::GetDispositionTypeLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
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
* Класс [String](../../../system/string/)
* Класс [Object](../../../system/object/)
* Класс [ContentDispositionHeaderValue](../)
* Пространство имён [System::Net::Http::Headers](../../)
* Библиотека [Aspose.Slides](../../../)