---
title: GetCertContentType()
second_title: Referência de API Aspose.Slides para C++
description: Obtém o tipo de certificado contido no array de bytes especificado.
type: docs
weight: 391
url: /pt/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) método


Obtém o tipo de certificado contido no array de bytes especificado.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados do certificado. |

### Valor de Retorno

Tipo de certificado X.509.

## X509Certificate2::GetCertContentType(const String\&) método


Obtém o tipo de certificado contido no arquivo especificado.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nome do arquivo de certificado. |

### Valor de Retorno

Tipo de certificado X.509.

## Veja Também

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [X509Certificate2](../)
* Classe [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Biblioteca [Aspose.Slides](../../../)