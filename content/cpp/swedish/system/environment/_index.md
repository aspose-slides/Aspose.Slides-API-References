---
title: Environment
second_title: Aspose.Slides för C++ API-referens
description: Miljötjänster. Detta är en statisk typ utan instanstjänster. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 1626
url: /sv/system/environment/
---
## Environment struktur


[Environment](./) tjänster. Detta är en statisk typ utan instans-tjänster. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class Environment
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static void [Exit](./exit/)(int) | Avslutar den aktuella processen och returnerar den angivna avslutningskoden till operativsystemet. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | Ersätter namn på miljövariabler som finns i den angivna strängen med värdena för dessa variabler och returnerar den resulterande strängen. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | Avbryter den aktuella processen. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | Returnerar kommandoraden som användes för att starta den aktuella processen. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | Returnerar sökvägen till den aktuella arbetskatalogen. |
| static int [get_ExitCode](./get_exitcode/)() | Returnerar avslutningskoden för den aktuella processen. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | Kontrollerar om en avstängning pågår. Inte implementerad. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | Returnerar true för 64-bitars plattformsprogram/-bibliotek. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | Returnerar NetBIOS-namnet för den här datorn. |
| static [String](../string/) [get_NewLine](./get_newline/)() | Returnerar radbrytningens sträng som är inställd för den aktuella miljön. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | Returnerar [OperatingSystem](../operatingsystem/)-objektet som innehåller information om det aktuella operativsystemet. |
| static int [get_ProcessorCount](./get_processorcount/)() | Returnerar antalet processorer på den aktuella maskinen. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | Returnerar strängen som innehåller den aktuella stackspårningsinformationen. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | Returnerar sökvägen till systemkatalogen. |
| static int [get_TickCount](./get_tickcount/)() | Returnerar antalet millisekunder som har gått sedan systemet startade. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | Returnerar nätverksdomännamnet för den aktuella användaren. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | Bestämmer om den aktuella processen körs i användarinteraktivt läge. |
| static [String](../string/) [get_UserName](./get_username/)() | Returnerar namnet på den användare som för närvarande är inloggad på [Windows](../../system.windows/)-OS. |
| static [Version](../version/) [get_Version](./get_version/)() | Returnerar [Version](../version/)-objektet som representerar informationen om versionen av den gemensamma språk-körningsmiljön. Versionsnumret som returneras av denna metod är snarare dummy och betyder inte att alla biblioteks-klasser beter sig i enlighet med den returnerade versionen. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | Returnerar mängden fysiskt minne som är mappat till processens kontext. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | Returnerar en array som innehåller kommandoradsargumenten som användes för att starta den aktuella processen. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | Returnerar värdet på den angivna miljövariabeln som är associerad med den aktuella processen. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | Returnerar värdet på den angivna miljövariabeln från den angivna platsen. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | Returnerar värdet på den angivna miljövariabeln som är associerad med den aktuella processen. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | Returnerar en ordbok som innehåller alla miljövariabelnamn och deras värden som är associerade med den aktuella processen. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | Returnerar en ordbok som innehåller alla miljövariabelnamn och deras värden från den angivna platsen. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | Returnerar värdet på den angivna miljövariabeln som är associerad med den aktuella processen. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | Returnerar den fullständigt kvalificerade sökvägen till den angivna systemmappen. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | Returnerar en array som innehåller namnen på alla logiska enheter på den aktuella datorn. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | Returnerar true endast för WSL. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | Ställer in den angivna katalogen som den aktuella arbetskatalogen. |
| static void [set_ExitCode](./set_exitcode/)(int) | Ställer in det angivna värdet som avslutningskod för den aktuella processen. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | INTE IMPLEMENTERAD. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | INTE IMPLEMENTERAD. |

## Enums

| Enum | Beskrivning |
| --- | --- |
| [SpecialFolder](./specialfolder/) | Representerar systemets särskilda mappar. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)