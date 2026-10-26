---
title: ToByteArray()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует строку или подстроку в массив байтов.
type: docs
weight: 508
url: /ru/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const метод

Преобразует строку или подстроку в массив байтов.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | **int32_t** | Начальный индекс подстроки. |
| length | **int32_t** | Длина подстроки. |
| LE | **bool** | Если true, кодировать символы, используя little endian; иначе — big endian. |

### Возвращаемое значение

[Array](../../array/) содержащий байты, представляющие символы строки.

## См. также

* Типовое определение [ArrayPtr](../../arrayptr/)
* Класс [String](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)