---
title: GetNameValueLength()
second_title: Aspose.Slides для C++ API Справка
description: Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса NameValueHeaderValue.
type: docs
weight: 118
url: /ru/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) method

Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [String](../../../system/string/) | Строка для разбора. |
| startIndex | **int32_t** | Начальная позиция для разбора. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Экземпляр, в который будет присвоен разобранный объект. |

### Возвращаемое значение

Возвращает длину разобранной подстроки, в противном случае 0.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) method

Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [String](../../../system/string/) | Строка для разбора. |
| startIndex | **int32_t** | Начальная позиция для разбора. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | Функция, используемая для создания новых экземпляров класса [NameValueHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Экземпляр, в который будет присвоен разобранный объект. |

### Возвращаемое значение

Возвращает длину разобранной подстроки, в противном случае 0.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Class [String](../../../system/string/)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)