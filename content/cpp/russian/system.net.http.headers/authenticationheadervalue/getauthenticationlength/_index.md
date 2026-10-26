---
title: GetAuthenticationLength()
second_title: Справочник API Aspose.Slides для C++
description: Разбирает указанную строку и возвращает последний индекс её строкового представления.
type: docs
weight: 118
url: /ru/system.net.http.headers/authenticationheadervalue/getauthenticationlength/
---
## AuthenticationHeaderValue::GetAuthenticationLength(String, int32_t, System::SharedPtr\<Object\>\&) метод

Разбирает указанную строку и возвращает последний индекс строкового представления.

```cpp
static int32_t System::Net::Http::Headers::AuthenticationHeaderValue::GetAuthenticationLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [String](../../../system/string/) | Строка, которую необходимо разобрать. |
| startIndex | **int32_t** | Начальная позиция для разбора. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Выходной параметр, в который будет записано разобранное значение. |

### Возвращаемое значение

Длина разобранной подстроки, иначе 0.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [Object](../../../system/object/)
* Класс [AuthenticationHeaderValue](../)
* Пространство имён [System::Net::Http::Headers](../../)
* Библиотека [Aspose.Slides](../../../)