---
title: SignData()
second_title: Aspose.Slides für C++ API-Referenz
description: Berechnet die Signatur des angegebenen Eingabewerts.
type: docs
weight: 183
url: /de/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) Methode

Berechnet die Signatur des angegebenen Eingabewerts.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) zum Lesen der Eingabedaten aus. |

### Rückgabewert

[DSA](../../dsa/) Signatur für die angegebenen Daten.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) Methode

Berechnet die Signatur des angegebenen Eingabewerts.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream, aus dem die zu signierenden Daten gelesen werden. |

### Rückgabewert

[DSA](../../dsa/) Signatur für die angegebenen Daten.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) Methode

Berechnet die Signatur des angegebenen Eingabewerts.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) zum Lesen der Eingabedaten aus. |
| offset | **int32_t** | Startindex des Eingabepufferabschnitts. |
| count | **int32_t** | Größe des Eingabepufferabschnitts. |

### Rückgabewert

[DSA](../../dsa/) Signatur für die angegebenen Daten.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) Methode

Berechnet den Hash-Wert des angegebenen Daten-Arrays mittels des angegebenen Hash-Algorithmus und signiert das Ergebnis.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Eingabedaten-Array. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Gibt [DSA](../../dsa/) Signatur für die Eingabedaten zurück. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) Methode

Berechnet den Hash-Wert des angegebenen Daten-Arrays mittels des angegebenen Hash-Algorithmus und signiert das Ergebnis.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Eingabedaten-Array. |
| offset | **int32_t** | Versatz in **data**. |
| count | **int32_t** | Anzahl der Bytes, die als Eingabedaten verwendet werden. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Gibt [DSA](../../dsa/) Signatur für die Eingabedaten zurück. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) Methode

Berechnet den Hash-Wert des angegebenen Binär-Streams mittels des angegebenen Hash-Algorithmus und signiert das Ergebnis.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binär-Stream. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Gibt [DSA](../../dsa/) Signatur für die Eingabedaten zurück. |

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klasse [DSACryptoServiceProvider](../)
* Klasse [Stream](../../../system.io/stream/)
* Struktur [HashAlgorithmName](../../hashalgorithmname/)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)