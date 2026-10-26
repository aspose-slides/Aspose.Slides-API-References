---
title: TransformFinalBlock()
second_title: Aspose.Slides для C++ справочник API
description: Обрабатывает последний блок данных и вычисляет хеш.
type: docs
weight: 79
url: /ru/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) метод

Обрабатывает последний блок данных и вычисляет хеш.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для чтения данных из. |
| inputOffset | int | Смещение входного буфера. |
| inputCount | int | Количество байтов для обработки. |

### Возвращаемое значение

Хеш, вычисленный для всей последовательности данных.

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [HashAlgorithm](../)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)