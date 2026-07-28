---
title: Environment
second_title: Referencja API Aspose.Slides dla C++
description: Usługi Environment. Jest to typ statyczny bez usług instancji. Nigdy nie należy tworzyć jego instancji w żaden sposób.
type: docs
weight: 1626
url: /pl/system/environment/
---
## Struktura Environment

[Environment](./) usługi. To jest typ statyczny bez usług instancji. Nie powinieneś nigdy tworzyć jego instancji w żaden sposób.

```cpp
class Environment
```

## Metody

| Metoda | Opis |
| --- | --- |
| static void [Exit](./exit/)(int) | Zakończa bieżący proces i zwraca podany kod wyjścia do systemu operacyjnego. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | Zastępuje nazwy zmiennych środowiskowych znalezionych w podanym ciągu ich wartościami i zwraca otrzymany ciąg. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | Przerywa bieżący proces. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | Zwraca wiersz poleceń użyty do uruchomienia bieżącego procesu. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | Zwraca ścieżkę do bieżącego katalogu roboczego. |
| static int [get_ExitCode](./get_exitcode/)() | Zwraca kod wyjścia bieżącego procesu. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | Sprawdza, czy trwa wyłączanie systemu. Niezaimplementowane. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | Zwraca true dla plików wykonywalnych/bibliotek na platformie 64-bitowej. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | Zwraca nazwę NetBIOS tego komputera. |
| static [String](../string/) [get_NewLine](./get_newline/)() | Zwraca ciąg nowej linii ustawiony dla bieżącego środowiska. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | Zwraca obiekt [OperatingSystem](../operatingsystem/) zawierający informacje o bieżącym systemie operacyjnym. |
| static int [get_ProcessorCount](./get_processorcount/)() | Zwraca liczbę procesorów w bieżącej maszynie. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | Zwraca ciąg zawierający informacje o bieżącym śladzie stosu. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | Zwraca ścieżkę do katalogu systemowego. |
| static int [get_TickCount](./get_tickcount/)() | Zwraca liczbę milisekund, które upłynęły od uruchomienia systemu. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | Zwraca nazwę domeny sieciowej bieżącego użytkownika. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | Określa, czy bieżący proces działa w trybie interaktywnym użytkownika. |
| static [String](../string/) [get_UserName](./get_username/)() | Zwraca nazwę użytkownika aktualnie zalogowanego w systemie [Windows](../../system.windows/). |
| static [Version](../version/) [get_Version](./get_version/)() | Zwraca obiekt [Version](../version/) reprezentujący informacje o wersji wspólnego środowiska uruchomieniowego. Numer wersji zwracany przez tę metodę jest jedynie przykładowy i nie oznacza, że wszystkie klasy biblioteki zachowują się zgodnie z tą wersją. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | Zwraca ilość pamięci fizycznej mapowanej do kontekstu procesu. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | Zwraca tablicę zawierającą argumenty wiersza poleceń użyte do uruchomienia bieżącego procesu. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | Zwraca wartość określonej zmiennej środowiskowej powiązanej z bieżącym procesem. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | Zwraca wartość określonej zmiennej środowiskowej z podanej lokalizacji. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | Zwraca wartość określonej zmiennej środowiskowej powiązanej z bieżącym procesem. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | Zwraca słownik zawierający wszystkie nazwy zmiennych środowiskowych i ich wartości powiązane z bieżącym procesem. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | Zwraca słownik zawierający wszystkie nazwy zmiennych środowiskowych i ich wartości z podanej lokalizacji. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | Zwraca wartość określonej zmiennej środowiskowej powiązanej z bieżącym procesem. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | Zwraca w pełni kwalifikowaną ścieżkę do określonego folderu systemowego. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | Zwraca tablicę zawierającą nazwy wszystkich logicznych dysków na bieżącym komputerze. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | Zwraca true tylko dla WSL. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | Ustawia podany katalog jako bieżący katalog roboczy. |
| static void [set_ExitCode](./set_exitcode/)(int) | Ustawia podaną wartość jako kod wyjścia dla bieżącego procesu. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | NIE ZAIMPLEMENTOWANE. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | NIE ZAIMPLEMENTOWANE. |

## Enumy

| Enum | Opis |
| --- | --- |
| [SpecialFolder](./specialfolder/) | Reprezentuje specjalne foldery systemowe. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)