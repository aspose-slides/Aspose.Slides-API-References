---
title: ECDsaBotan()
second_title: Referência da API Aspose.Slides para C++
description: Construtor. Usa parâmetros padrão.
type: docs
weight: 1
url: /pt/system.security.cryptography/ecdsabotan/ecdsabotan/
---
## ECDsaBotan::ECDsaBotan() construtor

Construtor. Usa parâmetros padrão.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan()
```

## ECDsaBotan::ECDsaBotan(const ECParameters\&) construtor

Construtor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECParameters &parameters)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Parâmetros do algoritmo. |

## ECDsaBotan::ECDsaBotan(const ECCurve\&) construtor

Construtor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECCurve &curve)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Curva usada para criar o par de chaves pública/privada. |

## ECDsaBotan::ECDsaBotan(int32_t) construtor

Construtor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(int32_t key_size)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key_size | **int32_t** | Tamanho da chave em bits. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey\&) construtor

Construtor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey &key)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key | const Botan::ECDSA_PublicKey\& | Chave pública Botan. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey\&) construtor

Construtor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey &key)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key | const Botan::ECDSA_PrivateKey\& | Chave privada Botan. |

## Veja Também

* Classe [ECDsaBotan](../)
* Estrutura [ECParameters](../../ecparameters/)
* Estrutura [ECCurve](../../eccurve/)
* Namespace [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)