---
title: Create()
second_title: Referência da API Aspose.Slides para C++
description: Cria a implementação padrão do algoritmo DSA.
type: docs
weight: 105
url: /pt/system.security.cryptography/dsa/create/
---
## DSA::Create() método

Cria a implementação padrão do algoritmo [DSA](../).

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### Valor de Retorno

[DSA](../) objeto do algoritmo.

## DSA::Create(const String\&) método

Cria a implementação padrão do algoritmo [DSA](../).

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Deve ser "System.Security.Cryptography.DSACryptoServiceProvider". |

### Valor de Retorno

[DSA](../) objeto do algoritmo.

## DSA::Create(int32_t) método

Cria a implementação padrão do algoritmo [DSA](../) com o tamanho da chave especificado.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | O tamanho da chave, em bits. |

## DSA::Create(const DSAParameters\&) método

Cria a implementação padrão do algoritmo [DSA](../) com os parâmetros especificados.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | Os parâmetros para o algoritmo [DSA](../). |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [DSA](../)
* Classe [String](../../../system/string/)
* Struct [DSAParameters](../../dsaparameters/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)