---
title: DigitalSignature class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/digitalsignature/
---
## DigitalSignature classe

Assinatura digital em arquivo assinado.

O tipo DigitalSignature expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/pt/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | Cria um novo objeto DigitalSignature com o certificado especificado. |
| [`__init__(self, file_path, password)`](/slides/python-net/pt/aspose.slides/digitalsignature/__init__/#str-str) | Cria um novo objeto DigitalSignature com o caminho do arquivo de certificado especificado e a senha. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`certificate`](/slides/python-net/pt/aspose.slides/digitalsignature/certificate/) | Objeto de certificado que foi usado para assinar o documento.<br/>            Somente leitura **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/pt/aspose.slides/digitalsignature/is_valid/) | Se esta assinatura digital for válida e o documento não tiver sido adulterado, este valor será true.<br/>            Somente leitura **bool**. |
| [`sign_time`](/slides/python-net/pt/aspose.slides/digitalsignature/sign_time/) | A hora em que o documento foi assinado.<br/>            Somente leitura **System.DateTime**. |
| [`comments`](/slides/python-net/pt/aspose.slides/digitalsignature/comments/) | O propósito da assinatura.<br/>            Leitura/gravação **str**. |


### Ver também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)