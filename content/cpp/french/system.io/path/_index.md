---
title: Path
second_title: Référence de l'API Aspose.Slides pour C++
description: Fournit des méthodes pour manipuler les chemins. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit.
type: docs
weight: 339
url: /fr/system.io/path/
---
## Path classe

Provides methods for manipulating paths. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Path
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Modifie l'extension dans le chemin de fichier spécifié. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Détermine si le chemin spécifié est valide en vérifiant s'il contient des caractères invalides. Une exception est levée si le chemin contient des caractères invalides. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Combine les segments de chemin spécifiés en un seul chemin en insérant des caractères de séparateur de répertoire entre les segments si nécessaire. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combine deux segments de chemin spécifiés en un seul chemin en insérant un caractère de séparateur de répertoire entre les segments si nécessaire. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combine trois segments de chemin spécifiés en un seul chemin en insérant des caractères de séparateur de répertoire entre les segments si nécessaire. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combine quatre segments de chemin spécifiés en un seul chemin en insérant des caractères de séparateur de répertoire entre les segments si nécessaire. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | Renvoie le nom du répertoire référencé par le chemin spécifié. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | Renvoie l'extension du fichier référencé par le chemin spécifié. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | Renvoie le nom du fichier référencé par le chemin spécifié. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | Renvoie le nom sans extension du fichier référencé par le chemin spécifié. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | Convertit le chemin spécifié en chemin absolu. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Renvoie un tableau contenant les caractères non autorisés dans les noms de fichiers. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | Renvoie un tableau contenant les caractères non autorisés dans les noms de chemins. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | Renvoie le répertoire racine du chemin spécifié. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | Renvoie un nom de fichier généré aléatoirement. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | Crée un nouveau fichier avec un nom unique et renvoie le chemin complet vers celui-ci. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | Crée un nouveau fichier avec un nom unique et renvoie le chemin complet vers celui-ci. Est un synonyme de la méthode [GetTempFileName_()](./gettempfilename_/). |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | Renvoie le chemin du répertoire temporaire de l'utilisateur actuel. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | Détermine si le chemin spécifié fait référence à un fichier avec une extension. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | Détermine si le chemin spécifié contient une racine. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | Normalise le chemin spécifié. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | Renvoie une instance de la classe boost::filesystem::path qui représente le chemin spécifié. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | Renvoie une représentation sous forme de chaîne de l'objet path de Boost spécifié. |

## Champs

| Champ | Description |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Un caractère alternatif utilisé pour séparer les niveaux de répertoires dans un chemin. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Un caractère utilisé pour séparer les niveaux de répertoires dans un chemin. |
| static [PathSeparator](./pathseparator/) | Un caractère séparateur utilisé pour séparer les chaînes de chemins dans les variables d'environnement. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Un caractère de séparateur de volume. |

## Remarques



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Génère un nom de fichier aléatoire.
  auto filename = Path::GetRandomFileName();

  // Affiche les informations sur le nom de fichier.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
Ce exemple de code produit la sortie suivante :
Nom de fichier : qhuzkyqv.y6p
Nom de fichier sans extension : qhuzkyqv
Extension : .y6p
*/
```

## Voir aussi

* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)