---
title: FromBase64CharArray()
second_title: Aspose.Slides для C++ справки по API
description: Декодирует данные, закодированные в base-64, представленные как диапазон в массиве символов Unicode.
type: docs
weight: 53
url: /ru/system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) метод


Декодирует данные, закодированные в base-64, представленные как диапазон в массиве символов Unicode.

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Массив, содержащий данные для декодирования |
| offset | int | Позиция во входном массиве, с которой начинается диапазон для декодирования |
| length | int | Длина диапазона для декодирования |

### Возвращаемое значение

Массив байтов, содержащий декодированные данные

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)