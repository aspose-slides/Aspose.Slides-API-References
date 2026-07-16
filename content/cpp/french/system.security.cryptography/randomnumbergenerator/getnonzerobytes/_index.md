---
title: GetNonZeroBytes()
second_title: Référence de l'API Aspose.Slides pour C++
description: Remplit les éléments du tableau existant avec des octets aléatoires non nuls.
type: docs
weight: 27
url: /fr/system.security.cryptography/randomnumbergenerator/getnonzerobytes/
---
## RandomNumberGenerator::GetNonZeroBytes(ArrayPtr\<uint8_t\>) méthode


Remplit les éléments du tableau existant avec des octets aléatoires non nuls.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(ArrayPtr<uint8_t> bytes)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tableau d'octets à remplir. |

## RandomNumberGenerator::GetNonZeroBytes(System::Details::ArrayView\<uint8_t\>) méthode


Remplit les éléments de la vue de tableau existante avec des octets aléatoires non nuls.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(System::Details::ArrayView<uint8_t> bytes)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Vue de tableau d'octets à remplir. |

## RandomNumberGenerator::GetNonZeroBytes(System::Details::StackArray\<uint8_t, N\>\&) méthode


Remplit les éléments du tableau empilé existant avec des octets aléatoires non nuls.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(System::Details::StackArray<uint8_t, N> &bytes)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Tableau empilé d'octets à remplir. |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [RandomNumberGenerator](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)