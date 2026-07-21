---
title: TransformBlock()
second_title: Справочник API Aspose.Slides для C++
description: Обрабатывает блок данных и копирует их в выходной массив.
type: docs
weight: 53
url: /ru/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) метод

Обрабатывает блок данных и копирует их в выходной массив.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для чтения данных из. |
| inputOffset | **int32_t** | Смещение входного буфера. |
| inputCount | **int32_t** | Количество байтов для обработки. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Выходной буфер для копирования данных; nullptr для отсутствия копирования. |
| outputOffset | **int32_t** | Смещение выходного буфера. |

### Возвращаемое значение

Количество записанных байтов.

## Смотрите также

* typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [ToBase64Transform](../)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)