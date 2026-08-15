---
title: Environment
second_title: Aspose.Slides for C++ API 參考
description: 環境服務。這是一個靜態型別，沒有實例服務。絕不應以任何方式建立其實例。
type: docs
weight: 1626
url: /zh-hant/system/environment/
---
## Environment struct

[Environment](./) services. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Environment
```

## 方法

| Method | Description |
| --- | --- |
| static void [Exit](./exit/)(int) | 終止目前的程序，並將指定的退出代碼返回給作業系統。 |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | 將指定字串中找到的環境變數名稱取代為相對應的變數值，並返回產生的字串。 |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | 中止目前的程序。 |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | 返回用於啟動目前程序的命令列。 |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | 返回目前工作目錄的路徑。 |
| static int [get_ExitCode](./get_exitcode/)() | 返回目前程序的退出代碼。 |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | 檢查是否正在關機。未實作。 |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | 在 64 位元平台的可執行檔/庫上返回 true。 |
| static [String](../string/) [get_MachineName](./get_machinename/)() | 返回此電腦的 NetBIOS 名稱。 |
| static [String](../string/) [get_NewLine](./get_newline/)() | 返回目前環境設定的換行字串。 |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | 返回包含目前作業系統資訊的 [OperatingSystem](../operatingsystem/) 物件。 |
| static int [get_ProcessorCount](./get_processorcount/)() | 返回目前機器的處理器數量。 |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | 返回包含目前堆疊追蹤資訊的字串。 |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | 返回系統目錄的路徑。 |
| static int [get_TickCount](./get_tickcount/)() | 返回系統啟動以來經過的毫秒數。 |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | 返回目前使用者的網路域名。 |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | 判斷目前程序是否在使用者交互模式下執行。 |
| static [String](../string/) [get_UserName](./get_username/)() | 返回目前登入 [Windows](../../system.windows/) 作業系統的使用者名稱。 |
| static [Version](../version/) [get_Version](./get_version/)() | 返回表示共通語言執行階段版本資訊的 [Version](../version/) 物件。此方法返回的版本號僅供參考，並不表示所有函式庫類別皆依該版本運作。 |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | 返回映射到程序上下文的實體記憶體量。 |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | 返回包含用於啟動目前程序的命令列參數的陣列。 |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | 返回與目前程序相關聯的指定環境變數的值。 |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | 返回來自指定位置的指定環境變數的值。 |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | 返回與目前程序相關聯的指定環境變數的值。 |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | 返回包含與目前程序相關聯的所有環境變數名稱及其值的字典。 |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | 返回包含指定位置所有環境變數名稱及其值的字典。 |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | 返回與目前程序相關聯的指定環境變數的值。 |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | 返回指定系統資料夾的完整路徑。 |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | 返回目前電腦上所有邏輯磁碟名稱的陣列。 |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | 僅在 WSL 上返回 true。 |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | 將指定目錄設定為目前工作目錄。 |
| static void [set_ExitCode](./set_exitcode/)(int) | 將指定值設定為目前程序的退出代碼。 |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | 未實作。 |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | 未實作。 |

## 列舉

| Enum | Description |
| --- | --- |
| [SpecialFolder](./specialfolder/) | 代表系統特殊資料夾。 |

## 另請參閱

* Namespace [System](../)
* Library [Aspose.Slides](../../)