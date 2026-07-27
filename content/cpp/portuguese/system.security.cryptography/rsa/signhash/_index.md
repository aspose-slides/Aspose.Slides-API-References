---
title: SignHash()
second_title: Referência da API Aspose.Slides para C++
description: Calcula a assinatura para o valor de hash especificado.
type: docs
weight: 144
url: /pt/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) método

Calcula a assinatura para o valor de hash especificado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Valor do hash. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algoritmo de hash. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Modo de preenchimento. retorna [RSA](../) assinatura para o hash especificado. |

## Veja Também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)