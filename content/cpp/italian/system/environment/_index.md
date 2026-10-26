---
title: Environment
second_title: Riferimento API di Aspose.Slides per C++
description: Servizi di Environment. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso con alcun mezzo.
type: docs
weight: 1626
url: /it/system/environment/
---
## Struttura Environment

[Environment](./) services. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso con alcun mezzo.

```cpp
class Environment
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static void [Exit](./exit/)(int) | Termina il processo corrente e restituisce il codice di uscita specificato al sistema operativo. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | Sostituisce i nomi delle variabili d'ambiente trovati nella stringa specificata con i valori di tali variabili e restituisce la stringa risultante. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | Interrompe il processo corrente. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | Restituisce la riga di comando utilizzata per avviare il processo corrente. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | Restituisce il percorso della directory di lavoro corrente. |
| static int [get_ExitCode](./get_exitcode/)() | Restituisce il codice di uscita per il processo corrente. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | Verifica se lo spegnimento è in corso. Non implementato. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | Restituisce true per eseguibili/librerie su piattaforma a 64 bit. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | Restituisce il nome NetBIOS di questo computer. |
| static [String](../string/) [get_NewLine](./get_newline/)() | Restituisce la stringa di newline impostata per l'ambiente corrente. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | Restituisce l'oggetto [OperatingSystem](../operatingsystem/) che contiene informazioni sul sistema operativo corrente. |
| static int [get_ProcessorCount](./get_processorcount/)() | Restituisce il numero di processori della macchina corrente. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | Restituisce la stringa che contiene le informazioni della traccia di stack corrente. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | Restituisce il percorso della directory di sistema. |
| static int [get_TickCount](./get_tickcount/)() | Restituisce il numero di millisecondi trascorsi dall'avvio del sistema. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | Restituisce il nome del dominio di rete dell'utente corrente. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | Determina se il processo corrente è in esecuzione in modalità interattiva dell'utente. |
| static [String](../string/) [get_UserName](./get_username/)() | Restituisce il nome dell'utente attualmente connesso al sistema operativo [Windows](../../system.windows/). |
| static [Version](../version/) [get_Version](./get_version/)() | Restituisce l'oggetto [Version](../version/) che rappresenta le informazioni sulla versione del runtime del linguaggio comune. Il numero di versione restituito da questo metodo è piuttosto fittizio e non indica che tutte le classi della libreria si comportino secondo la versione restituita. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | Restituisce la quantità di memoria fisica mappata al contesto del processo. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | Restituisce un array contenente gli argomenti della riga di comando utilizzati per avviare il processo corrente. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | Restituisce il valore della variabile d'ambiente specificata associata al processo corrente. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | Restituisce il valore della variabile d'ambiente specificata dalla posizione indicata. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | Restituisce il valore della variabile d'ambiente specificata associata al processo corrente. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | Restituisce un dizionario contenente tutti i nomi delle variabili d'ambiente e i loro valori associati al processo corrente. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | Restituisce un dizionario contenente tutti i nomi delle variabili d'ambiente e i loro valori dalla posizione specificata. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | Restituisce il valore della variabile d'ambiente specificata associata al processo corrente. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | Restituisce il percorso completamente qualificato della cartella di sistema specificata. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | Restituisce un array contenente i nomi di tutte le unità logiche del computer corrente. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | Restituisce true solo per WSL. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | Imposta la directory specificata come directory di lavoro corrente. |
| static void [set_ExitCode](./set_exitcode/)(int) | Imposta il valore specificato come codice di uscita per il processo corrente. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | NON IMPLEMENTATO. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | NON IMPLEMENTATO. |

## Enum

| Enum | Descrizione |
| --- | --- |
| [SpecialFolder](./specialfolder/) | Rappresenta le cartelle speciali del sistema. |

## Vedi anche

* Namespace [System](../)
* Libreria [Aspose.Slides](../../)