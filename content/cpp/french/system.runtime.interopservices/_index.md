---
title: "System::Runtime::InteropServices"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 781
url: /fr/system.runtime.interopservices/
---
## Classes

| Class | Description |
| --- | --- |
| [Details_ExternalException](./details_externalexception/) | Le type d'exception de base pour toutes les exceptions d'interop COM et les exceptions de gestion structurée des exceptions (SEH). Ne créez jamais d'instances de cette classe manuellement. Utilisez la classe ExternalException à la place. Ne jamais encapsuler les instances de la classe ExternalException dans [System::SmartPtr](../system/smartptr/). |
| [Marshal](./marshal/) | Fournit une implémentation de marshaling. uniquement pour la compatibilité avec le code traduit, car aucun code géré n’est pris en charge du côté C++. Il s’agit d’un type statique sans services d’instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit. |
| [MemoryMarshal](./memorymarshal/) | Fournit une implémentation de marshaling mémoire. uniquement pour la compatibilité avec le code traduit, car aucun code géré n’est pris en charge du côté C++. Il s’agit d’un type statique sans services d’instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit. |
| [NativeLibrary](./nativelibrary/) |  |
| [OSPlatform](./osplatform/) |  |

## Structures

| Struct | Description |
| --- | --- |
| [FILETIME](./filetime/) | Contient les composants de temps de fichier. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N’utilisez jamais la classe [System::SmartPtr](../system/smartptr/) pour gérer les objets de ce type. |
| [RuntimeInformation](./runtimeinformation/) |  |

## Énumérations

| Enum | Description |
| --- | --- |
| [GCHandleType](./gchandletype/) | Définit comment le handle est traité par le ramasse-miettes. |
| [VarEnum](./varenum/) | Définit comment les éléments du tableau doivent être marshaled. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [ExternalException](./externalexception/) |  |