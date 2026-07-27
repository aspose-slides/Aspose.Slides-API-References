---
title: CreateDecryptor()
second_title: Referência da API Aspose.Slides para C++
description: Cria um descriptografador com parâmetros associados ao objeto do algoritmo.
type: docs
weight: 196
url: /pt/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() método

Cria um descriptografador com parâmetros associados ao objeto do algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

### Valor de Retorno

Novo objeto descriptografador criado.

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método

Cria um descriptografador com parâmetros explícitos.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Chave a ser usada. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Valor inicial a ser usado. |

### Valor de Retorno

Novo objeto descriptografador criado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICryptoTransform](../../icryptotransform/)
* Classe [SymmetricAlgorithm](../)
* Espaço de nomes [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)