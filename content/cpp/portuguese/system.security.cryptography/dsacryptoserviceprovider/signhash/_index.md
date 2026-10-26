---
title: SignHash()
second_title: Referência da API Aspose.Slides para C++
description: Computa a assinatura do valor de entrada especificado.
type: docs
weight: 196
url: /pt/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) método

Computa a assinatura do valor de entrada especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Valor hash dos dados a ser assinado. |
| str | const [String](../../../system/string/)\& | Identificador do algoritmo de hash usado para criar o hash. |

### Valor de Retorno

[DSA](../../dsa/) assinatura para os dados especificados.

## Veja Também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [String](../../../system/string/)
* Classe [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)