---
title: TransformFinalBlock()
second_title: Aspose.Slides для C++ справочник API
description: Обрабатывает последний блок данных и вычисляет значение вывода.
type: docs
weight: 14
url: /ru/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) метод

Обрабатывает последний блок данных и вычисляет значение вывода.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для чтения данных из. |
| inputOffset | int | Смещение буфера ввода. |
| inputCount | int | Количество байтов для обработки. |

### Возвращаемое значение

Вывод, рассчитанный для всей входной последовательности.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [ICryptoTransform](../)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)