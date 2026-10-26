---
title: SignData()
second_title: Aspose.Slides für C++ API-Referenz
description: Berechnet die Signatur des angegebenen Eingabewerts.
type: docs
weight: 183
url: /de/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) Methode


Berechnet die Signatur des angegebenen Eingabewerts.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) zum Lesen von Eingabedaten aus. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hash-Algorithmus, der verwendet werden soll. |

### Rückgabewert

[RSA](../../rsa/) Signatur für die angegebenen Daten.

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) Methode


Berechnet die Signatur des angegebenen Eingabewerts.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream zum Lesen der zu signierenden Daten. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hash-Algorithmus, der verwendet werden soll. |

### Rückgabewert

[RSA](../../rsa/) Signatur für die angegebenen Daten.

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) Methode


Berechnet die Signatur des angegebenen Eingabewerts.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) zum Lesen von Eingabedaten aus. |
| offset | **int32_t** | Eingabepuffer-Abschnitt Anfangsindex. |
| count | **int32_t** | Eingabepuffer-Abschnitt Größe. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hash-Algorithmus, der verwendet werden soll. |

### Rückgabewert

[RSA](../../rsa/) Signatur für die angegebenen Daten.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [RSACryptoServiceProvider](../)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)