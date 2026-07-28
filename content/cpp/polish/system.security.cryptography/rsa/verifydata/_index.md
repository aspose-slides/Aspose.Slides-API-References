---
title: VerifyData()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Weryfikuje, czy podpis określonych danych jest prawidłowy.
type: docs
weight: 157
url: /pl/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metoda

Weryfikuje, że podpis określonych danych jest prawidłowy.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podpisane dane. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dane podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Tryb wypełnienia. zwraca true, jeśli podpis jest prawidłowy, w przeciwnym razie - false. |

## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metoda

Weryfikuje, że podpis określonych danych jest prawidłowy.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podpisane dane. |
| offset | **int32_t** | Przesunięcie w **data**. |
| count | **int32_t** | Liczba bajtów do skrótu. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dane podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Tryb wypełnienia. zwraca true, jeśli podpis jest prawidłowy, w przeciwnym razie - false. |

## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metoda

Weryfikuje, że podpis określonego strumienia binarnego jest prawidłowy.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Podpisane dane. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dane podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Tryb wypełnienia. zwraca true, jeśli podpis jest prawidłowy, w przeciwnym razie - false. |

## Zobacz także

* Definicja typu [ByteArrayPtr](../../../system/bytearrayptr/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [StreamPtr](../../../system/streamptr/)
* Klasa [RSASignaturePadding](../../rsasignaturepadding/)
* Klasa [RSA](../)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)