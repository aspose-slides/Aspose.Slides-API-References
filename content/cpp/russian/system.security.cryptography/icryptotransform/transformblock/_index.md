---
title: TransformBlock()
second_title: Aspose.Slides для C++ Справочник API
description: Обрабатывает блок данных и копирует данные в выходной массив.
type: docs
weight: 1
url: /ru/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) метод

Обрабатывает блок данных и копирует данные в выходной массив.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для чтения данных из. |
| inputOffset | int | Смещение во входном буфере. |
| inputCount | int | Количество байтов для обработки. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер вывода для копирования данных; nullptr для отсутствия копирования. |
| outputOffset | int | Смещение в выходном буфере. |

### Возвращаемое значение

Количество записанных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [ICryptoTransform](../)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)