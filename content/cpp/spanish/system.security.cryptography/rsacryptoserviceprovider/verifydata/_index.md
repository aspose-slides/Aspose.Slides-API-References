---
title: VerifyData()
second_title: Referencia de API de Aspose.Slides para C++
description: Comprueba la firma de los datos.
type: docs
weight: 209
url: /es/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) method


Comprueba la firma de los datos.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) para comprobar la firma. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Algoritmo hash a usar. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Firma tal como se recibió. |

### Valor de retorno

True si la firma es válida, false de lo contrario.

## Véase también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [RSACryptoServiceProvider](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)