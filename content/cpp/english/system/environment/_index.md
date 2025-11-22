---
title: Environment
second_title: Aspose.Slides for C++ API Reference
description: Environment services. This is a static type with no instance services. You should never create instances of it by any means.
type: docs
weight: 1574
url: /system/environment/
---
## Environment struct


[Environment](./) services. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Environment
```

## Methods

| Method | Description |
| --- | --- |
| static void [Exit](./exit/)(int) | Terminates the current process and returns the specified exit code to the operating system. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | Replaces the names of environment variables found in the specified string with the values of those variables and returns the resulting string. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | Aborts the current process. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | Returns the command line used to start the current process. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | Returns the path to the current working directory. |
| static int [get_ExitCode](./get_exitcode/)() | Returns the exit code for the current process. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | Checks if shutdown is in progress. Not implemented. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | Returns true for 64-bit platform executables/libs. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | Returns the NetBIOS name of this computer. |
| static [String](../string/) [get_NewLine](./get_newline/)() | Returns the newline string set for the current environment. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | Returns the [OperatingSystem](../operatingsystem/) object that contains information about the current operating system. |
| static int [get_ProcessorCount](./get_processorcount/)() | Returns the number of processors or the current machine. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | Returns the string that contains the current stack trace inofrmation. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | Returns the path to the system directory. |
| static int [get_TickCount](./get_tickcount/)() | Returns the number of milliseconds passed since the system started. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | Returns the network domain name of the current user. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | Determines whether the current process is running in user interactive mode. |
| static [String](../string/) [get_UserName](./get_username/)() | Returns the name of the user currently logged on to the [Windows](../../system.windows/) OS. |
| static [Version](../version/) [get_Version](./get_version/)() | Returns the [Version](../version/) object that represents the information about the version of the common language runtime. The version number returned by this method is rather dummy and does not mean that all library classes behave in accordance with the returned version. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | Returns the amount of physical memory mapped to the process context. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | Returns an array containing the command-line arguments used to start the current process. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | Returns the value of the specified environment varibale associated with the current process. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | Returns the value of the specified environment varibale from the specified location. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | Returns the value of the specified environment varibale associated with the current process. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | Returns a dictionary containing all environment variables names and their values associated with the current process. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | Returns a dictionary containing all environment variables' names and their values from the specified location. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | Returns the value of the specified environment varibale associated with the current process. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | Returns fully qualified path to the specified system folder. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | Returns an array containing the names of all logical drives on the current computer. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | Returns true only for WSL. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | Sets the specified directory as the current working directory. |
| static void [set_ExitCode](./set_exitcode/)(int) | Sets the specified value as exit code for the current process. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | NOT IMPLEMENTED. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | NOT IMPLEMENTED. |
## Enums

| Enum | Description |
| --- | --- |
| [SpecialFolder](./specialfolder/) | Represents system special folders. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)