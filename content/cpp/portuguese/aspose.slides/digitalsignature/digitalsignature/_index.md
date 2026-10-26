---
title: DigitalSignature()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo objeto DigitalSignature com o certificado especificado.
type: docs
weight: 66
url: /pt/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) construtor

Cria um novo objeto [DigitalSignature](../) com o certificado especificado.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | Certificado que será usado para assinar a apresentação. |

## DigitalSignature::DigitalSignature(System::String, System::String) construtor

Cria um novo objeto [DigitalSignature](../) com o caminho do arquivo de certificado e a senha especificados.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | Caminho para o arquivo com o certificado. |
| password | [System::String](../../../system/string/) | Senha necessária para acessar o certificado. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [DigitalSignature](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)