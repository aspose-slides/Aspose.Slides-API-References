---
title: CreateDecryptor()
second_title: Referência da API Aspose.Slides para C++
description: Cria objeto descriptografador com parâmetros explícitos.
type: docs
weight: 14
url: /pt/system.security.cryptography/rc2managed/createdecryptor/
---
## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método

Cria objeto descriptografador com parâmetros explícitos.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Chave de criptografia em forma de array de bytes. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Valor inicial em forma de array de bytes. |

### Valor de Retorno

Objeto descriptografador recém-criado.

## RC2Managed::CreateDecryptor() método

Cria objeto descriptografador com parâmetros definidos pelo objeto algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método

Cria objeto descriptografador com parâmetros definidos pelo objeto algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICryptoTransform](../../icryptotransform/)
* Classe [RC2Managed](../)
* Espaço de nomes [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)