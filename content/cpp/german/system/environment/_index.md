---
title: Environment
second_title: Aspose.Slides für C++ API-Referenz
description: Umgebungsdienste. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten unter keinen Umständen Instanzen davon erstellen.
type: docs
weight: 1626
url: /de/system/environment/
---
## Umgebungsstruktur

[Environment](./) Dienste. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten unter keinen Umständen Instanzen davon erstellen.

```cpp
class Environment
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static void [Exit](./exit/)(int) | Beendet den aktuellen Prozess und gibt den angegebenen Rückgabecode an das Betriebssystem zurück. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | Ersetzt die Namen von Umgebungsvariablen, die im angegebenen String gefunden wurden, durch die Werte dieser Variablen und gibt den resultierenden String zurück. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | Bricht den aktuellen Prozess ab. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | Gibt die Befehlszeile zurück, die zum Starten des aktuellen Prozesses verwendet wurde. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | Gibt den Pfad zum aktuellen Arbeitsverzeichnis zurück. |
| static int [get_ExitCode](./get_exitcode/)() | Gibt den Rückgabecode des aktuellen Prozesses zurück. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | Überprüft, ob ein Herunterfahren im Gange ist. Nicht implementiert. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | Gibt true für 64-Bit-Plattform-Executable-/-Bibliotheken zurück. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | Gibt den NetBIOS-Namen dieses Computers zurück. |
| static [String](../string/) [get_NewLine](./get_newline/)() | Gibt die für die aktuelle Umgebung festgelegte Newline-Zeichenkette zurück. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | Gibt das [OperatingSystem](../operatingsystem/)-Objekt zurück, das Informationen über das aktuelle Betriebssystem enthält. |
| static int [get_ProcessorCount](./get_processorcount/)() | Gibt die Anzahl der Prozessoren der aktuellen Maschine zurück. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | Gibt die Zeichenkette zurück, die die aktuelle Stack-Trace-Information enthält. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | Gibt den Pfad zum Systemverzeichnis zurück. |
| static int [get_TickCount](./get_tickcount/)() | Gibt die seit Systemstart verstrichenen Millisekunden zurück. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | Gibt den Netzwerkdomänennamen des aktuellen Benutzers zurück. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | Ermittelt, ob der aktuelle Prozess im interaktiven Benutzermodus läuft. |
| static [String](../string/) [get_UserName](./get_username/)() | Gibt den Namen des aktuell bei dem [Windows](../../system.windows/)-OS angemeldeten Benutzers zurück. |
| static [Version](../version/) [get_Version](./get_version/)() | Gibt das [Version](../version/)-Objekt zurück, das die Informationen zur Version der Common-Language-Runtime darstellt. Die von dieser Methode zurückgegebene Versionsnummer ist eher eine Platzhalternummer und bedeutet nicht, dass alle Bibliotheksklassen sich gemäß der zurückgegebenen Version verhalten. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | Gibt die Menge des physischen Speichers zurück, die dem Prozesskontext zugeordnet ist. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | Gibt ein Array zurück, das die zum Starten des aktuellen Prozesses verwendeten Befehlszeilenargumente enthält. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | Gibt den Wert der angegebenen Umgebungsvariable zurück, die dem aktuellen Prozess zugeordnet ist. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | Gibt den Wert der angegebenen Umgebungsvariable aus dem angegebenen Speicherort zurück. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | Gibt den Wert der angegebenen Umgebungsvariable zurück, die dem aktuellen Prozess zugeordnet ist. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | Gibt ein Wörterbuch zurück, das alle Namen von Umgebungsvariablen und ihre Werte enthält, die dem aktuellen Prozess zugeordnet sind. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | Gibt ein Wörterbuch zurück, das alle Namen von Umgebungsvariablen und ihre Werte aus dem angegebenen Speicherort enthält. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | Gibt den Wert der angegebenen Umgebungsvariable zurück, die dem aktuellen Prozess zugeordnet ist. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | Gibt den vollqualifizierten Pfad zu dem angegebenen Systemordner zurück. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | Gibt ein Array zurück, das die Namen aller logischen Laufwerke des aktuellen Computers enthält. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | Gibt nur für WSL true zurück. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | Setzt das angegebene Verzeichnis als aktuelles Arbeitsverzeichnis. |
| static void [set_ExitCode](./set_exitcode/)(int) | Setzt den angegebenen Wert als Rückgabecode für den aktuellen Prozess. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | NICHT IMPLEMENTIERT. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | NICHT IMPLEMENTIERT. |
## Aufzählungen

| Enum | Beschreibung |
| --- | --- |
| [SpecialFolder](./specialfolder/) | Stellt System-Spezialordner dar. |
## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)