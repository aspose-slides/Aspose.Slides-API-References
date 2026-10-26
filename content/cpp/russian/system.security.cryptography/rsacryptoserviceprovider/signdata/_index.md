---
title: SignData()
second_title: Aspose.Slides для C++ справочник API
description: Вычисляет подпись указанного входного значения.
type: docs
weight: 183
url: /ru/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) метод


Вычисляет подпись заданного входного значения.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) для чтения входных данных. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Алгоритм хеширования, который будет использоваться. |

### Возвращаемое значение

[RSA](../../rsa/) подпись для указанных данных.

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) метод


Вычисляет подпись заданного входного значения.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток для чтения данных, которые подписываются. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Алгоритм хеширования, который будет использоваться. |

### Возвращаемое значение

[RSA](../../rsa/) подпись для указанных данных.

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) метод


Вычисляет подпись заданного входного значения.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) для чтения входных данных. |
| offset | **int32_t** | Начальный индекс среза буфера ввода. |
| count | **int32_t** | Размер среза буфера ввода. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Алгоритм хеширования, который будет использоваться. |

### Возвращаемое значение

[RSA](../../rsa/) подпись для указанных данных.

## Смотрите также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [RSACryptoServiceProvider](../)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)