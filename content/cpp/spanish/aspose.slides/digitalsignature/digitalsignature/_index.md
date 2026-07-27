---
title: DigitalSignature()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea un nuevo objeto DigitalSignature con el certificado especificado.
type: docs
weight: 66
url: /es/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) constructor

Crea un nuevo objeto [DigitalSignature](../) con el certificado especificado.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | Certificado que se utilizará para firmar la presentación. |

## DigitalSignature::DigitalSignature(System::String, System::String) constructor

Crea un nuevo objeto [DigitalSignature](../) con la ruta del archivo de certificado y la contraseña especificados.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | Ruta al archivo con el certificado. |
| password | [System::String](../../../system/string/) | Contraseña necesaria para acceder al certificado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Clase [DigitalSignature](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)