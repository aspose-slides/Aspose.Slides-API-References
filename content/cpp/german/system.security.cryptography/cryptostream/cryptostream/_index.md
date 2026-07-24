---
title: CryptoStream()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruktor.
type: docs
weight: 1
url: /de/system.security.cryptography/cryptostream/cryptostream/
---
## CryptoStream::CryptoStream(const SharedPtr\<System::IO::Stream\>\&, const SharedPtr\<ICryptoTransform\>\&, CryptoStreamMode) Konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::CryptoStream::CryptoStream(const SharedPtr<System::IO::Stream> &stream, const SharedPtr<ICryptoTransform> &transform, CryptoStreamMode mode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Stream, der umschlossen werden soll. |
| transform | const [SharedPtr](../../../system/sharedptr/)\<[ICryptoTransform](../../icryptotransform/)\>\& | Transformationsfunktion zur Datenverarbeitung beim Senden/Lesen vom Stream. |
| mode | [CryptoStreamMode](../../cryptostreammode/) | Stream-Richtung. |

## Siehe auch

* Enum [CryptoStreamMode](../../cryptostreammode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [CryptoStream](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)