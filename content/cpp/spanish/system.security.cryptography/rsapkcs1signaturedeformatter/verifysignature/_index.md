---
title: VerifySignature()
second_title: Referencia de API de Aspose.Slides para C++
description: Verifica la firma del hash de los datos.
type: docs
weight: 40
url: /es/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

Verifica la firma del hash de los datos.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hash calculado para los datos. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Firma recibida para los datos. |

### Valor devuelto

True si la firma es válida, false de lo contrario.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [RSAPKCS1SignatureDeformatter](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)