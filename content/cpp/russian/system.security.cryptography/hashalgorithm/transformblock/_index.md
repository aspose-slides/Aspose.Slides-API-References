---
title: TransformBlock()
second_title: Справочник API Aspose.Slides для C++
description: Обрабатывает блок данных и копирует данные в выходной массив.
type: docs
weight: 66
url: /ru/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) метод

Обрабатывает блок данных и копирует данные в выходной массив.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для чтения данных из. |
| inputOffset | int | Смещение входного буфера. |
| inputCount | int | Количество байтов для обработки. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Выходной буфер для копирования данных; nullptr, если копирование не требуется. |
| outputOffset | int | Смещение выходного буфера. |

### Возвращаемое значение

Количество записанных байтов.

## См. также

* Тип-определение [ArrayPtr](../../../system/arrayptr/)
* Класс [HashAlgorithm](../)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)