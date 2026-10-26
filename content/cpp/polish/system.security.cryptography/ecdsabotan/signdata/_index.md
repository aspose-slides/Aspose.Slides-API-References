---
title: SignData()
second_title: Aspose.Slides dla C++ – referencja API
description: Oblicza wartość skrótu podanej tablicy danych i podpisuje wynik.
type: docs
weight: 131
url: /pl/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) metoda

Oblicza wartość skrótu podanej tablicy danych i podpisuje wynik.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tablica danych wejściowych. zwraca podpis ECDSA dla danych wejściowych. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) metoda

Oblicza wartość skrótu podanej tablicy danych i podpisuje wynik.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tablica danych wejściowych. |
| offset | **int32_t** | Offset w **data**. |
| count | **int32_t** | Liczba bajtów używanych jako dane wejściowe. zwraca podpis ECDSA dla danych wejściowych. |

## ECDsaBotan::SignData(const StreamPtr\&) metoda

Oblicza wartość skrótu podanego strumienia binarnego i podpisuje wynik.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Strumień binarny. zwraca podpis ECDSA dla danych wejściowych. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Oblicza wartość skrótu podanej tablicy danych przy użyciu określonego algorytmu skrótu i podpisuje wynik.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tablica danych wejściowych. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. zwraca podpis ECDSA dla danych wejściowych. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metoda

Oblicza wartość skrótu podanej tablicy danych przy użyciu określonego algorytmu skrótu i podpisuje wynik.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tablica danych wejściowych. |
| offset | **int32_t** | Offset w **data**. |
| count | **int32_t** | Liczba bajtów używanych jako dane wejściowe. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. zwraca podpis ECDSA dla danych wejściowych. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) metoda

Oblicza wartość skrótu podanego strumienia binarnego przy użyciu określonego algorytmu skrótu i podpisuje wynik.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Strumień binarny. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. zwraca podpis ECDSA dla danych wejściowych. |

## Zobacz także

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)