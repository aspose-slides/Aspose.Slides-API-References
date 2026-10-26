---
title: SignData()
second_title: Aspose.Slides pro C++ API Reference
description: Vypočítá podpis zadané vstupní hodnoty.
type: docs
weight: 183
url: /cs/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) metoda

Vypočítá podpis zadané vstupní hodnoty.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) pro čtení vstupních dat z. |

### Návratová hodnota

[DSA](../../dsa/) podpis pro zadaná data.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) metoda

Vypočítá podpis zadané vstupní hodnoty.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream pro čtení podepisovaných dat z. |

### Návratová hodnota

[DSA](../../dsa/) podpis pro zadaná data.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) metoda

Vypočítá podpis zadané vstupní hodnoty.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) pro čtení vstupních dat z. |
| offset | **int32_t** | Počáteční index výřezu vstupní vyrovnávací paměti. |
| count | **int32_t** | Velikost výřezu vstupní vyrovnávací paměti. |

### Návratová hodnota

[DSA](../../dsa/) podpis pro zadaná data.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Vypočítá hash hodnotu zadaného pole dat pomocí zadaného hash algoritmu a výsledek podepíše.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Pole vstupních dat. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. vrací [DSA](../../dsa/) podpis pro vstupní data. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metoda

Vypočítá hash hodnotu zadaného pole dat pomocí zadaného hash algoritmu a výsledek podepíše.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Pole vstupních dat. |
| offset | **int32_t** | Posun v **data**. |
| count | **int32_t** | Počet bajtů použitých jako vstupní data. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. vrací [DSA](../../dsa/) podpis pro vstupní data. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) metoda

Vypočítá hash hodnotu zadaného binárního proudu pomocí zadaného hash algoritmu a výsledek podepíše.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binární proud. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. vrací [DSA](../../dsa/) podpis pro vstupní data. |

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Třída [DSACryptoServiceProvider](../)
* Třída [Stream](../../../system.io/stream/)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)