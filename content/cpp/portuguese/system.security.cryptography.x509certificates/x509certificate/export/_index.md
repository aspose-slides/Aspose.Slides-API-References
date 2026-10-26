---
title: Export()
second_title: Referência da API Aspose.Slides para C++
description: Exporta o objeto atual para um array de bytes usando o formato especificado. NÃO IMPLEMENTADO.
type: docs
weight: 287
url: /pt/system.security.cryptography.x509certificates/x509certificate/export/
---
## X509Certificate::Export(X509ContentType) const method

Exporta o objeto atual para um array de bytes usando o formato especificado. NÃO IMPLEMENTADO.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type) const
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | Especifica como formatar os dados de saída. |

### Valor de Retorno

Um array de bytes que representa o objeto atual.

## X509Certificate::Export(X509ContentType, const SecureStringPtr\&) const method

Exporta o objeto atual para um array de bytes usando o formato especificado. NÃO IMPLEMENTADO.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const SecureStringPtr &password) const
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | Especifica como formatar os dados de saída. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | A senha necessária para acessar os dados do certificado. |

### Valor de Retorno

Um array de bytes que representa o objeto atual.

## X509Certificate::Export(X509ContentType, const String\&) const method

Exporta o objeto atual para um array de bytes usando o formato especificado. NÃO IMPLEMENTADO.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const String &password) const
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | Especifica como formatar os dados de saída. |
| password | const [String](../../../system/string/)\& | A senha necessária para acessar os dados do certificado. |

### Valor de Retorno

Um array de bytes que representa o objeto atual.

## Veja Também

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)