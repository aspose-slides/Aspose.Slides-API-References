---
title: ToBase64CharArray()
second_title: Aspose.Slides для C++: справочник API
description: Base-64 кодирует диапазон элементов в указанном массиве байтов и сохраняет закодированные данные в виде массива символов Unicode.
type: docs
weight: 27
url: /ru/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) метод


Base-64 кодирует диапазон элементов в указанном массиве байтов и сохраняет закодированные данные в виде массива символов Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Массив байтов, содержащий диапазон элементов для кодирования |
| offset_in | int | Индекс элемента во входном массиве, с которого начинается диапазон для кодирования |
| length | int | Длина диапазона элементов для кодирования |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Константная ссылка на массив вывода, в который следует поместить полученные данные |
| offset_out | int | Индекс в массиве вывода, с которого начать помещать полученные данные |
| insert_line_breaks | **bool** | Указывает, следует ли вставлять символы разрыва строки в массив вывода после каждых 76 символов base-64 |

### Возвращаемое значение

Количество символов, записанных в массив вывода

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) метод


Base-64 кодирует диапазон элементов в указанном массиве байтов и сохраняет закодированные данные в виде массива символов Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Массив байтов, содержащий диапазон элементов для кодирования |
| offset_in | int | Индекс элемента во входном массиве, с которого начинается диапазон для кодирования |
| length | int | Длина диапазона элементов для кодирования |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Константная ссылка на массив вывода, в который следует поместить полученные данные |
| offset_out | int | Индекс в массиве вывода, с которого начать помещать полученные данные |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Указывает параметры форматирования данных, закодированных в base-64 |

### Возвращаемое значение

Количество символов, записанных в массив вывода

## Смотрите также

* Перечисление [Base64FormattingOptions](../../base64formattingoptions/)
* Типовое определение [ArrayPtr](../../arrayptr/)
* Структура [Convert](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)