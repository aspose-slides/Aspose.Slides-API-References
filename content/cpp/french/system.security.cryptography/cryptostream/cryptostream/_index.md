---
title: CryptoStream()
second_title: Référence de l'API Aspose.Slides pour C++
description: Constructeur.
type: docs
weight: 1
url: /fr/system.security.cryptography/cryptostream/cryptostream/
---
## CryptoStream::CryptoStream(const SharedPtr\<System::IO::Stream\>\&, const SharedPtr\<ICryptoTransform\>\&, CryptoStreamMode) constructeur

Constructeur.

```cpp
System::Security::Cryptography::CryptoStream::CryptoStream(const SharedPtr<System::IO::Stream> &stream, const SharedPtr<ICryptoTransform> &transform, CryptoStreamMode mode)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Flux à envelopper. |
| transform | const [SharedPtr](../../../system/sharedptr/)\<[ICryptoTransform](../../icryptotransform/)\>\& | Fonction de transformation utilisée pour traiter les données lors de l'envoi ou de la lecture vers ou depuis le flux. |
| mode | [CryptoStreamMode](../../cryptostreammode/) | Direction du flux. |

## Voir aussi

* Enum [CryptoStreamMode](../../cryptostreammode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [ICryptoTransform](../../icryptotransform/)
* Classe [CryptoStream](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)