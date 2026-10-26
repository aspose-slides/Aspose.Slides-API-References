---
title: Environment
second_title: Справочник API Aspose.Slides для C++
description: Службы окружения. Это статический тип без экземплярных служб. Вы никогда не должны создавать его экземпляры каким-либо способом.
type: docs
weight: 1600
url: /ru/system/environment/
---
## Environment struct

[Environment](./) службы. Это статический тип без экземплярных служб. Вы никогда не должны создавать его экземпляры каким-либо способом.

```cpp
class Environment
```

## Methods

| Method | Description |
| --- | --- |
| static void [Exit](./exit/)(int) | Прерывает текущий процесс и возвращает указанный код завершения операционной системе. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | Заменяет имена переменных окружения, найденные в указанной строке, их значениями и возвращает полученную строку. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | Прерывает текущий процесс. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | Возвращает командную строку, использованную для запуска текущего процесса. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | Возвращает путь к текущему рабочему каталогу. |
| static int [get_ExitCode](./get_exitcode/)() | Возвращает код завершения текущего процесса. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | Проверяет, выполняется ли завершение работы. Не реализовано. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | Возвращает true для 64-битных исполняемых файлов/библиотек. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | Возвращает NetBIOS-имя этого компьютера. |
| static [String](../string/) [get_NewLine](./get_newline/)() | Возвращает строку перевода строки, установленную в текущем окружении. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | Возвращает объект [OperatingSystem](../operatingsystem/), содержащий информацию о текущей операционной системе. |
| static int [get_ProcessorCount](./get_processorcount/)() | Возвращает количество процессоров текущей машины. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | Возвращает строку, содержащую информацию о текущем стеке вызовов. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | Возвращает путь к системному каталогу. |
| static int [get_TickCount](./get_tickcount/)() | Возвращает количество миллисекунд, прошедших с момента запуска системы. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | Возвращает имя сетевого домена текущего пользователя. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | Определяет, запущен ли текущий процесс в интерактивном пользовательском режиме. |
| static [String](../string/) [get_UserName](./get_username/)() | Возвращает имя пользователя, в данный момент вошедшего в ОС [Windows](../../system.windows/). |
| static [Version](../version/) [get_Version](./get_version/)() | Возвращает объект [Version](../version/), представляющий информацию о версии общей среды выполнения (CLR). Номер версии, возвращаемый этим методом, является условным и не означает, что все классы библиотеки работают в соответствии с возвращённой версией. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | Возвращает объём физической памяти, отображённой в контекст процесса. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | Возвращает массив, содержащий аргументы командной строки, использованные для запуска текущего процесса. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | Возвращает значение указанной переменной окружения, связанной с текущим процессом. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | Возвращает значение указанной переменной окружения из указанного местоположения. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | Возвращает значение указанной переменной окружения, связанной с текущим процессом. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | Возвращает словарь, содержащий имена всех переменных окружения и их значения, связанные с текущим процессом. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | Возвращает словарь, содержащий имена всех переменных окружения и их значения из указанного местоположения. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | Возвращает значение указанной переменной окружения, связанной с текущим процессом. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | Возвращает полностью квалифицированный путь к указанному системному каталогу. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | Возвращает массив, содержащий имена всех логических дисков текущего компьютера. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | Возвращает true только для WSL. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | Устанавливает указанный каталог как текущий рабочий каталог. |
| static void [set_ExitCode](./set_exitcode/)(int) | Устанавливает указанное значение в качестве кода завершения текущего процесса. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | НЕ РЕАЛИЗОВАНО. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | НЕ РЕАЛИЗОВАНО. |

## Enums

| Enum | Description |
| --- | --- |
| [SpecialFolder](./specialfolder/) | Представляет системные специальные папки. |

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)