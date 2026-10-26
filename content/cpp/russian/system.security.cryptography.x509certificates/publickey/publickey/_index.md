---
title: PublicKey()
second_title: Справочник API Aspose.Slides для C++
description: Конструктор.
type: docs
weight: 1
url: /ru/system.security.cryptography.x509certificates/publickey/publickey/
---
## PublicKey::PublicKey(const SharedPtr\<Oid\>\&, const SharedPtr\<AsnEncodedData\>\&, const SharedPtr\<AsnEncodedData\>) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::PublicKey::PublicKey(const SharedPtr<Oid> &oid, const SharedPtr<AsnEncodedData> &parameters, const SharedPtr<AsnEncodedData> key_value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | Объект идентификатора, представляющий открытый ключ. |
| parameters | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | ASN.1-закодированные параметры открытого ключа. |
| key_value | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\> | ASN.1-закодированное значение открытого ключа. |

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [Oid](../../../system.security.cryptography/oid/)
* Класс [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Класс [PublicKey](../)
* Пространство имён [System::Security::Cryptography::X509Certificates](../../)
* Библиотека [Aspose.Slides](../../../)