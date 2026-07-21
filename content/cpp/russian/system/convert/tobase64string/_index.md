---
title: ToBase64String()
second_title: Справочник API Aspose.Slides for C++
description: Base-64 кодирует элементы в указанном массиве байтов и возвращает закодированные данные в виде строки.
type: docs
weight: 40
url: /ru/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) метод

Base-64 кодирует элементы в указанном массиве байтов и возвращает закодированные данные в виде строки.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Массив байтов для кодирования |
| insert_line_breaks | **bool** | Указывает, следует ли вставлять символы переноса строки в выходную строку после каждых 76 символов base-64 |

### Возвращаемое значение

Строка, содержащая base-64 представление входного массива

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) метод

Base-64 кодирует диапазон элементов в указанном массиве байтов и возвращает закодированные данные в виде строки.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Массив байтов, содержащий диапазон элементов для кодирования |
| offset_in | int | Индекс элемента во входном массиве, с которого начинается диапазон для кодирования |
| length | int | Длина диапазона элементов для кодирования |
| insert_line_breaks | **bool** | Указывает, следует ли вставлять символы переноса строки в выходную строку после каждых 76 символов base-64 |

### Возвращаемое значение

Строка, содержащая base-64 представление диапазона элементов входного массива

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) метод

Base-64 кодирует элементы в указанном массиве байтов и возвращает закодированные данные в виде строки.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Массив байтов для кодирования |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Указывает параметры форматирования base-64 закодированных данных |

### Возвращаемое значение

Строка, содержащая base-64 представление входного массива

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) метод

Base-64 кодирует диапазон элементов в указанном массиве байтов и возвращает закодированные данные в виде строки.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Массив байтов, содержащий диапазон элементов для кодирования |
| offset_in | int | Индекс элемента во входном массиве, с которого начинается диапазон для кодирования |
| length | int | Длина диапазона элементов для кодирования |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Указывает параметры форматирования base-64 закодированных данных |

### Возвращаемое значение

Строка, содержащая base-64 представление диапазона элементов входного массива

## См. также

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Класс [String](../../string/)
* Struct [Convert](../)
* Пространство имён [System](../../)
* Library [Aspose.Slides](../../../)