---
title: Directory
second_title: Référence de l'API Aspose.Slides pour C++
description: Contient des méthodes pour manipuler les répertoires. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit.
type: docs
weight: 235
url: /fr/system.io/directory/
---
## Classe Directory


Contient des méthodes pour manipuler les répertoires. Il s’agit d’un type statique sans services d’instance. Vous ne devez jamais créer d’instances de celui-ci par quelque moyen que ce soit.

```cpp
class Directory
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | Crée tous les répertoires dans le chemin spécifié s’ils n’existent pas. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | Supprime le fichier ou répertoire spécifié. Ne lance pas d'exception. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Recherche les répertoires qui répondent aux critères de recherche spécifiés, soit dans le répertoire indiqué, soit dans l’ensemble de l’arborescence dont le répertoire indiqué est la racine. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Recherche les fichiers qui répondent aux critères de recherche spécifiés, soit dans le répertoire indiqué, soit dans l’ensemble de l’arborescence dont le répertoire indiqué est la racine. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Recherche les fichiers et répertoires qui répondent aux critères de recherche spécifiés, soit dans le répertoire indiqué, soit dans l’ensemble de l’arborescence dont le répertoire indiqué est la racine. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Détermine si le chemin spécifié fait référence à un répertoire existant. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Renvoie la date de création de l’entité spécifiée en heure locale. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Renvoie la date de création de l’entité spécifiée en temps UTC. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | Renvoie le nom complet (y compris le chemin) du répertoire courant. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Recherche les répertoires qui répondent aux critères de recherche spécifiés, soit dans le répertoire indiqué, soit dans l’ensemble de l’arborescence dont le répertoire indiqué est la racine. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | Renvoie le répertoire racine du chemin spécifié. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Recherche les fichiers qui répondent aux critères de recherche spécifiés, soit dans le répertoire indiqué, soit dans l’ensemble de l’arborescence dont le répertoire indiqué est la racine. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Recherche les fichiers et répertoires qui répondent aux critères de recherche spécifiés, soit dans le répertoire indiqué, soit dans l’ensemble de l’arborescence dont le répertoire indiqué est la racine. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Renvoie la date du dernier accès de l’entité spécifiée en heure locale. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Renvoie la date du dernier accès de l’entité spécifiée en temps UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Renvoie la date de la dernière écriture de l’entité spécifiée en heure locale. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Renvoie la date de la dernière écriture de l’entité spécifiée en temps UTC. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | NON IMPLEMENTÉ. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | Renvoie un pointeur partagé vers l’objet [DirectoryInfo](../directoryinfo/) représentant le répertoire parent de l’entité spécifiée. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Déplace l’entité spécifiée vers le nouvel emplacement. Si l’entité à déplacer est un répertoire, il est déplacé avec tout son contenu. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Définit la date de création de l’entité spécifiée en heure locale. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Définit la date de création de l’entité spécifiée en temps UTC. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | Définit le répertoire courant. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Définit la date du dernier accès de l’entité spécifiée en heure locale. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Définit la date du dernier accès de l’entité spécifiée en temps UTC. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Définit la date de la dernière écriture de l’entité spécifiée en heure locale. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Définit la date de la dernière écriture de l’entité spécifiée en temps UTC. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | Un alias pour un pointeur partagé vers un objet IEnumerable qui énumère un ensemble d’objets [String](../../system/string/). |

## Remarques



```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // Crée des chaînes contenant les chemins vers des répertoires.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Vérifie si les répertoires existent.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Affiche les informations du répertoire temporaire.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
Cet exemple de code produit la sortie suivante :
Le répertoire 'C:\' existe.
Le répertoire 'C:\Some directory' n'existe pas.
Le répertoire 'C:\Users\lanor\AppData\Local\Temp\' existe.
Creation Time: 27.08.2021 14:21:42
Last Access Time: 07.10.2021 12:16:41
Last Write Time: 07.10.2021 12:16:41
*/
```

## Voir aussi

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)