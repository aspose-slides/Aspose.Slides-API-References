---
title: VerifyHash()
second_title: Referência da API Aspose.Slides para C++
description: Verifica a assinatura dos dados.
type: docs
weight: 222
url: /pt/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) método


Verifica a assinatura dos dados.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash calculado para os dados recebidos. |
| str | const [String](../../../system/string/)\& | Nome do algoritmo de hash usado. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Assinatura recebida. |

### Valor de Retorno

Verdadeiro se a assinatura for válida, falso caso contrário.

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) método


Verifica se a assinatura do hash especificado é válida.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Valor de hash dos dados assinados. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Dados da assinatura. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Modo de preenchimento. retorna verdadeiro se a assinatura for válida, caso contrário - falso. |

## Ver Também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [RSACryptoServiceProvider](../)
* Classe [RSASignaturePadding](../../rsasignaturepadding/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Espaço de nomes [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)