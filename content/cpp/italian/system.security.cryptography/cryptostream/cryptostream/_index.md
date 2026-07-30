---
title: CryptoStream()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruttore.
type: docs
weight: 1
url: /it/system.security.cryptography/cryptostream/cryptostream/
---
## CryptoStream::CryptoStream(const SharedPtr\<System::IO::Stream\>\&, const SharedPtr\<ICryptoTransform\>\&, CryptoStreamMode) costruttore

Costruttore.

```cpp
System::Security::Cryptography::CryptoStream::CryptoStream(const SharedPtr<System::IO::Stream> &stream, const SharedPtr<ICryptoTransform> &transform, CryptoStreamMode mode)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Stream da avvolgere. |
| transform | const [SharedPtr](../../../system/sharedptr/)\<[ICryptoTransform](../../icryptotransform/)\>\& | Funzione di trasformazione per elaborare i dati quando inviati/letti dallo stream. |
| mode | [CryptoStreamMode](../../cryptostreammode/) | Direzione dello stream. |

## Vedi anche

* Enum [CryptoStreamMode](../../cryptostreammode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [ICryptoTransform](../../icryptotransform/)
* Classe [CryptoStream](../)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Libreria [Aspose.Slides](../../../)