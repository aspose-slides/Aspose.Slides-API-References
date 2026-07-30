---
title: SignData()
second_title: Aspose.Slides pro C++ API
description: Vypočítá hodnotu hash daného pole dat pomocí zadaného hash algoritmu a podepíše výsledek.
type: docs
weight: 79
url: /cs/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Vypočítá hodnotu hash zadaného pole dat pomocí zadaného hash algoritmu a podepíše výsledek.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Vstupní pole dat. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. vrací ECDSA podpis pro vstupní data. |

## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metoda

Vypočítá hodnotu hash zadaného pole dat pomocí zadaného hash algoritmu a podepíše výsledek.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Vstupní pole dat. |
| offset | **int32_t** | Posun v **data**. |
| count | **int32_t** | Počet bajtů použitých jako vstupní data. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. vrací ECDSA podpis pro vstupní data. |

## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) metoda

Vypočítá hodnotu hash zadaného binárního proudu pomocí zadaného hash algoritmu a podepíše výsledek.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binární proud. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. vrací ECDSA podpis pro vstupní data. |

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Třída [ECDsa](../)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)