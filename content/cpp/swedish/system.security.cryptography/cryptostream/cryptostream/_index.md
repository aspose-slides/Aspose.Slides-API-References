---
title: CryptoStream()
second_title: Aspose.Slides för C++ API-referens
description: Konstruktor.
type: docs
weight: 1
url: /sv/system.security.cryptography/cryptostream/cryptostream/
---
## CryptoStream::CryptoStream(const SharedPtr<System::IO::Stream>&, const SharedPtr<ICryptoTransform>&, CryptoStreamMode) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::CryptoStream::CryptoStream(const SharedPtr<System::IO::Stream> &stream, const SharedPtr<ICryptoTransform> &transform, CryptoStreamMode mode)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)<[System::IO::Stream](../../../system.io/stream/)>& | Ström att omsluta. |
| transform | const [SharedPtr](../../../system/sharedptr/)<[ICryptoTransform](../../icryptotransform/)>& | Transformationsfunktion för att bearbeta data vid sändning/läsning till/från ström. |
| mode | [CryptoStreamMode](../../cryptostreammode/) | Strömriktning. |

## Se också

* Enum [CryptoStreamMode](../../cryptostreammode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Stream](../../../system.io/stream/)
* Klass [ICryptoTransform](../../icryptotransform/)
* Klass [CryptoStream](../)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)