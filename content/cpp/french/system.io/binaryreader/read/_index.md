---
title: Read()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lit un seul caractère depuis le flux d'entrée.
type: docs
weight: 66
url: /fr/system.io/binaryreader/read/
---
## BinaryReader::Read() méthode


Lit un seul caractère depuis le flux d'entrée.

```cpp
virtual int System::IO::BinaryReader::Read()
```


### Valeur de retour

Caractère lu encodé en UTF-16 ; si le caractère lu est représenté par deux points de code en UTF-16, seul le surrogat haut est renvoyé.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) méthode


Lit le nombre spécifié d'octets depuis le flux d'entrée et les écrit dans le tableau d'octets indiqué.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets où écrire les octets lus |
| index | int | Une position basée sur zéro dans **buffer** où commencer l'écriture |
| count | int | Le nombre d'octets à lire |

### Valeur de retour

Le nombre d'octets lus

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) méthode


Lit le nombre spécifié de caractères depuis le flux d'entrée, les convertit en encodage UTF-16 et écrit les caractères UTF-16 résultants dans le tableau de caractères indiqué à partir de la position spécifiée.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Le tableau de caractères UTF-16 où écrire les caractères lus depuis le flux d'entrée |
| index | int | Un indice basé sur zéro dans **buffer** où commencer l'écriture |
| count | int | Le nombre de caractères à lire depuis le flux |

### Valeur de retour

Le nombre de caractères lus depuis le flux d'entrée

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BinaryReader](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)