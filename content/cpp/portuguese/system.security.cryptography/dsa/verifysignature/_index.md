---
title: VerifySignature()
second_title: Referência da API Aspose.Slides para C++
description: Verifique a assinatura DSA para os dados especificados.
type: docs
weight: 14
url: /pt/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) method

Verifique a assinatura [DSA](../) para os dados especificados.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) assinatura assinada com **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) assinatura. |

### Valor de Retorno

true - se **rgb_signature** corresponde ao [DSA](../) assinatura calculada em **rgb_hash**, caso contrário - false.

## Veja Também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)