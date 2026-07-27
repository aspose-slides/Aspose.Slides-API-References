---
title: Create()
second_title: Referência da API Aspose.Slides para C++
description: Cria a implementação padrão do algoritmo ECDSA.
type: docs
weight: 131
url: /pt/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() método


Cria a implementação padrão do algoritmo ECDSA.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```


### Valor de retorno

Objeto do algoritmo ECDSA.

## ECDsa::Create(const ECCurve\&) método


Cria a implementação padrão do algoritmo ECDSA com uma chave recém-criada sobre a curva especificada.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Curva a ser usada para a criação da chave. |

### Valor de retorno

Objeto do algoritmo ECDSA.

## ECDsa::Create(const ECParameters\&) método


Cria a implementação padrão do algoritmo ECDSA usando os parâmetros especificados.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Parâmetros que representam a chave. |

### Valor de retorno

Objeto do algoritmo ECDSA.

## ECDsa::Create(const String\&) método


Cria a implementação especificada do algoritmo ECDSA.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | Nome do algoritmo. |

### Valor de retorno

Objeto do algoritmo ECDSA.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ECDsa](../)
* Classe [String](../../../system/string/)
* Estrutura [ECCurve](../../eccurve/)
* Estrutura [ECParameters](../../ecparameters/)
* Espaço de nomes [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)