---
title: Environment
second_title: Aspose.Slides for C++ API 参考
description: 环境服务。此类型为静态类型，没有实例服务。绝不应通过任何方式创建其实例。
type: docs
weight: 1600
url: /zh/system/environment/
---
## Environment 结构体

[Environment](./) 服务。此类型为静态类型，没有实例服务。绝不应通过任何方式创建其实例。

```cpp
class Environment
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static void [Exit](./exit/)(int) | 终止当前进程并将指定的退出代码返回给操作系统。 |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | 将指定字符串中找到的环境变量名称替换为相应变量的值，并返回生成的字符串。 |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | 中止当前进程。 |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | 返回用于启动当前进程的命令行。 |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | 返回当前工作目录的路径。 |
| static int [get_ExitCode](./get_exitcode/)() | 返回当前进程的退出代码。 |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | 检查是否正在进行关机。未实现。 |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | 对于 64 位平台的可执行文件/库返回 true。 |
| static [String](../string/) [get_MachineName](./get_machinename/)() | 返回此计算机的 NetBIOS 名称。 |
| static [String](../string/) [get_NewLine](./get_newline/)() | 返回当前环境设置的换行符字符串。 |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | 返回 [OperatingSystem](../operatingsystem/) 对象，该对象包含关于当前操作系统的信息。 |
| static int [get_ProcessorCount](./get_processorcount/)() | 返回当前机器的处理器数量。 |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | 返回包含当前堆栈跟踪信息的字符串。 |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | 返回系统目录的路径。 |
| static int [get_TickCount](./get_tickcount/)() | 返回系统启动以来经过的毫秒数。 |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | 返回当前用户的网络域名。 |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | 确定当前进程是否在用户交互模式下运行。 |
| static [String](../string/) [get_UserName](./get_username/)() | 返回当前登录到 [Windows](../../system.windows/) 操作系统的用户名称。 |
| static [Version](../version/) [get_Version](./get_version/)() | 返回 [Version](../version/) 对象，该对象表示公共语言运行时版本信息。该方法返回的版本号仅为示例，并不意味着所有库类都遵循该返回的版本行为。 |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | 返回映射到进程上下文的物理内存量。 |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | 返回包含用于启动当前进程的命令行参数的数组。 |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | 返回与当前进程关联的指定环境变量的值。 |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | 返回来自指定位置的指定环境变量的值。 |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | 返回与当前进程关联的指定环境变量的值。 |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | 返回一个字典，包含与当前进程关联的所有环境变量名称及其值。 |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | 返回一个字典，包含来自指定位置的所有环境变量名称及其值。 |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | 返回与当前进程关联的指定环境变量的值。 |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | 返回指定系统文件夹的完全限定路径。 |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | 返回当前计算机上所有逻辑驱动器名称的数组。 |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | 仅在 WSL 环境下返回 true。 |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | 将指定目录设置为当前工作目录。 |
| static void [set_ExitCode](./set_exitcode/)(int) | 将指定值设为当前进程的退出代码。 |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | 未实现。 |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | 未实现。 |

## 枚举

| 枚举 | 描述 |
| --- | --- |
| [SpecialFolder](./specialfolder/) | 表示系统特殊文件夹。 |

## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)