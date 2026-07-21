---
title: GetNameValueListLength()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует переданную строку, начиная с указанного индекса, в коллекцию экземпляров класса NameValueHeaderValue и возвращает длину разобранной подстроки.
type: docs
weight: 131
url: /ru/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) method

Преобразует переданную строку, начиная с указанного индекса, в коллекцию экземпляров класса NameValueHeaderValue и возвращает длину разобранной подстроки.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [String](../../../system/string/) | Строка для анализа. |
| startIndex | **int32_t** | Начальная позиция для анализа. |
| delimiter | char16_t | Строка, используемая для разделения элементов в указанной строке. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Выходной параметр, в который будет присвоена разобранная коллекция. |

### Возвращаемое значение

Длина разобранной подстроки.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [ObjectCollection](../../objectcollection/)
* Класс [NameValueHeaderValue](../)
* Пространство имён [System::Net::Http::Headers](../../)
* Библиотека [Aspose.Slides](../../../)