---
title: Environment
second_title: Aspose.Slides C++ API hivatkozás
description: Környezet szolgáltatások. Ez egy statikus típus, amelynek nincsenek példányszolgáltatásai. Soha ne hozzon létre példányokat ebből semmilyen módon.
type: docs
weight: 1626
url: /hu/system/environment/
---
## Környezet struktúra


[Environment](./) services. Ez egy statikus típus, amelynek nincsenek példányszolgáltatásai. Soha ne hozzon létre példányokat ebből semmilyen módon.

```cpp
class Environment
```

## Metódusok

| Method | Leírás |
| --- | --- |
| static void [Exit](./exit/)(int) | Leállítja az aktuális folyamatot, és visszaadja a megadott kilépési kódot a operációs rendszernek. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | Lecseréli a megadott karakterláncban található környezeti változók nevét az adott változók értékére, és visszaadja az eredményül kapott karakterláncot. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | Megszakítja az aktuális folyamatot. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | Visszaadja az aktuális folyamat indításához használt parancssort. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | Visszaadja az aktuális munkakönyvtár elérési útját. |
| static int [get_ExitCode](./get_exitcode/)() | Visszaadja az aktuális folyamat kilépési kódját. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | Ellenőrzi, hogy leállítás folyamatban van-e. NINCS MEGVALÓSÍTVA. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | Igaz értéket ad 64-bites platform futtatható fájlokhoz/könyvtárakhoz. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | Visszaadja ennek a számítógépnek a NetBIOS nevét. |
| static [String](../string/) [get_NewLine](./get_newline/)() | Visszaadja az aktuális környezethez beállított új sor karakterláncot. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | Visszaadja a [OperatingSystem](../operatingsystem/) objektumot, amely információkat tartalmaz az aktuális operációs rendszerről. |
| static int [get_ProcessorCount](./get_processorcount/)() | Visszaadja a processzorok számát vagy az aktuális gépét. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | Visszaadja a karakterláncot, amely az aktuális veremnyomkövetési információkat tartalmazza. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | Visszaadja a rendszerkönyvtár elérési útját. |
| static int [get_TickCount](./get_tickcount/)() | Visszaadja a rendszerindítás óta eltelt ezredmásodpercek számát. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | Visszaadja az aktuális felhasználó hálózati tartomány nevét. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | Megállapítja, hogy az aktuális folyamat felhasználói interaktív módban fut-e. |
| static [String](../string/) [get_UserName](./get_username/)() | Visszaadja a jelenleg bejelentkezett felhasználó nevét a [Windows](../../system.windows/) operációs rendszerben. |
| static [Version](../version/) [get_Version](./get_version/)() | Visszaadja a [Version](../version/) objektumot, amely a közös nyelvi futtatókör (CLR) verziójával kapcsolatos információkat képviseli. Ennek a metódusnak a visszatérési verziószáma inkább példaként szolgál, és nem jelenti, hogy minden könyvtári osztály ennek megfelelően viselkedik. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | Visszaadja a folyamatkörnyezethez leképezett fizikai memória mennyiségét. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | Visszaad egy tömböt, amely tartalmazza az aktuális folyamat indításához használt parancssori argumentumokat. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | Visszaadja a megadott környezeti változó értékét, amely az aktuális folyamathoz kapcsolódik. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | Visszaadja a megadott környezeti változó értékét a megadott helyről. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | Visszaadja a megadott környezeti változó értékét, amely az aktuális folyamathoz kapcsolódik. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | Visszaad egy szótárt, amely az aktuális folyamathoz tartozó összes környezeti változó nevét és értékét tartalmazza. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | Visszaad egy szótárt, amely a megadott helyről az összes környezeti változó nevét és értékét tartalmazza. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | Visszaadja a megadott környezeti változó értékét, amely az aktuális folyamathoz kapcsolódik. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | Visszaadja a megadott rendszerkönyvtár teljesen kvalifikált elérési útját. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | Visszaad egy tömböt, amely az aktuális számítógép összes logikai meghajtójának nevét tartalmazza. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | Csak WSL esetén ad igaz értéket. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | Beállítja a megadott könyvtárat az aktuális munkakönyvtárnak. |
| static void [set_ExitCode](./set_exitcode/)(int) | Beállítja a megadott értéket az aktuális folyamat kilépési kódjaként. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | NINCS MEGVALÓSÍTVA. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | NINCS MEGVALÓSÍTVA. |

## Enums

| Enum | Leírás |
| --- | --- |
| [SpecialFolder](./specialfolder/) | A rendszer speciális mappáit képviseli. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)