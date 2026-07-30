---
title: Environment
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Služby prostředí. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet instance tohoto typu žádným způsobem.
type: docs
weight: 1626
url: /cs/system/environment/
---
## Struktura Environment

[Environment](./) služby. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet instance tohoto typu žádným způsobem.

```cpp
class Environment
```

## Metody

| Metoda | Popis |
| --- | --- |
| static void [Exit](./exit/)(int) | Ukončí aktuální proces a vrátí zadaný návratový kód operačnímu systému. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | Nahradí názvy proměnných prostředí nalezených ve zadaném řetězci hodnotami těchto proměnných a vrátí vzniklý řetězec. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | Zruší aktuální proces. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | Vrací příkazový řádek použitý k spuštění aktuálního procesu. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | Vrací cestu k aktuálnímu pracovnímu adresáři. |
| static int [get_ExitCode](./get_exitcode/)() | Vrací návratový kód aktuálního procesu. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | Kontroluje, zda probíhá vypnutí systému. Není implementováno. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | Vrací true pro spustitelné soubory/knihovny na 64bitové platformě. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | Vrací NetBIOS název tohoto počítače. |
| static [String](../string/) [get_NewLine](./get_newline/)() | Vrací řetězec nového řádku nastavený pro aktuální prostředí. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | Vrací objekt [OperatingSystem](../operatingsystem/), který obsahuje informace o aktuálním operačním systému. |
| static int [get_ProcessorCount](./get_processorcount/)() | Vrací počet procesorů aktuálního stroje. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | Vrací řetězec, který obsahuje aktuální informace o zásobníku. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | Vrací cestu do systémového adresáře. |
| static int [get_TickCount](./get_tickcount/)() | Vrací počet milisekund uplynulých od startu systému. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | Vrací název síťové domény aktuálního uživatele. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | Určuje, zda aktuální proces běží v interaktivním uživatelském režimu. |
| static [String](../string/) [get_UserName](./get_username/)() | Vrací jméno uživatele aktuálně přihlášeného k operačnímu systému [Windows](../../system.windows/). |
| static [Version](../version/) [get_Version](./get_version/)() | Vrací objekt [Version](../version/), který představuje informace o verzi společného runtime jazyka. Číslo verze vrácené touto metodou je spíše fiktivní a neznamená, že všechny třídy knihovny se chovají v souladu s touto verzí. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | Vrací množství fyzické paměti mapované do kontextu procesu. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | Vrací pole obsahující argumenty příkazového řádku použité ke spuštění aktuálního procesu. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | Vrací hodnotu zadané proměnné prostředí spojené s aktuálním procesem. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | Vrací hodnotu zadané proměnné prostředí z určeného umístění. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | Vrací hodnotu zadané proměnné prostředí spojené s aktuálním procesem. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | Vrací slovník obsahující názvy všech proměnných prostředí a jejich hodnoty spojené s aktuálním procesem. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | Vrací slovník obsahující názvy všech proměnných prostředí a jejich hodnoty z určeného umístění. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | Vrací hodnotu zadané proměnné prostředí spojené s aktuálním procesem. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | Vrací plně kvalifikovanou cestu k určenému systémovému adresáři. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | Vrací pole obsahující názvy všech logických jednotek na aktuálním počítači. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | Vrací true pouze pro WSL. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | Nastaví zadaný adresář jako aktuální pracovní adresář. |
| static void [set_ExitCode](./set_exitcode/)(int) | Nastaví zadanou hodnotu jako návratový kód pro aktuální proces. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | NENÍ IMPLEMENTOVÁNO. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | NENÍ IMPLEMENTOVÁNO. |

## Výčty

| Výčet | Popis |
| --- | --- |
| [SpecialFolder](./specialfolder/) | Reprezentuje speciální systémové složky. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)