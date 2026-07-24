---
title: SignData()
second_title: Aspose.Slides für C++ API-Referenz
description: Berechnet den Hashwert des angegebenen Datenarrays mit dem angegebenen Hash-Algorithmus und signiert das Ergebnis.
type: docs
weight: 79
url: /de/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) Methode

Berechnet den Hashwert des angegebenen Datenarrays mit dem angegebenen Hash-Algorithmus und signiert das Ergebnis.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Eingabedaten-Array. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. gibt [DSA](../) Signatur für die Eingabedaten zurück. |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) Methode

Berechnet den Hashwert des angegebenen Datenarrays mit dem angegebenen Hash-Algorithmus und signiert das Ergebnis.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Eingabedaten-Array. |
| offset | **int32_t** | Versatz in **data**. |
| count | **int32_t** | Anzahl der Bytes, die als Eingabedaten verwendet werden. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. gibt [DSA](../) Signatur für die Eingabedaten zurück. |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) Methode

Berechnet den Hashwert des angegebenen Binärstreams mit dem angegebenen Hash-Algorithmus und signiert das Ergebnis.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binärer Stream. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. gibt [DSA](../) Signatur für die Eingabedaten zurück. |

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)