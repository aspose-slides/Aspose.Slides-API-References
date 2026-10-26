---
title: X509KeyUsageFlags
second_title: Referência da API Aspose.Slides para C++
description: Define como a chave do certificado pode ser usada.
type: docs
weight: 274
url: /pt/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum

Define como a chave do certificado pode ser usada.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| None | 0 | Nenhum parâmetro de uso da chave. |
| EncipherOnly | 1 | A chave pode ser usada apenas para criptografia. |
| CrlSign | 2 | A chave pode ser usada para assinar uma lista de revogação de certificados. |
| KeyCertSign | 4 | A chave pode ser usada para assinar certificados. |
| KeyAgreement | 8 | A chave pode ser usada para determinar o acordo de chave. |
| DataEncipherment | 16 | A chave pode ser usada para criptografia de dados. |
| KeyEncipherment | 32 | A chave pode ser usada para criptografia de chave. |
| NonRepudiation | 64 | A chave pode ser usada para autenticação. |
| DigitalSignature | 128 | A chave pode ser usada como assinatura digital. |
| DecipherOnly | 32768 | A chave pode ser usada apenas para descriptografia. |

## Ver também

* Namespace [System::Security::Cryptography::X509Certificates](../)
* Biblioteca [Aspose.Slides](../../)