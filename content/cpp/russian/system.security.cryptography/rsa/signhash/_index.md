---
title: SignHash()
second_title: Справочник API Aspose.Slides для C++
description: Вычисляет подпись для указанного значения хеша.
type: docs
weight: 144
url: /ru/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) метод

Вычисляет подпись для указанного значения хеша.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Значение хеша. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Алгоритм хеширования. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Режим заполнения. Возвращает [RSA](../) подпись для указанного хеша. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)