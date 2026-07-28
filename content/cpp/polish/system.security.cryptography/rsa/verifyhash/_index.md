---
title: VerifyHash()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Weryfikuje, czy podpis określonego skrótu jest prawidłowy.
type: docs
weight: 170
url: /pl/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) metoda

Weryfikuje, czy podpis określonego skrótu jest prawidłowy.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Wartość skrótu danych podpisanych. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Dane podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Tryb wypełnienia. zwraca true, jeśli podpis jest prawidłowy, w przeciwnym razie - false. |

## Zobacz także

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [RSASignaturePadding](../../rsasignaturepadding/)
* Klasa [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)