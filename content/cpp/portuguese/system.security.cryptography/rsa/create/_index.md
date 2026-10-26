---
title: Create()
second_title: Referência da API do Aspose.Slides para C++
description: Cria a implementação padrão do algoritmo RSA.
type: docs
weight: 183
url: /pt/system.security.cryptography/rsa/create/
---
## RSA::Create() método


Cria a implementação padrão do algoritmo [RSA](../).

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) método


Cria a implementação padrão do algoritmo [RSA](../).

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Deve ser \"System.Security.Cryptography.RSACryptoServiceProvider\". |

## RSA::Create(int32_t) método


Cria a implementação padrão do algoritmo [RSA](../) com o tamanho de chave especificado.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | O tamanho da chave, em bits. |

## RSA::Create(const RSAParameters\&) método


Cria a implementação padrão do algoritmo [RSA](../) com os parâmetros especificados.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | Os parâmetros para o algoritmo [RSA](../). |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSA](../)
* Class [String](../../../system/string/)
* Struct [RSAParameters](../../rsaparameters/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)