---
title: X509KeyUsageExtension()
second_title: Referência da API Aspose.Slides para C++
description: Construtor padrão.
type: docs
weight: 1
url: /pt/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() construtor

Construtor padrão.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) construtor

Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Dados codificados dos usos de chave. |
| critical | **bool** | Sinal de criticidade. |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) construtor

Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | Usos de chave. |
| critical | **bool** | Sinal de criticidade. |

## Veja também

* Enum [X509KeyUsageFlags](../../x509keyusageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [X509KeyUsageExtension](../)
* Classe [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Espaço de nomes [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)