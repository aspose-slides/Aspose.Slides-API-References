---
title: Environment
second_title: Aspose.Slides for C++ API 참조
description: 환경 서비스. 이것은 인스턴스 서비스를 갖지 않는 정적 유형입니다. 어떠한 방법으로도 해당 인스턴스를 만들면 안 됩니다.
type: docs
weight: 1626
url: /ko/system/environment/
---
## 환경 구조체

[Environment](./) 서비스. 이는 인스턴스 서비스를 갖지 않는 정적 유형입니다. 어떠한 방법으로도 해당 인스턴스를 만들면 안 됩니다.

```cpp
class Environment
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static void [Exit](./exit/)(int) | 현재 프로세스를 종료하고 지정된 종료 코드를 운영 체제에 반환합니다. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | 지정된 문자열에서 찾은 환경 변수 이름을 해당 변수의 값으로 교체하고 결과 문자열을 반환합니다. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | 현재 프로세스를 중단합니다. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | 현재 프로세스를 시작하는 데 사용된 명령줄을 반환합니다. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | 현재 작업 디렉터리의 경로를 반환합니다. |
| static int [get_ExitCode](./get_exitcode/)() | 현재 프로세스의 종료 코드를 반환합니다. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | 종료가 진행 중인지 확인합니다. 구현되지 않음. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | 64비트 플랫폼 실행 파일/라이브러리에 대해 true를 반환합니다. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | 이 컴퓨터의 NetBIOS 이름을 반환합니다. |
| static [String](../string/) [get_NewLine](./get_newline/)() | 현재 환경에 설정된 newline 문자열을 반환합니다. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | 현재 운영 체제에 대한 정보를 포함하는 [OperatingSystem](../operatingsystem/) 객체를 반환합니다. |
| static int [get_ProcessorCount](./get_processorcount/)() | 프로세서 개수 또는 현재 머신의 수를 반환합니다. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | 현재 스택 트레이스 정보를 포함하는 문자열을 반환합니다. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | 시스템 디렉터리의 경로를 반환합니다. |
| static int [get_TickCount](./get_tickcount/)() | 시스템 시작 이후 경과된 밀리초 수를 반환합니다. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | 현재 사용자의 네트워크 도메인 이름을 반환합니다. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | 현재 프로세스가 사용자 인터랙티브 모드에서 실행 중인지 판단합니다. |
| static [String](../string/) [get_UserName](./get_username/)() | [Windows](../../system.windows/) OS에 현재 로그인한 사용자의 이름을 반환합니다. |
| static [Version](../version/) [get_Version](./get_version/)() | 공통 언어 런타임 버전에 대한 정보를 나타내는 [Version](../version/) 객체를 반환합니다. 이 메서드가 반환하는 버전 번호는 실제와 다르며, 모든 라이브러리 클래스가 해당 버전에 맞게 동작한다는 의미는 아닙니다. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | 프로세스 컨텍스트에 매핑된 물리 메모리 양을 반환합니다. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | 현재 프로세스를 시작하는 데 사용된 명령줄 인수를 포함하는 배열을 반환합니다. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | 현재 프로세스와 연관된 지정된 환경 변수의 값을 반환합니다. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | 지정된 위치에서 지정된 환경 변수의 값을 반환합니다. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | 현재 프로세스와 연관된 지정된 환경 변수의 값을 반환합니다. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | 현재 프로세스와 연관된 모든 환경 변수 이름과 값을 포함하는 사전을 반환합니다. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | 지정된 위치에서 모든 환경 변수 이름과 값을 포함하는 사전을 반환합니다. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | 현재 프로세스와 연관된 지정된 환경 변수의 값을 반환합니다. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | 지정된 시스템 폴더에 대한 전체 경로를 반환합니다. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | 현재 컴퓨터의 모든 논리 드라이브 이름을 포함하는 배열을 반환합니다. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | WSL인 경우에만 true를 반환합니다. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | 지정된 디렉터리를 현재 작업 디렉터리로 설정합니다. |
| static void [set_ExitCode](./set_exitcode/)(int) | 지정된 값을 현재 프로세스의 종료 코드로 설정합니다. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | 구현되지 않음. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | 구현되지 않음. |

## 열거형

| 열거형 | 설명 |
| --- | --- |
| [SpecialFolder](./specialfolder/) | 시스템 특수 폴더를 나타냅니다. |

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)