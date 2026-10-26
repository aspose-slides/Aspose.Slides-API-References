---
title: SignData()
second_title: Aspose.Slides C++ API-referencia
description: Számítja ki a megadott bemeneti érték aláírását.
type: docs
weight: 183
url: /hu/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) metódus

A megadott bemeneti érték aláírását számítja ki.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) a bemeneti adatok beolvasásához. |

### Visszatérési érték

[DSA](../../dsa/) aláírás a megadott adatokra.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) metódus

A megadott bemeneti érték aláírását számítja ki.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream a aláírandó adatok beolvasásához. |

### Visszatérési érték

[DSA](../../dsa/) aláírás a megadott adatokra.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) metódus

A megadott bemeneti érték aláírását számítja ki.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) a bemeneti adatok beolvasásához. |
| offset | **int32_t** | A bemeneti puffer szelet kezdőindexe. |
| count | **int32_t** | A bemeneti puffer szelet mérete. |

### Visszatérési érték

[DSA](../../dsa/) aláírás a megadott adatokra.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metódus

A megadott adat tömb hash értékét számítja ki a megadott hash algoritmussal, majd aláírja az eredményt.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Bemeneti adat tömb. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. Visszaadja a [DSA](../../dsa/) aláírást a bemeneti adatokra. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metódus

A megadott adat tömb hash értékét számítja ki a megadott hash algoritmussal, majd aláírja az eredményt.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Bemeneti adat tömb. |
| offset | **int32_t** | Offset a **data**-ban. |
| count | **int32_t** | A bemeneti adatként használandó bájtok száma. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. Visszaadja a [DSA](../../dsa/) aláírást a bemeneti adatokra. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) metódus

A megadott bináris adatfolyam hash értékét számítja ki a megadott hash algoritmussal, majd aláírja az eredményt.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Bináris adatfolyam. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. Visszaadja a [DSA](../../dsa/) aláírást a bemeneti adatokra. |

## Lásd még

* Típusdefiníció [ByteArrayPtr](../../../system/bytearrayptr/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [StreamPtr](../../../system/streamptr/)
* Osztály [DSACryptoServiceProvider](../)
* Osztály [Stream](../../../system.io/stream/)
* Struktúra [HashAlgorithmName](../../hashalgorithmname/)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)