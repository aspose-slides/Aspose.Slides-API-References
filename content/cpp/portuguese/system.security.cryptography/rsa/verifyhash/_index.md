---
title: VerifyHash()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se a assinatura do hash especificado é válida.
type: docs
weight: 170
url: /pt/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) método


Verifica se a assinatura do hash especificado é válida.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Valor de hash dos dados assinados. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Dados da assinatura. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Modo de preenchimento. retorna true se a assinatura for válida, caso contrário - false. |

## Veja também

* Definição de tipo [ByteArrayPtr](../../../system/bytearrayptr/)
* Definição de tipo [SharedPtr](../../../system/sharedptr/)
* Classe [RSASignaturePadding](../../rsasignaturepadding/)
* Classe [RSA](../)
* Estrutura [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)