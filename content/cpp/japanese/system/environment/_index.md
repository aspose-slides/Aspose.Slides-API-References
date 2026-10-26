---
title: Environment
second_title: Aspose.Slides for C++ API リファレンス
description: Environment サービスです。この型はインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成してはいけません。
type: docs
weight: 1626
url: /ja/system/environment/
---
## Environment 構造体

[Environment](./) サービス。この型はインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成してはいけません。

```cpp
class Environment
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static void [Exit](./exit/)(int) | 現在のプロセスを終了し、指定された終了コードをオペレーティングシステムに返します。 |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | 指定された文字列内で見つかった環境変数名をその変数の値に置き換え、結果の文字列を返します。 |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | 現在のプロセスを中止します。 |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | 現在のプロセスの起動に使用されたコマンドラインを返します。 |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | 現在の作業ディレクトリへのパスを返します。 |
| static int [get_ExitCode](./get_exitcode/)() | 現在のプロセスの終了コードを返します。 |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | シャットダウンが進行中かどうかを確認します。未実装です。 |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | 64 ビットプラットフォームの実行ファイル/ライブラリに対して true を返します。 |
| static [String](../string/) [get_MachineName](./get_machinename/)() | このコンピュータの NetBIOS 名を返します。 |
| static [String](../string/) [get_NewLine](./get_newline/)() | 現在の環境で設定された改行文字列を返します。 |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | 現在のオペレーティングシステムに関する情報を含む [OperatingSystem](../operatingsystem/) オブジェクトを返します。 |
| static int [get_ProcessorCount](./get_processorcount/)() | 現在のマシンのプロセッサ数を返します。 |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | 現在のスタックトレース情報を含む文字列を返します。 |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | システムディレクトリへのパスを返します。 |
| static int [get_TickCount](./get_tickcount/)() | システム起動以来経過したミリ秒数を返します。 |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | 現在のユーザーのネットワークドメイン名を返します。 |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | 現在のプロセスがユーザー対話モードで実行されているかどうかを判定します。 |
| static [String](../string/) [get_UserName](./get_username/)() | 現在 [Windows](../../system.windows/) OS にログオンしているユーザーの名前を返します。 |
| static [Version](../version/) [get_Version](./get_version/)() | 共通言語ランタイムのバージョンに関する情報を表す [Version](../version/) オブジェクトを返します。このメソッドが返すバージョン番号は実質的にダミーであり、すべてのライブラリクラスが返されたバージョンに従って動作することを意味するものではありません。 |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | プロセスコンテキストにマップされた物理メモリ量を返します。 |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | 現在のプロセスの起動に使用されたコマンドライン引数を含む配列を返します。 |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | 現在のプロセスに関連付けられた、指定された環境変数の値を返します。 |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | 指定された場所から、指定された環境変数の値を返します。 |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | 現在のプロセスに関連付けられた、指定された環境変数の値を返します。 |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | 現在のプロセスに関連付けられた、すべての環境変数名とその値を含む辞書を返します。 |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | 指定された場所から、すべての環境変数名とその値を含む辞書を返します。 |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | 現在のプロセスに関連付けられた、指定された環境変数の値を返します。 |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | 指定されたシステムフォルダーへの完全修飾パスを返します。 |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | 現在のコンピュータ上のすべての論理ドライブ名を含む配列を返します。 |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | WSL の場合にのみ true を返します。 |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | 指定されたディレクトリを現在の作業ディレクトリとして設定します。 |
| static void [set_ExitCode](./set_exitcode/)(int) | 指定された値を現在のプロセスの終了コードとして設定します。 |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | 未実装です。 |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | 未実装です。 |

## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [SpecialFolder](./specialfolder/) | システムの特別フォルダーを表します。 |

## 参照

* 名前空間 [System](../)
* Library [Aspose.Slides](../../)