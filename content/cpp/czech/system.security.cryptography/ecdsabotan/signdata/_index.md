---
title: SignData()
second_title: Aspose.Slides pro C++ – reference API
description: Vypočítá hash hodnotu zadaného pole dat a podepíše výsledek.
type: docs
weight: 131
url: /cs/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) metoda

Vypočítá hash hodnotu zadaného pole dat a podepíše výsledek.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Vstupní pole dat. vrátí ECDSA podpis pro vstupní data. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) metoda

Vypočítá hash hodnotu zadaného pole dat a podepíše výsledek.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Vstupní pole dat. |
| offset | **int32_t** | Posun v **data**. |
| count | **int32_t** | Počet bajtů použitých jako vstupní data. vrátí ECDSA podpis pro vstupní data. |

## ECDsaBotan::SignData(const StreamPtr\&) metoda

Vypočítá hash hodnotu zadaného binárního proudu a podepíše výsledek.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binární proud. vrátí ECDSA podpis pro vstupní data. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Vypočítá hash hodnotu zadaného pole dat pomocí zadaného hash algoritmu a podepíše výsledek.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Vstupní pole dat. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. vrátí ECDSA podpis pro vstupní data. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metoda

Vypočítá hash hodnotu zadaného pole dat pomocí zadaného hash algoritmu a podepíše výsledek.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Vstupní pole dat. |
| offset | **int32_t** | Posun v **data**. |
| count | **int32_t** | Počet bajtů použitých jako vstupní data. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. vrátí ECDSA podpis pro vstupní data. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) metoda

Vypočítá hash hodnotu zadaného binárního proudu pomocí zadaného hash algoritmu a podepíše výsledek.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binární proud. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. vrátí ECDSA podpis pro vstupní data. |

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Třída [ECDsaBotan](../)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)