---
title: Console
second_title: Référence API Aspose.Slides pour C++
description: Fournit des méthodes permettant d'écrire des données sur le flux de sortie standard. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par aucun moyen.
type: docs
weight: 196
url: /fr/system/console/
---
## Classe Console


Fournit des méthodes pour écrire des données sur le flux de sortie standard. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par aucun moyen.

```cpp
class Console
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static void [Beep](./beep/)() | NON IMPLEMENTÉ. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | Retourne un pointeur partagé pointant vers l'objet qui représente le flux d'erreur standard. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | Retourne un pointeur partagé pointant vers l'objet qui représente le flux d'entrée standard. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | Retourne un pointeur partagé pointant vers l'objet qui représente le flux de sortie standard. |
| static void [Mute](./mute/)(**bool**) | Coupe ou réactive le flux de sortie standard. |
| static void [ReadKey](./readkey/)() | NON IMPLEMENTÉ. |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | Définit la légende de la fenêtre de la console. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Assigne l'objet spécifié à la propriété Error de la classe. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | Définit la propriété In à l'objet TextReader spécifié. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Assigne l'objet spécifié à la propriété Out de la classe. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Écrit la représentation sous forme de chaîne de l'objet spécifié sur le flux de sortie standard. |
| static void [Write](./write/)(**bool**) | Écrit la représentation sous forme de chaîne de la valeur booléenne sur le flux de sortie standard. |
| static void [Write](./write/)(char_t) | Écrit la valeur de caractère spécifiée sur le flux de sortie standard. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Écrit la représentation sous forme de chaîne du tableau de caractères spécifié sur le flux de sortie standard. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | Écrit la représentation sous forme de chaîne de la valeur [Decimal](../decimal/) sur le flux de sortie standard. |
| static void [Write](./write/)(**double**) | Écrit la représentation sous forme de chaîne d'une valeur à virgule flottante en double précision sur le flux de sortie standard. |
| static void [Write](./write/)(**float**) | Écrit la représentation sous forme de chaîne d'une valeur à virgule flottante en simple précision sur le flux de sortie standard. |
| static void [Write](./write/)(**int32_t**) | Écrit la représentation sous forme de chaîne d'une valeur entière 32 bits sur le flux de sortie standard. |
| static void [Write](./write/)(**int64_t**) | Écrit la représentation sous forme de chaîne d'une valeur entière 64 bits sur le flux de sortie standard. |
| static void [Write](./write/)(const [String](../string/)\&) | Écrit l'objet string spécifié sur le flux de sortie standard. |
| static void [Write](./write/)(const char_t *) | Écrit la c-string spécifiée sur le flux de sortie standard. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | Écrit la représentation sous forme de chaîne de la valeur [TypeInfo](../typeinfo/) sur le flux de sortie standard. |
| static void [Write](./write/)(**uint32_t**) | Écrit la représentation sous forme de chaîne d'une valeur entière non signée 32 bits sur le flux de sortie standard. |
| static void [Write](./write/)(**uint64_t**) | Écrit la représentation sous forme de chaîne d'une valeur entière non signée 64 bits sur le flux de sortie standard. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Écrit la représentation sous forme de chaîne de la plage spécifiée du tableau de caractères spécifié sur le flux de sortie standard. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | Écrit la représentation sous forme de chaîne des arguments spécifiés formatés selon le format spécifié sur le flux de sortie standard. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | Écrit le terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Écrit la représentation sous forme de chaîne de l'objet spécifié suivie du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(**bool**) | Écrit la représentation sous forme de chaîne de la valeur booléenne suivie du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(char_t) | Écrit la valeur de caractère spécifiée suivie du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Écrit la représentation sous forme de chaîne du tableau de caractères spécifié suivi du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | Écrit la représentation sous forme de chaîne de la valeur [Decimal](../decimal/) suivie du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(**double**) | Écrit la représentation sous forme de chaîne d'une valeur à virgule flottante en double précision suivie du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(**float**) | Écrit la représentation sous forme de chaîne d'une valeur à virgule flottante en simple précision suivie du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(**int32_t**) | Écrit la représentation sous forme de chaîne d'une valeur entière 32 bits suivie du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(**int64_t**) | Écrit la représentation sous forme de chaîne d'une valeur entière 64 bits suivie du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | Écrit l'objet string spécifié suivi du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(const char_t *) | Écrit la c-string spécifiée suivie du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | Écrit la représentation sous forme de chaîne de la valeur [TypeInfo](../typeinfo/) suivie du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(**uint32_t**) | Écrit la représentation sous forme de chaîne d'une valeur entière non signée 32 bits suivie du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(**uint64_t**) | Écrit la représentation sous forme de chaîne d'une valeur entière non signée 64 bits suivie du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Écrit la représentation sous forme de chaîne de la plage spécifiée du tableau de caractères spécifié suivie du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | Écrit la représentation sous forme de chaîne de l'objet Exception spécifié suivi du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | Écrit la représentation sous forme de chaîne des arguments spécifiés formatés selon le format spécifié suivi du terminateur de ligne actuel sur le flux de sortie standard. |
| static void [WriteLine](./writeline/)(const char *) |  |
## Remarques



```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Affiche le message de bienvenue.
  Console::WriteLine(u"Hello, world!");

  // Crée une instance de la classe 'std::array'.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // Affiche les éléments du tableau.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
Cet exemple de code produit la sortie suivante :
Bonjour, le monde!
1 2 3 4 5
*/
```

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)