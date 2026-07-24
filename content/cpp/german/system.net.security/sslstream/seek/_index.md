---
title: Seek()
second_title: Aspose.Slides für C++ API Referenz
description: Legt die Position des Streams fest, der durch das aktuelle Objekt dargestellt wird.
type: docs
weight: 365
url: /de/system.net.security/sslstream/seek/
---
## SslStream::Seek(int64_t, IO::SeekOrigin) Methode


Legt die Position des Streams fest, der durch das aktuelle Objekt dargestellt wird.

```cpp
int64_t System::Net::Security::SslStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| offset | **int64_t** | Der Byte-Versatz relativ zu einer durch **origin** angegebenen Position |
| origin | [IO::SeekOrigin](../../../system.io/seekorigin/) | Gibt die Position an, von der aus und die Richtung, in die der Versatz berechnet wird |

### Rückgabewert

Die neue Position des Streams

## Siehe auch

* Aufzählung [SeekOrigin](../../../system.io/seekorigin/)
* Klasse [SslStream](../)
* Namensraum [System::Net::Security](../../)
* Bibliothek [Aspose.Slides](../../../)