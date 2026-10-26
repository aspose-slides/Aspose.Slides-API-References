---
title: Read()
second_title: Справочник API Aspose.Slides для C++
description: Считывает данные из потока.
type: docs
weight: 14
url: /ru/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод


Считывает данные из потока.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Буфер данных назначения. |
| offset | **int32_t** | Смещение в буфере назначения. |
| count | **int32_t** | Количество байтов для чтения. |

### Возвращаемое значение

Фактическое количество считываемых байтов.

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод


Считывает данные из потока.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Буфер данных назначения. |
| offset | **int32_t** | Смещение в буфере назначения. |
| count | **int32_t** | Количество байтов для чтения. |

### Возвращаемое значение

Фактическое количество считываемых байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CryptoStream](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)