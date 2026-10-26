---
title: DigitalSignature class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/digitalsignature/
---
## DigitalSignature classe

Firma digitale in file firmato.

Il tipo DigitalSignature espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/it/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | Crea un nuovo oggetto DigitalSignature con il certificato specificato. |
| [`__init__(self, file_path, password)`](/slides/python-net/it/aspose.slides/digitalsignature/__init__/#str-str) | Crea un nuovo oggetto DigitalSignature con il percorso del file di certificato e la password specificati. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`certificate`](/slides/python-net/it/aspose.slides/digitalsignature/certificate/) | Oggetto certificato utilizzato per firmare il documento.<br/>            Read-only **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/it/aspose.slides/digitalsignature/is_valid/) | Se questa firma digitale è valida e il documento non è stato manomesso, questo valore sarà true.<br/>            Read-only **bool**. |
| [`sign_time`](/slides/python-net/it/aspose.slides/digitalsignature/sign_time/) | Il momento in cui il documento è stato firmato.<br/>            Read-only **System.DateTime**. |
| [`comments`](/slides/python-net/it/aspose.slides/digitalsignature/comments/) | Lo scopo della firma.<br/>            Read/write **str**. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)