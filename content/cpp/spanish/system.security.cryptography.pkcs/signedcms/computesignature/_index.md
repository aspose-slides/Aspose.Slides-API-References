---
title: ComputeSignature()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una firma.
type: docs
weight: 14
url: /es/system.security.cryptography.pkcs/signedcms/computesignature/
---
## SignedCms::ComputeSignature(const SharedPtr\<CmsSigner\>\&, bool) método

Crea una firma.

```cpp
void System::Security::Cryptography::Pkcs::SignedCms::ComputeSignature(const SharedPtr<CmsSigner> &signer, bool silent)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signer | const [SharedPtr](../../../system/sharedptr/)\<[CmsSigner](../../cmssigner/)\>\& | Firmante a usar. |
| silent | **bool** | Indica si se debe suprimir la solicitud al usuario de un certificado válido si el certificado asociado con **signer** no es válido. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [CmsSigner](../../cmssigner/)
* Clase [SignedCms](../)
* Espacio de nombres [System::Security::Cryptography::Pkcs](../../)
* Library [Aspose.Slides](../../../)