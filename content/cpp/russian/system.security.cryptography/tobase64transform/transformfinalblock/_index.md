---
title: TransformFinalBlock()
second_title: Aspose.Slides для C++ справка API
description: Обрабатывает последний блок данных и вычисляет выходное значение.
type: docs
weight: 66
url: /ru/system.security.cryptography/tobase64transform/transformfinalblock/
---
## ToBase64Transform::TransformFinalBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) method


Обрабатывает последний блок данных и вычисляет выходное значение.

```cpp
System::ArrayPtr<uint8_t> System::Security::Cryptography::ToBase64Transform::TransformFinalBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для чтения данных из. |
| inputOffset | **int32_t** | Смещение входного буфера. |
| inputCount | **int32_t** | Количество байтов для обработки. |

### Возвращаемое значение

Вывод, рассчитанный для всей входной последовательности.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ToBase64Transform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)