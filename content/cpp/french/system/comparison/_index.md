---
title: Comparison
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente un pointeur vers la méthode qui compare deux objets du même type. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer des objets de ce type."
type: docs
weight: 183
url: /fr/system/comparison/
---
## Classe de comparaison

Représente un pointeur vers la méthode qui compare deux objets du même type. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe [System::SmartPtr](../smartptr/) pour gérer des objets de ce type.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des objets que la méthode compare |
## Méthodes

| Méthode | Description |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | Appelle l'objet invoquable pointé par l'objet actuel. |
## Remarques

```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// La classe modèle qui représente un tableau dynamique.
template <typename T>
class MyArray
{
  // Utilisé pour stocker les données du tableau.
  std::vector<T> m_data;

public:
  // Construit une nouvelle instance de notre tableau dynamique.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // Utilisé pour trier les données du tableau. Cette méthode accepte une instance de
  // la classe modèle 'System::Comparison'.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // Retourne le nombre d'éléments que notre tableau dynamique stocke.
  size_t get_Size()
  {
    return m_data.size();
  }

  // Utilisé pour obtenir un élément à l'index spécifié.
  T& operator[](int index)
  {
    if (index < 0 || index >= m_data.size())
    {
      throw IndexOutOfRangeException(u"index");
    }
    return m_data[index];
  }
};

int main() {
  // Crée une instance de la classe MyArray avec les éléments spécifiés.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // Trie les éléments du tableau dynamique par ordre croissant.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // Affiche les éléments du tableau dynamique.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
Cet exemple de code produit la sortie suivante :
a
b
c
d
e
*/
```

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)