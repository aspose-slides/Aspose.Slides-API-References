---
title: CryptoStream()
second_title: Referencia de API de Aspose.Slides para C++
description: Constructor.
type: docs
weight: 1
url: /es/system.security.cryptography/cryptostream/cryptostream/
---
## CryptoStream::CryptoStream(const SharedPtr\<System::IO::Stream\>\&, const SharedPtr\<ICryptoTransform\>\&, CryptoStreamMode) constructor


Constructor.

```cpp
System::Security::Cryptography::CryptoStream::CryptoStream(const SharedPtr<System::IO::Stream> &stream, const SharedPtr<ICryptoTransform> &transform, CryptoStreamMode mode)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Flujo a envolver. |
| transform | const [SharedPtr](../../../system/sharedptr/)\<[ICryptoTransform](../../icryptotransform/)\>\& | Función de transformación para procesar datos al enviarlos/leerlos al/de flujo. |
| mode | [CryptoStreamMode](../../cryptostreammode/) | Dirección del flujo. |

## Véase también

* Enum [CryptoStreamMode](../../cryptostreammode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Stream](../../../system.io/stream/)
* Clase [ICryptoTransform](../../icryptotransform/)
* Clase [CryptoStream](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)