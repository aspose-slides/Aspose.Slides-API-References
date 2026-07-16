---
title: OperatingSystem
second_title: Référence API Aspose.Slides pour C++
description: "Représente un système d'exploitation particulier et fournit des informations à son sujet. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défaillances d'assertion. Encapsulez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 1158
url: /fr/system/operatingsystem/
---
## classe OperatingSystem

Représente un système d'exploitation particulier et fournit des informations à son sujet. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Encapsulez toujours cette classe dans un pointeur [System::SmartPtr](../smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument.

```cpp
class OperatingSystem
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | Renvoie l'identifiant de la plateforme du système d'exploitation représenté par l'objet actuel. |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | Renvoie le nom du service pack du système d'exploitation représenté par l'objet actuel. |
| const [Version](../version/)\& [get_Version](./get_version/)() const | Renvoie une référence constante à un objet [Version](../version/) représentant la version du système d'exploitation représenté par l'objet actuel. |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | Renvoie la représentation sous forme de chaîne de la version du système d'exploitation représenté par l'objet actuel. |
| static **bool** [IsFreeBSD](./isfreebsd/)() | Indique si l'application actuelle s'exécute sous FreeBSD. |
| static **bool** [IsLinux](./islinux/)() | Indique si l'application actuelle s'exécute sous Linux. |
| static **bool** [IsMacOS](./ismacos/)() | Indique si l'application actuelle s'exécute sous MacOS. |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | Indique si l'application actuelle s'exécute sur la plateforme spécifiée. |
| static **bool** [IsWindows](./iswindows/)() | Indique si l'application actuelle s'exécute sur [Windows](../../system.windows/). |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | Construit une instance qui représente un système d'exploitation spécifié par un identifiant de plateforme particulier et une version. |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | Construit une instance qui représente un système d'exploitation spécifié par un identifiant de plateforme particulier, une version et un service pack. |
| [String](../string/) [ToString](./tostring/)() const | Renvoie la représentation sous forme de chaîne de la version du système d'exploitation représenté par l'objet actuel. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)