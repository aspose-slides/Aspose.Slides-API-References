---
title: CreateSignature()
second_title: Referência da API Aspose.Slides para C++
description: Cria a assinatura para os dados especificados.
type: docs
weight: 1
url: /pt/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) método


Cria a assinatura para os dados especificados.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) para calcular o hash de. |

### Valor de Retorno

Assinatura calculada em forma de array de bytes.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) método


Cria a assinatura para o valor de hash especificado.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Algoritmo de hash a ser usado ao criar a assinatura. |

### Valor de Retorno

Assinatura calculada em forma de array de bytes.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [AsymmetricSignatureFormatter](../)
* Classe [HashAlgorithm](../../hashalgorithm/)
* Namespace [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)