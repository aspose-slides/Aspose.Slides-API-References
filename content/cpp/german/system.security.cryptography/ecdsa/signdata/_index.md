---
title: SignData()
second_title: Aspose.Slides für C++ API-Referenz
description: Berechnet den Hash-Wert des angegebenen Datenarrays mit dem angegebenen Hash-Algorithmus und signiert das Ergebnis.
type: docs
weight: 79
url: /de/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) Methode

Berechnet den Hash-Wert des angegebenen Datenarrays mit dem angegebenen Hash-Algorithmus und signiert das Ergebnis.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Eingabedaten-Array. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Gibt die ECDSA-Signatur für die Eingabedaten zurück. |

## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) Methode

Berechnet den Hash-Wert des angegebenen Datenarrays mit dem angegebenen Hash-Algorithmus und signiert das Ergebnis.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Eingabedaten-Array. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Anzahl der Bytes, die als Eingabedaten verwendet werden. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Gibt die ECDSA-Signatur für die Eingabedaten zurück. |

## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) Methode

Berechnet den Hash-Wert des angegebenen Binärstreams mit dem angegebenen Hash-Algorithmus und signiert das Ergebnis.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binärstream. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Gibt die ECDSA-Signatur für die Eingabedaten zurück. |

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klasse [ECDsa](../)
* Struktur [HashAlgorithmName](../../hashalgorithmname/)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)