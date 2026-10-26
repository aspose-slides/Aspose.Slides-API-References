---
title: VerifySignature()
second_title: Referencia de API de Aspose.Slides para C++
description: Verifica la firma en los datos.
type: docs
weight: 27
url: /es/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método


Verifica la firma en los datos.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) signed with **rgbSignature**. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Signature to be verified for data. |

### Valor devuelto

True if signature check succeeds, false otherwise.

## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) método


Verifica la firma en los datos. Not implemented.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Algoritmo a usar para el hash. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Firma a verificar para los datos. |

### Valor devuelto

True if signature check succeeds, false otherwise.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [AsymmetricSignatureDeformatter](../)
* Clase [HashAlgorithm](../../hashalgorithm/)
* Espacio de nombres [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)