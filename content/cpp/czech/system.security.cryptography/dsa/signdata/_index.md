---
title: SignData()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vypočítá hash hodnotu zadaného pole dat pomocí zadaného hash algoritmu a podepíše výsledek.
type: docs
weight: 79
url: /cs/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Vypočítá hash hodnotu určeného pole dat pomocí určeného hash algoritmu a podepíše výsledek.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Vstupní pole dat. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. vrací [DSA](../) podpis pro vstupní data. |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metoda

Vypočítá hash hodnotu určeného pole dat pomocí určeného hash algoritmu a podepíše výsledek.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Vstupní pole dat. |
| offset | **int32_t** | Posun v **data**. |
| count | **int32_t** | Počet bajtů použitého jako vstupní data. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. vrací [DSA](../) podpis pro vstupní data. |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) metoda

Vypočítá hash hodnotu určeného binárního proudu pomocí určeného hash algoritmu a podepíše výsledek.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binární proud. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. vrací [DSA](../) podpis pro vstupní data. |

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)