---
title: VerifySignature()
second_title: Referência da API Aspose.Slides para C++
description: Verifica a assinatura DSA para os dados especificados.
type: docs
weight: 118
url: /pt/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) método

Verifique a assinatura [DSA](../../dsa/) para os dados especificados.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) assinada com **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) assinatura. |

### Valor de Retorno

true - se **rgb_signature** corresponder à assinatura [DSA](../../dsa/) computada em **rgb_hash**, caso contrário - false.

## Veja Também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)