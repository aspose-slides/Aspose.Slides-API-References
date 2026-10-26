---
title: VerifyData()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Weryfikuje, czy podpis określonych danych jest prawidłowy.
type: docs
weight: 105
url: /pl/system.security.cryptography/ecdsa/verifydata/
---
## ECDsa::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Weryfikuje, czy podpis określonych danych jest prawidłowy.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podpisane dane. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dane podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. zwraca true, jeśli podpis jest prawidłowy, w przeciwnym razie - false. |

## ECDsa::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Weryfikuje, czy podpis określonych danych jest prawidłowy.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podpisane dane. |
| offset | **int32_t** | Przesunięcie w **data**. |
| count | **int32_t** | Liczba bajtów do zhashowania. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dane podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. zwraca true, jeśli podpis jest prawidłowy, w przeciwnym razie - false. |

## ECDsa::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Weryfikuje, czy podpis określonego strumienia binarnego jest prawidłowy.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Podpisane dane. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dane podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. zwraca true, jeśli podpis jest prawidłowy, w przeciwnym razie - false. |

## Zobacz także

* Definicja typu [ByteArrayPtr](../../../system/bytearrayptr/)
* Definicja typu [StreamPtr](../../../system/streamptr/)
* Klasa [ECDsa](../)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)