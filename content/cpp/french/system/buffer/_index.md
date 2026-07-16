---
title: Buffer
second_title: Référence de l'API Aspose.Slides pour C++
description: Contient des méthodes qui manipulent des tableaux d'octets bruts. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de ce type, quel que soit le moyen.
type: docs
weight: 144
url: /fr/system/buffer/
---
## Classe Buffer


Contient des méthodes qui manipulent des tableaux d'octets bruts. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci, quel que soit le moyen.

```cpp
class Buffer
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | Copie un nombre spécifié d'octets du tampon source vers le tampon de destination. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interprète deux tableaux typés spécifiés comme des tableaux bruts d'octets et copie les données de l'un à l'autre. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | Interprète deux tableaux spécifiés comme des tableaux bruts d'octets et copie les données de l'un à l'autre. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interprète deux tableaux typés spécifiés comme des tableaux bruts d'octets et copie les données de l'un à l'autre. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interprète deux tableaux typés spécifiés comme des tableaux bruts d'octets et copie les données de l'un à l'autre. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interprète deux tableaux typés spécifiés comme des tableaux bruts d'octets et copie les données de l'un à l'autre. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interprète deux tableaux typés spécifiés comme des tableaux bruts d'octets et copie les données de l'un à l'autre. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interprète deux tableaux typés spécifiés comme des tableaux bruts d'octets et copie les données de l'un à l'autre. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interprète deux tableaux typés spécifiés comme des tableaux bruts d'octets et copie les données de l'un à l'autre. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | Détermine le nombre d'octets occupés par tous les éléments du tableau spécifié. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Détermine le nombre d'octets occupés par tous les éléments du tableau spécifié. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Détermine le nombre d'octets occupés par tous les éléments du tableau spécifié. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | Interprète le tableau typé spécifié comme un tableau brut d'octets et récupère la valeur d'octet à l'offset d'octet spécifié. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | Interprète le tableau typé spécifié comme un tableau brut d'octets et récupère la valeur d'octet à l'offset d'octet spécifié. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | Interprète le tableau typé spécifié comme un tableau brut d'octets et récupère la valeur d'octet à l'offset d'octet spécifié. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | Interprète le tableau typé spécifié comme un tableau brut d'octets et définit la valeur d'octet spécifiée à l'offset d'octet spécifié. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | Interprète le tableau typé spécifié comme un tableau brut d'octets et définit la valeur d'octet spécifiée à l'offset d'octet spécifié. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | Interprète le tableau typé spécifié comme un tableau brut d'octets et définit la valeur d'octet spécifiée à l'offset d'octet spécifié. |
## Remarques



```cpp
#include <system/buffer.h>

using namespace System;

void Print(const SmartPtr<Array<uint8_t>> &source, int size)
{
  for (auto i = 0; i < size; i++)
  {
    std::cout << static_cast<int>(source[i]) << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Créer et remplir le tableau.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // Afficher les éléments du tableau.
  Print(first, SIZE);

  // Créer un tableau contenant une partie du premier.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // Afficher les éléments du deuxième tableau.
  Print(second, SIZE / 2);

  // Définir la valeur de l'élément à l'index 0 et afficher les éléments du tableau.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
Cet exemple de code produit la sortie suivante :
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)