---
title: VerifyData()
second_title: Aspose.Slides dla C++ – referencja API
description: Sprawdza podpis danych.
type: docs
weight: 209
url: /pl/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) method

Sprawdza podpis danych.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) do sprawdzenia podpisu. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Algorytm skrótu do użycia. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podpis otrzymany. |

### Wartość zwracana

Prawda, jeśli podpis jest prawidłowy, fałsz w przeciwnym razie.

## Zobacz także

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [RSACryptoServiceProvider](../)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)