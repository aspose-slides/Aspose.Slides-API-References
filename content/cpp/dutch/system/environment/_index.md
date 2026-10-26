---
title: Environment
second_title: Aspose.Slides voor C++ API-referentie
description: Omgevingsservices. Dit is een statisch type zonder instantie services. Je mag onder geen enkele omstandigheid instanties ervan maken.
type: docs
weight: 1626
url: /nl/system/environment/
---
## Environment-struct


[Environment](./) services. Dit is een statisch type zonder instantie services. Je mag onder geen enkele omstandigheid instanties ervan maken.

```cpp
class Environment
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static void [Exit](./exit/)(int) | Beëindigt het huidige proces en geeft de opgegeven exitcode terug aan het besturingssysteem. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | Vervangt de namen van omgevingsvariabelen die in de opgegeven string worden gevonden door de waarden van die variabelen en retourneert de resulterende string. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | Breekt het huidige proces af. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | Retourneert de opdrachtregel die is gebruikt om het huidige proces te starten. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | Retourneert het pad naar de huidige werkmap. |
| static int [get_ExitCode](./get_exitcode/)() | Retourneert de exitcode voor het huidige proces. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | Controleert of een afsluiting bezig is. Niet geïmplementeerd. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | Retourneert true voor 64-bit platform uitvoerbare bestanden/bibliotheken. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | Retourneert de NetBIOS-naam van deze computer. |
| static [String](../string/) [get_NewLine](./get_newline/)() | Retourneert de newline-string die is ingesteld voor de huidige omgeving. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | Retourneert het [OperatingSystem](../operatingsystem/)-object dat informatie over het huidige besturingssysteem bevat. |
| static int [get_ProcessorCount](./get_processorcount/)() | Retourneert het aantal processors van de huidige machine. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | Retourneert de string die de huidige stack-trace-informatie bevat. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | Retourneert het pad naar de systeemmap. |
| static int [get_TickCount](./get_tickcount/)() | Retourneert het aantal milliseconden dat is verstreken sinds het systeem is gestart. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | Retourneert de netwerkdomeinnaam van de huidige gebruiker. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | Bepaalt of het huidige proces wordt uitgevoerd in gebruikers-interactieve modus. |
| static [String](../string/) [get_UserName](./get_username/)() | Retourneert de naam van de gebruiker die momenteel is aangemeld bij het [Windows](../../system.windows/)-besturingssysteem. |
| static [Version](../version/) [get_Version](./get_version/)() | Retourneert het [Version](../version/)-object dat de informatie over de versie van de Common Language Runtime weergeeft. Het door deze methode geretourneerde versienummer is eerder een dummy en betekent niet dat alle bibliotheekklassen zich gedragen overeenkomstig met de geretourneerde versie. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | Retourneert de hoeveelheid fysiek geheugen die is toegewezen aan de procescontext. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | Retourneert een array met de commandoregel-argumenten die zijn gebruikt om het huidige proces te starten. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | Retourneert de waarde van de opgegeven omgevingsvariabele die bij het huidige proces hoort. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | Retourneert de waarde van de opgegeven omgevingsvariabele van de opgegeven locatie. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | Retourneert de waarde van de opgegeven omgevingsvariabele die bij het huidige proces hoort. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | Retourneert een woordenboek met alle namen van omgevingsvariabelen en hun waarden die bij het huidige proces horen. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | Retourneert een woordenboek met alle namen van omgevingsvariabelen en hun waarden van de opgegeven locatie. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | Retourneert de waarde van de opgegeven omgevingsvariabele die bij het huidige proces hoort. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | Retourneert het volledig gekwalificeerde pad naar de opgegeven systeemmap. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | Retourneert een array met de namen van alle logische stations op de huidige computer. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | Retourneert alleen true voor WSL. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | Stelt de opgegeven map in als de huidige werkmap. |
| static void [set_ExitCode](./set_exitcode/)(int) | Stelt de opgegeven waarde in als exitcode voor het huidige proces. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | NIET GEAIMPLEMENTEERD. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | NIET GEAIMPLEMENTEERD. |

## Enumeraties

| Enumeratie | Beschrijving |
| --- | --- |
| [SpecialFolder](./specialfolder/) | Vertegenwoordigt systeemspeciale mappen. |

## Zie ook

* Namespace [System](../)
* Library [Aspose.Slides](../../)