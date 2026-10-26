---
title: SignHash()
second_title: Aspose.Slides для C++ справочник API
description: Вычисляет подпись указанного входного значения.
type: docs
weight: 196
url: /ru/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) метод

Вычисляет подпись указанного входного значения.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Хеш-значение данных, которые необходимо подписать. |
| str | const [String](../../../system/string/)\& | Идентификатор алгоритма хеширования, используемый для создания хеша. |

### Возвращаемое значение

[DSA](../../dsa/) подпись для указанных данных.

## См. также

* Тип [ByteArrayPtr](../../../system/bytearrayptr/)
* Класс [String](../../../system/string/)
* Класс [DSACryptoServiceProvider](../)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)