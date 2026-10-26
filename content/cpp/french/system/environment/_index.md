---
title: Environment
second_title: Référence de l'API Aspose.Slides pour C++
description: Services d'environnement. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci, de quelque manière que ce soit.
type: docs
weight: 1600
url: /fr/system/environment/
---
## Structure Environment


[Environment](./) services. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci, de quelque manière que ce soit.

```cpp
class Environment
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static void [Exit](./exit/)(int) | Met fin au processus en cours et renvoie le code de sortie spécifié au système d'exploitation. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | Remplace les noms des variables d'environnement trouvés dans la chaîne spécifiée par les valeurs de ces variables et renvoie la chaîne résultante. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | Interrompt le processus en cours. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | Renvoie la ligne de commande utilisée pour lancer le processus en cours. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | Renvoie le chemin du répertoire de travail actuel. |
| static int [get_ExitCode](./get_exitcode/)() | Renvoie le code de sortie du processus en cours. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | Vérifie si l'arrêt est en cours. Non implémenté. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | Renvoie true pour les exécutables/bibliothèques de plateforme 64 bits. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | Renvoie le nom NetBIOS de cet ordinateur. |
| static [String](../string/) [get_NewLine](./get_newline/)() | Renvoie la chaîne de saut de ligne définie pour l'environnement actuel. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | Renvoie l'objet [OperatingSystem](../operatingsystem/) qui contient des informations sur le système d'exploitation actuel. |
| static int [get_ProcessorCount](./get_processorcount/)() | Renvoie le nombre de processeurs de la machine actuelle. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | Renvoie la chaîne contenant les informations de trace de la pile actuelle. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | Renvoie le chemin du répertoire système. |
| static int [get_TickCount](./get_tickcount/)() | Renvoie le nombre de millisecondes écoulées depuis le démarrage du système. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | Renvoie le nom de domaine réseau de l'utilisateur actuel. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | Détermine si le processus en cours s'exécute en mode interactif utilisateur. |
| static [String](../string/) [get_UserName](./get_username/)() | Renvoie le nom de l'utilisateur actuellement connecté au système d'exploitation [Windows](../../system.windows/). |
| static [Version](../version/) [get_Version](./get_version/)() | Renvoie l'objet [Version](../version/) qui représente les informations sur la version du runtime du langage commun. Le numéro de version renvoyé par cette méthode est plutôt factice et ne signifie pas que toutes les classes de la bibliothèque se comportent conformément à la version renvoyée. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | Renvoie la quantité de mémoire physique mappée au contexte du processus. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | Renvoie un tableau contenant les arguments de ligne de commande utilisés pour lancer le processus en cours. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | Renvoie la valeur de la variable d'environnement spécifiée associée au processus en cours. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | Renvoie la valeur de la variable d'environnement spécifiée depuis l'emplacement indiqué. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | Renvoie la valeur de la variable d'environnement spécifiée associée au processus en cours. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | Renvoie un dictionnaire contenant tous les noms de variables d'environnement et leurs valeurs associés au processus en cours. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | Renvoie un dictionnaire contenant tous les noms de variables d'environnement et leurs valeurs depuis l'emplacement spécifié. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | Renvoie la valeur de la variable d'environnement spécifiée associée au processus en cours. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | Renvoie le chemin complet vers le dossier système spécifié. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | Renvoie un tableau contenant les noms de tous les lecteurs logiques de l'ordinateur actuel. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | Renvoie true uniquement pour WSL. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | Définit le répertoire spécifié comme répertoire de travail actuel. |
| static void [set_ExitCode](./set_exitcode/)(int) | Définit la valeur spécifiée comme code de sortie pour le processus en cours. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | NON IMPLEMENTÉ. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | NON IMPLEMENTÉ. |

## Énumérations

| Énum | Description |
| --- | --- |
| [SpecialFolder](./specialfolder/) | Représente les dossiers spéciaux du système. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)