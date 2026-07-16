---
title: GetBytes()
second_title: Référence de l'API Aspose.Slides pour C++
description: Remplit les éléments du tableau existant avec des octets aléatoires.
type: docs
weight: 14
url: /fr/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) méthode


Remplit les éléments du tableau existant avec des octets aléatoires.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tableau d'octets à remplir. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) méthode


Remplit une tranche du tableau existant avec des octets aléatoires.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tranche du tableau d'octets à remplir. |
| offset | int | Indice de début de la tranche. |
| count | int | Taille de la tranche. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) méthode


Remplit les éléments de la vue de tableau existante avec des octets aléatoires.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Vue du tableau d'octets à remplir. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) méthode


Remplit une tranche de la vue de tableau existante avec des octets aléatoires.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Tranche de la vue du tableau d'octets à remplir. |
| offset | int | Indice de début de la tranche. |
| count | int | Taille de la tranche. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) méthode


Remplit les éléments du tableau empilé existant avec des octets aléatoires.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Tableau empilé d'octets à remplir. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) méthode


Remplit une tranche du tableau empilé existant avec des octets aléatoires.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Tranche du tableau empilé d'octets à remplir. |
| offset | int | Indice de début de la tranche. |
| count | int | Taille de la tranche. |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [RandomNumberGenerator](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)