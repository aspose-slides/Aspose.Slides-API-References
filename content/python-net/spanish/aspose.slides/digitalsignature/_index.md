---
title: DigitalSignature class
second_title: Aspose.Slides para Python a través de la API de .NET
description: 
type: docs
url: /es/aspose.slides/digitalsignature/
---
## DigitalSignature clase

Firma digital en archivo firmado.

El tipo DigitalSignature expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/es/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | Crea un nuevo objeto DigitalSignature con el certificado especificado. |
| [`__init__(self, file_path, password)`](/slides/python-net/es/aspose.slides/digitalsignature/__init__/#str-str) | Crea un nuevo objeto DigitalSignature con la ruta del archivo de certificado especificada y la contraseña. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`certificate`](/slides/python-net/es/aspose.slides/digitalsignature/certificate/) | Objeto de certificado que se utilizó para firmar el documento.<br/>            Solo lectura **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/es/aspose.slides/digitalsignature/is_valid/) | Si esta firma digital es válida y el documento no ha sido manipulado, este valor será true.<br/>            Solo lectura **bool**. |
| [`sign_time`](/slides/python-net/es/aspose.slides/digitalsignature/sign_time/) | La hora en que se firmó el documento.<br/>            Solo lectura **System.DateTime**. |
| [`comments`](/slides/python-net/es/aspose.slides/digitalsignature/comments/) | El propósito de la firma.<br/>            Lectura/escritura **str**. |


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)