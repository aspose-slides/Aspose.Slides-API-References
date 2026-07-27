---
title: GetNameInfo()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o nome do assunto ou do emissor do certificado.
type: docs
weight: 248
url: /pt/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const method


Obtém o nome do assunto ou do emissor do certificado.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | Opções de formatação de nome. |
| for_issuer | **bool** | Se verdadeiro, retorna o nome do emissor; caso contrário, retorna o nome do assunto. |

### Valor de Retorno

Nome formatado do emissor ou do assunto.

## Veja Também

* Enum [X509NameType](../../x509nametype/)
* Classe [String](../../../system/string/)
* Classe [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Biblioteca [Aspose.Slides](../../../)