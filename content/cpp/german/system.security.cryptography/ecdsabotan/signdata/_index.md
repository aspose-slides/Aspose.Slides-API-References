---
title: SignData()
second_title: Aspose.Slides für C++ API-Referenz
description: Berechnet den Hashwert des angegebenen Datenarrays und signiert das Ergebnis.
type: docs
weight: 131
url: /de/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) Methode

Berechnet den Hashwert des angegebenen Datenarrays und signiert das Ergebnis.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Eingabedatenarray. Gibt die ECDSA-Signatur für die Eingabedaten zurück. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) Methode

Berechnet den Hashwert des angegebenen Datenarrays und signiert das Ergebnis.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Eingabedatenarray. |
| offset | **int32_t** | Versatz in **data**. |
| count | **int32_t** | Anzahl der Bytes, die als Eingabedaten verwendet werden. Gibt die ECDSA-Signatur für die Eingabedaten zurück. |

## ECDsaBotan::SignData(const StreamPtr\&) Methode

Berechnet den Hashwert des angegebenen Binärstroms und signiert das Ergebnis.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binärstrom. Gibt die ECDSA-Signatur für die Eingabedaten zurück. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) Methode

Berechnet den Hashwert des angegebenen Datenarrays mit dem angegebenen Hash-Algorithmus und signiert das Ergebnis.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Eingabedatenarray. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Gibt die ECDSA-Signatur für die Eingabedaten zurück. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) Methode

Berechnet den Hashwert des angegebenen Datenarrays mit dem angegebenen Hash-Algorithmus und signiert das Ergebnis.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Eingabedatenarray. |
| offset | **int32_t** | Versatz in **data**. |
| count | **int32_t** | Anzahl der Bytes, die als Eingabedaten verwendet werden. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Gibt die ECDSA-Signatur für die Eingabedaten zurück. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) Methode

Berechnet den Hashwert des angegebenen Binärstroms mit dem angegebenen Hash-Algorithmus und signiert das Ergebnis.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binärstrom. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. Gibt die ECDSA-Signatur für die Eingabedaten zurück. |

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klasse [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namensraum [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)