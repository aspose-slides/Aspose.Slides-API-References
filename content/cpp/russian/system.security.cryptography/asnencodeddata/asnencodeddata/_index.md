---
title: AsnEncodedData()
second_title: Aspose.Slides для C++ справочник API
description: Конструктор копирования.
type: docs
weight: 1
url: /ru/system.security.cryptography/asnencodeddata/asnencodeddata/
---
## AsnEncodedData::AsnEncodedData(const SharedPtr\<AsnEncodedData\>\&) конструктор


Конструктор копирования.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<AsnEncodedData> &asn_encoded_data)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| asn_encoded_data | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../)\>\& | [Object](../../../system/object/) для копирования данных из. |

## AsnEncodedData::AsnEncodedData(const ByteArrayPtr\&) конструктор


Конструктор.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const ByteArrayPtr &raw_data)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Закодированные данные в необработанном байтовом формате. |

## AsnEncodedData::AsnEncodedData(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&) конструктор


Конструктор.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../oid/)\>\& | [Object](../../../system/object/) идентификатор закодированных данных. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Закодированные данные в необработанном байтовом формате. |

## AsnEncodedData::AsnEncodedData(const String\&, const ByteArrayPtr\&) конструктор


Конструктор.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const String &oid, const ByteArrayPtr &raw_data)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) идентификатор закодированных данных. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Закодированные данные в необработанном байтовом формате. |

## См. также

* Типоопределение [SharedPtr](../../../system/sharedptr/)
* Типоопределение [ByteArrayPtr](../../../system/bytearrayptr/)
* Класс [AsnEncodedData](../)
* Класс [Oid](../../oid/)
* Класс [String](../../../system/string/)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)