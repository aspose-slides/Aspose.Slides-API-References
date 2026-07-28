---
title: VerifyHash()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Sprawdza podpis danych.
type: docs
weight: 222
url: /pl/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) method


Sprawdza podpis danych.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Skrót obliczony dla odebranych danych. |
| str | const [String](../../../system/string/)\& | Nazwa używanego algorytmu skrótu. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podpis otrzymany. |

### Wartość zwracana

true jeśli podpis jest prawidłowy, false w przeciwnym razie.

## Zobacz także

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)