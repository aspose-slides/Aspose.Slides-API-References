---
title: CreateEncryptor()
second_title: Referência da API Aspose.Slides para C++
description: Cria um objeto criptografador com parâmetros explícitos.
type: docs
weight: 1
url: /pt/system.security.cryptography/tripledesmanaged/createencryptor/
---
## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método

Cria um objeto criptografador com parâmetros explícitos.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Chave de criptografia em forma de array de bytes. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Valor inicial em forma de array de bytes. |

### Valor de Retorno

Objeto criptografador recém-criado.

## TripleDESManaged::CreateEncryptor() método

Cria um objeto criptografador com parâmetros definidos pelo objeto algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método

Cria um objeto criptografador com parâmetros definidos pelo objeto algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICryptoTransform](../../icryptotransform/)
* Classe [TripleDESManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)