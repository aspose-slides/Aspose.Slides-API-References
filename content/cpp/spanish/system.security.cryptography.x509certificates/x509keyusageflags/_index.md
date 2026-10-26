---
title: X509KeyUsageFlags
second_title: Referencia de API de Aspose.Slides para C++
description: Define cómo se puede usar la clave del certificado.
type: docs
weight: 274
url: /es/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum

Define cómo se puede usar la clave del certificado.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### Valores

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Sin parámetros de uso de clave. |
| EncipherOnly | 1 | La clave solo se puede usar para cifrado. |
| CrlSign | 2 | La clave puede usarse para firmar una lista de revocación de certificados. |
| KeyCertSign | 4 | La clave puede usarse para firmar certificados. |
| KeyAgreement | 8 | La clave puede usarse para determinar el acuerdo de claves. |
| DataEncipherment | 16 | La clave puede usarse para el cifrado de datos. |
| KeyEncipherment | 32 | La clave puede usarse para el cifrado de claves. |
| NonRepudiation | 64 | La clave puede usarse para autenticación. |
| DigitalSignature | 128 | La clave puede usarse como firma digital. |
| DecipherOnly | 32768 | La clave solo se puede usar para descifrado. |

## Ver también

* Espacio de nombres [System::Security::Cryptography::X509Certificates](../)
* Biblioteca [Aspose.Slides](../../)