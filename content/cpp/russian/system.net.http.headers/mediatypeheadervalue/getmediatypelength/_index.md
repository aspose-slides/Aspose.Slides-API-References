---
title: GetMediaTypeLength()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса MediaTypeHeaderValue.
type: docs
weight: 144
url: /ru/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) метод

Преобразует переданную строку от указанного индекса в экземпляр [MediaTypeHeaderValue](../) класса.

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [String](../../../system/string/) | Строка для разбора. |
| startIndex | **int32_t** | Начальная позиция для разбора. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | Делегат, используемый для создания экземпляров [MediaTypeHeaderValue](../) класса. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | Экземпляр, в который будет присвоен разобранный объект. |

### Возвращаемое значение

Возвращает длину разобранной подстроки, в противном случае 0.

## См. также

* Тип-определение [HeaderFunc](../../headerfunc/)
* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [MediaTypeHeaderValue](../)
* Пространство имён [System::Net::Http::Headers](../../)
* Библиотека [Aspose.Slides](../../../)